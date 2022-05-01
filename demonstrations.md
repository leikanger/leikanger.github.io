[ [neoRL](index.md) ]   [ [demonstration](demonstrations.md) ]     [ [about the author](./about_the_author.md) ]

-----------------------------------------------------

## Real-time learning videos
The following demonstrations are examples of autonomous navigation in the allocentric
[WaterWorld](https://pygame-learning-environment.readthedocs.io/en/latest/user/games/waterworld.html) environment (not the simpler egocentric javascript-version);
    controlling acceleration in 2 directions, the agent is set to catch green entities while avoiding red.
The agent is initiated at the beginning of the video, with no precursors other than what is described in the listed [articles](./index.md). 

Note that the WaterWorld environment involves temporal dynamics due to intertial mechanics, best described as ``driving on ice''.



------------------------------------------

### Recurrent desires in neoRL networks
A video of recursive desire-structures -- full category II autonomy. 
The first layer learns Q-values according to the place-cell representation. 
When actions have a Euclidean significance, state-action values can be interpreted as a desire vector.
Desire vectors can establish desires for deeper neoRL nodes.

In the experiment shown in the attached video, OVC projection of desire is used as input to the same OVC module.
Two desires govern the PC module and three desires govern the OVC module, with both nodes giving output to agent value function.
Agent design is illustrated in the figure on the left of this page.

<iframe src="https://player.vimeo.com/video/685172019?h=bf434220e7&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" width="496" height="504" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen title="A neoRL agent governed by recurrent desires."></iframe>

----

### Externally supplied desires.

For more Elements-of-Interest (EoI), the navigation challenge becomes difficult;
here mastered by a PC + OVC collaborative neoRL agent with 0th order desires -- where agent desire is directly governed by the location of EoI in each NRES modality.
With all EoI being algorithmically defined, this video demonstrates an agent with category I autonomy.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZyvxaMnm92s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Autonomous desires for 8EoI

For comparison, navigation by autonomous desires is possible, i.e., a full category II autonomy according to the illustration to my left.
8 elements of interest makes this challenge difficult for a human pilot, requiring constant vigilance for longer periods of time.
The neoRL agent is capable of proficient navigation without becoming tired. 
See [Towards neoRL networks; the emergence of purposive graphs](https://ar5iv.org/abs/2202.12622)

<iframe src="https://player.vimeo.com/video/696086825?h=9de753f18f&amp;title=0&amp;byline=0&amp;portrait=0&amp;speed=0&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" width="496" height="504" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen title="Category II autonomy by neoRL graphs."></iframe>
