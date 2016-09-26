---
title: "Step 6: Make More Levels + Challenges"
slug: make-levels-challenges
---

You did it!

You've created a feature-complete toss game, and even included some last-minute features to appease your employer!

##**Impotant Note!!!**
If you followed along with the video tutorial, you may have noticed we used a lot of static variables. THIS IS NOT GOOD PRACTICE! Since static variables can be referenced from anywhere and are not reset each scene, it's easy to lose track of code affecting them in larger projects, leading to large headaches. If you did the video tutorial and used static variables, take time right now to refactor your code so that you use normal variables and direct references.

You may have also noticed that we did a lot of copy-pasting of whole Scenes, but never turned our key objects into Prefabs. This means that if we change something like, say, the texture of the Chute, in one Scene, it will *only* change in that one Scene. If, instead, we had made our Chute a Prefab, changing its texture in one Scene would affect *every* Chute in *every* Scene.

That in mind...

>[action]
If you followed the video tutorials, please do the following:
- Remove *all* static variables from your code
- Texture your Ball, and make sure that the change happens to *every* Ball (hint: this will be easier if your Balls are prefabs)
- Add a new level *without* copy-pasting an old Scene.

Now it will be much easier to extend your game and make it truly your own :)  You've fulfilled the basics required of your contract. Now it's up to you to make your game the best VR toss game ever seen!

If you would like to extend your game, here are some suggestions:

1. Make 3 more levels

1. Save the high score permanently and show it to the player before switching levels

1. Add a main menu

1. Create a time-based mode

1. Share the game with a friend and ask "What did you want to do that you couldn't?" and try implementing that new feature
