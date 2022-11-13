---
layout: post
title:  "3D visualization tool for Intel RealSense Depth Camera"
date:   2022-11-11 14:49:20 -0600
categories: research
---

This is a video of 3d visualization tool that I developed to extract key features - such as 3D positions of surgical tools and pegs - from depth camera.
Although Intel provides a native viewer for the RealSense Depth Camera, it was barely usable for research because the results of my algorithm could not be overlaid on the viewer.
This tool is implemented using Qt and OpenGL, and allows me to interactively see the results of my algorithm in real time through mouse and keyboard.

<iframe width="560" height="315" src="https://www.youtube.com/embed/qYSltm59dsE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>