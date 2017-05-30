---
title: "Toss VR Project"
slug: toss-vr-project
---

The company MakeVRGames LLC has contracted you to create a VR throwing game like arcade hoops or ski ball. Congrats on landing your first VR contract! The company has certain specifications it wants from you, but has also left ample room for you to make any desired modifications in your quest to create the ultimate tossing game. To assist with development, they've broken down their core desired components in steps. Here's a list of their desired deliverables:

**A VR game:**

1. That uses throwing of objects as it's core mechanic
1. That has the player score points by said throwing mechanic
1. That fades to black in between scenes (they've read about that pesky load-screen jittery-ness)
1. That is super-duper alley-ooper fun

Let's get started!

# Picking Up & Throwing

> [challenge]
>
Create a simple scene (just a floor `Quad/Cube` is fine) and import `SteamVR`. Then write a script attached to the hand controllers (in the CameraRig prefab hierarchy) that allows you to pick up and throw objects.

<!--  -->

> [info]
>
You may find it useful to use Trigger Colliders to detect when grabbable objects are in range, and then to parent those objects to your hand when you press whatever buttOn you'd like to use to pick them up. Since your grabbable objects will likely use Rigidbodies, you may also want to toggle their `Is Kinematic` property to prevent forces from being applied while they're held.

<!-- -->

> [info]
>
To find out what info you can get from the Vive controllers, look at the `SteamVR_Controller` script.

<!-- If you're having trouble figuring this out on your own, we've created a video tutorial and [sample project built using the video tutorial's instructions](https://skygnite@bitbucket.org/MakeSchool-Tutorials/meme-toss-unity-vr.git), but **BUYER BEWARE**!  These videos will involve many steps that are **NOT** considered best-practice. If you choose to follow the video instructions, we highly suggest you do the following afterwards:

- Remove *all* static variables from your code
- Texture your Ball, and make sure that the change happens to *every* Ball (hint: this will be easier if your Balls are prefabs)
- Add a new level *without* copy-pasting an old Scene.

![ms-video-youtube](https://www.youtube.com/embed/LtCrdRJwNSY)  -->
