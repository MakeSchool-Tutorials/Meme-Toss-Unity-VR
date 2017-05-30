---
title: "Step 3: Scoring and UI"
slug: scoring-points
---

You should now have a `Chute` that spawns `Balls`, but never too many. You should be able to pick up and throw your `Balls`, and when they fall too far, they should die and new balls should appear.

Now we want a `Goal` that awards points when hit, and some UI to display the score to the player. After a certain number of throws, the game should advance to the next level. Oh, and feedback is important, so... be sure to give the players some visual feedback when a `Ball` hits the `Goal`. Something flashy. Something groovy.

This is a *lot*, so we're going to suggest some steps that will make it less daunting and more manageable.

## Add the UI

> [challenge]
>
Create the score's UI display. For now, set some debug control you can use to increment the score, so that you can hop into VR and see the score going up.
>
As a hint, we suggest creating a Canvas with a Text child and setting the Canvas to be in World Space and be veeeeeeery very scaled down (0.01 ought to do it).

If we were not building in VR, we would suggest simply logging this information, but, because we are in VR, the default console is inconvenient to view, unless you're pair-programming and can always have someone looking at the console to report values.

# Add the goal

> [challenge]
>
Now create a Goal that, when hit by a ball, awards a point to the score!  You can turn off your debug score-incrementing logic now, if you were using any.

We're almost there.

# Spawn a new ball

> [challenge]
>
Make the Balls get Destroyed when they touch the Goal. Be sure that new Balls spawn when old ones die!

# Scoooooooooooore!

Now you have the basic scoring mechanic, so we can move on to fancier things.

> [challenge]
>
Create some ball-counting UI to display the current ball count, and then implement logic to advance the Scene after a certain number of Balls have been Destroyed. Can you think of a good way to break this step down into smaller steps?
>
This task, by the way, also adds the implicit task of creating a new level to load in the first place. If you'd like, you can add a visual indicator to your Scene, a log statement, or something else placeholder to say "my code that switches Scenes would get called here, but I haven't implemented it yet," and then you can do that later.

Finally, let's add some feedback.

# Getting flashy

> [challenge]
>
Add a visual and/or auditory effect that plays when a Ball hits the Goal, thus scoring a point. If your method involves creating objects in the Scene, be sure that those objects get Destroyed and don't exist forever, or that they get reused. Overpopulating the Scene is generally not a great idea.
>
If you're not sure what would make a good effect, try a Particle System! If you're feeling like using a Particle System, but don't necessarily want to create your own, you can find some great ones on the Asset Store, many of them for free, and/or in the `ParticleSystems` Standard Assets package!

<!-- For video assistance, see the following:

![ms-video-youtube](https://www.youtube.com/embed/vJVBCRoE6rk)

![ms-video-youtube](https://www.youtube.com/embed/ru1J9isOYSk)  -->
