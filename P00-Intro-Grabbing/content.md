---
title: "Toss VR Project"
slug: toss-vr-project
---

The company MakeVRGames LLC has contracted you to create a VR throwing game like arcade hoops or ski ball. Congrats on landing your first VR contract! The company has certain specifications it wants from you, but has also left ample room for you to make any desired modifications in your quest to create the ultimate tossing game. To assist with development, they've broken down their core desired components in steps. Here's a list of their desired deliverables:

1. A VR game

2. That uses throwing of objects as it's core mechanic

3. That has the player score points by said throwing mechanic

4. That fades to black in between scenes (they've read about that pesky load-screen jitteryness)

5. That is super duper alley-ooper fun

If you get stuck, you can refer to a finished example project here: [https://skygnite@bitbucket.org/MakeSchool-Tutorials/meme-toss-unity-vr.git](https://skygnite@bitbucket.org/MakeSchool-Tutorials/meme-toss-unity-vr.git)

>[action]
###Step 1: SteamVR Input and Control Setup
>
Create a simple scene (just a floor Quad/Cube is fine) and import SteamVR. Then write a script attached to the hand controllers (in the CameraRig prefab hierarchy) that allows you to pick up and throw objects.
>

Hint: You'll need to use trigger colliders and set things to isKinematic = true/false in your code.
>[info] To find out what info you can get from the Vive controllers, look at the SteamVR_Controller script

If you're having trouble figuring this out on your own, we've created a video tutorial:
<iframe width="560" height="315" src="https://www.youtube.com/embed/LtCrdRJwNSY" frameborder="0" allowfullscreen></iframe>