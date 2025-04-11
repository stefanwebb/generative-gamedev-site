---
draft: true
date: 2025-03-11
categories:
  - Animation
  - Unity
---

# How does Unity retarget humanoid animations?

Unity has a clever solution to the problem of translating animations from one human rig to another. It transforms animations based on the rotation of the model's bones into one based on abstract muscles. I'll explain what joint space and muscle space are for representing poses, how to translate between the two, and how to use them to retarget animations.

<!-- more -->
