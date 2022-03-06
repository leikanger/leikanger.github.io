[ [neoRL](index) ]   [ [demonstration](demonstrations.md) ]     [ [about the author](./about_the_author.md) ]

-----------------------------------------------------

## Real-time learning videos
Autonomous navigation happens in the allocentric [WaterWorld](https://pygame-learning-environment.readthedocs.io/en/latest/user/games/waterworld.html) environment (not the simpler egocentric javascript-version). 
Learning and execution happens in real-time in the following videos, with the agent being initiated at the beginning of the run (video) with no precursors other than what is described in the above article. 

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

For more Elements-of-Interest, the navigation challenge becomes difficult;
here mastered by a PC + OVC collaborative neoRL agent with trivial desires -- agent desire is directly governed by the location of EoI in each NRES modality.
However, in this experiment, all EoI are supplied by the environment.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZyvxaMnm92s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

