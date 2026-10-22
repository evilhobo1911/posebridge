# PoseBridge

Pose a physical figure. Get an animation-ready digital pose.

![Figure on the capture turntable](media/01-figure-on-turntable.jpg)

PoseBridge turns hand-posed figures into editable character poses. It tracks
square ArUco tags — the figure is just an armature that holds the tags in a
human-readable pose. Tags on each body segment and around the turntable let a
camera work out where every part is in 3D. PoseBridge solves the joint angles,
builds an editable rig in Blender, and exports the pose for Unreal Engine — a
desk-sized alternative to a motion-capture stage for posing and blocking
animation.

![Solved pose on the Blender rig](media/02-solved-rig-in-blender.jpg)

## What it does

- Captures a posed figure from multiple turntable angles with one camera
- Recovers each body segment's position from its tags
- Solves the full-body joint pose and builds an editable Blender rig
- Exports the pose to Unreal Engine
- Supports two figures in one capture; self-tests check its own accuracy

![The capture setup](media/03-capture-rig.jpg)

## Status

Working in-house tool, used for my game's animation work. Source not released yet.

## Credits

Built with Python, OpenCV and Blender.
Figure: [Dummy 13 v1.0](https://www.printables.com/model/981111-dummy-13-version-10)
by soozafone (CC BY), with my ArUco tag mounts added.

---
© evilhobo1911. All rights reserved.
