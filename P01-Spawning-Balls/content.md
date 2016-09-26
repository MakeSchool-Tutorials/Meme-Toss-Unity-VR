---
title: "Step 2: Spawn Balls"
slug: spawning-balls
---

Now that you have the core mechanic of the game down, throwing, let's make the objects you throw spawn!

>[action]
Create a chute that spawns balls and obeys the following rules:
>
1. Only 2 Balls may be in the level at one time
>
1. If a Ball falls too far, it gets Destroyed
>
1. Ball spawning happens after a delay, to prevent two balls from spawning in the same location and immediately colliding/exploding away from each other
>
As a hint, some of your logic may want to live in different places, depending on how you want to structure how things talk to each other. If you're having difficulty deciding the *best* way to do this, try focusing instead of which way makes the most sense to *you*.  For example, does it make more sense to have a Chute that counts balls or a Scene Controller that counts balls and tells the chute when to spawn a new one?  Does it make more sense for Balls to Destroy themselves, or does it make more sense for something else to manage that?  Do what you think you will remember later.

If you would like to follow the video, keep in mind that this video goes into the next UI section:
<iframe width="560" height="315" src="https://www.youtube.com/embed/vJVBCRoE6rk" frameborder="0" allowfullscreen></iframe>
