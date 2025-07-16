# Padia Stories

Origin Notes: These consist of fabricated narratives for characters of popular culture franchises, namely “The Witcher” and “Friends”. They were proposed by Kapesh Padia et al. as case studies for “https://doi.org/10.20380/GI2018.05”.
graph features handled: Dynamic, Dynamic (discrete), N-layers
Graph features in papers: clusters (pre-existing),dynamic (discrete),layered graphs,n-layers
Origin Paper: Yarn: Generating Storyline Visualizations Using HTN Planning (https://www.notion.so/Yarn-Generating-Storyline-Visualizations-Using-HTN-Planning-fff01d52e4ad81a9955fe879e1bf4ddf?pvs=21)
Appeared in years: 2018,2019
Type of Collection: Lost/Unavailable
is it stored properly?: No
must be analyzed: No
In repo?: No
Related to Literature - Algorithm (1) (Dataset tag relations): Yarn: generating storyline visualizations using HTN planning (https://www.notion.so/Yarn-generating-storyline-visualizations-using-HTN-planning-76a49c2b1f2541628c6971986bceb008?pvs=21), A system for generating storyline visualizations using hierarchical task network planning (https://www.notion.so/A-system-for-generating-storyline-visualizations-using-hierarchical-task-network-planning-ec16ce5ae8bd43db972e2f77ae829ce3?pvs=21)
cleaned format?: Yes
duplicate?: No
link works?: No
Added in paper: No
Origin paper plaintext: Yarn: Generating Storyline Visualizations Using HTN Planning
Page id: fff01d52e4ad81aab37cfe32b3735f7b
unavailable/skip: Yes
Cleaned ALL data: No
first look: No
Related to Literature - Algorithm (Dataset tag relations) 1: Yarn: generating storyline visualizations using HTN planning (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/Yarn%20generating%20storyline%20visualizations%20using%20HTN%20c2613f33ff704f2eb5092e8db9ab9c28.md), A system for generating storyline visualizations using hierarchical task network planning (../../Literature%20ad87f14e7097454fb2f784e2c8a2797a/Literature%20-%20Algorithm%2012e01bfc60a84007aa7d2d34293e123d/A%20system%20for%20generating%20storyline%20visualizations%20u%202223a30b41a04953890d0d91ecb036c7.md)

# Body

### Descriptions from Literature

From ‘’[Yarn: Generating Storyline Visualizations Using HTN Planning](https://doi.org/10.20380/GI2018.05)”:

> For our first example we use a narrative adapted from the video game Witcher 2 to show the capabilities of Yarn. In our example narrative, the hero, Geralt of Rivia needs to rescue his friend, Triss Merigold, who has mysteriously disappeared. On his journey to find her he must first determine where she was seen last, talk to multiple friends, and resolve a conflict between a troll couple before he can meet her.
There are two choice points in this narrative: first, Margot can either choose to help Geralt or refuse to provide help; second, the troll couple can either accept or reject Geralt’s solution to their conflict. Each of these choices affects the outcome of the narrative creating three possible timelines.
The first timeline contains events favorable to Geralt. In this timeline, Margot agrees to help Geralt and the troll couple accept Geralt’s solution leading him to find Triss. Fig. 5 shows a visualization of this outcome as the reality timeline for our narrative. We can see that Geralt was able to successfully track Triss’s last known location, gather information from friends, resolve a conflict between the trolls, and meet Triss. Note that in this visualization we are showing the default, reality timeline and all links are drawn with 100% opacity. We can also observe all single-entity events in the narrative in this visualization.
In the second timeline, the trolls reject Geralt’s solution to their conflict. Fig. 6 shows a visualization of this unfavorable outcome as diegetic timeline overlaid on top of the reality timeline. While most of the events are same in both timelines, the diegetic timeline ends at the event “Speak to She-Troll.” The reduced opacity of the reality timeline allows the user to compare common sections of the two timelines, even when one of them is smaller than the other.
In the third timeline, Margot refuses to help Geralt preventing him from progressing further on his quest. This is the shortest timeline in our narrative.
> 

From ‘’[Yarn: Generating Storyline Visualizations Using HTN Planning](https://doi.org/10.20380/GI2018.05)”:

> For our second example we use a fictional narrative scenario based on the popular sitcom Friends.
In this narrative, Ross’s plan is to take Rachel on a date. To do so, he must acquire more information about her, find some way of talking to her, ensure she is positively disposed towards him, and eventually ask her out. He can acquire more information about her in a number of ways including calling her mother, or asking Phoebe about her by either call or text. To ensure she is in a positive mood, he can either give her a gift or say nice things to her, and finally he can either ask her out himself or ask for Phoebe’s help. To illustrate causality of events in the narrative timeline, we have set up the operator functions for Rachel such that she is more inclined to say yes to Ross if he talks to her mother rather than requesting Phoebe’s help. Additionally, Rachel’s probability of accepting Ross’s proposal is also dependent on how impressed she is by him when he asks her.
There are four choice points in this narrative: three for Ross, and one for Rachel. The choices made by Ross create 12 alternate timelines, each illustrating a different way in which he can ask Rachel out. Towards the end of each timeline Rachel can decide to either reply yes to Ross, or reply no, creating a total of 24 timelines.
Fig. 7 shows a visualization where Rachel agrees to go out with Ross in both timelines. While the timelines result in the same outcome, and visually look the same, we can inspect the labels on top of the events in Ross’s timeline to identify the differences. Lighter labels correspond to the reality timeline, while darker labels correspond to the diegetic timeline. In the reality timeline, Ross decided to give a gift to Rachel after talking to her mom, while in the diegetic timeline he decided to act friendly with her.
Fig. 8 shows another visualization for the same narrative. In this example we can see the effect of causal conditions set in the operator functions for Rachel. In the reality timeline, Rachel decided not to go out with Ross because he asked Phoebe for help by messaging her. On the other hand, she agreed to go out with him in the diegetic timeline because in this case Ross decided to talk to her mother.
> 

### Example Figures

From ‘’[Yarn: Generating Storyline Visualizations Using HTN Planning](https://doi.org/10.20380/GI2018.05)”:

![Untitled](../../../Benchmark%20datasets%2064e0439269f9497799025562a4087ce1/Padia%20Stories%20c02a38b9ea5e40bfb682ae77e2ac23af/Untitled.png)