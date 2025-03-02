---
layout: default
title: Tinkerings
permalink: /tinkerings
---

# Tinkerings

I enjoy tinkering with technology. Here are some of my cool and fun personal projects. 

## MagiDraw

This project converts drawings into interactive AR games. It is written in Python and OpenCV. It uses constrained Delaunay triangulation to create a mesh of triangles that can be bonded to the provided skeleton. The bonding weights of the triangles are automatically calculated based on the A* algorithm. Animating the drawing involves warping the triangles based on the weighted movement from the skeleton. Making my own drawings move and interacting with them is quite fascinating. Here is the [source code](https://github.com/iicfcii/magi-draw){:target="_blank"}. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/8Le_Ol11Q4Q?si=oMiuXaIvjQCEWwZj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p></p>

## Unrank

I used to play a lot of Overwatch, a competitive team-based FPS game. There are many intricacies involving team fight timing, ability usage, and hero selection. I thought a match data visualizer could be useful and fun to look at for both casual and professional players. For the tool I built, the data is extracted visually from the in-game replay system. Basic image matching using OpenCV was sufficient, but a lot of tuning and tweaks were required. I also built a website to present the match data interactively. The website is developed with React and Grommet. Here is the source code for the [data extractor](https://github.com/iicfcii/unrank){:target="_blank"} and [web visualizer](https://github.com/iicfcii/unrank-web){:target="_blank"}. The website host will archive the site if it remains inactive for a while, so this [link](https://unrank.avosapps.us/demo){:target="_blank"} may not work. If I get time, I might try to switch the host. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/R8Uaf_MqUNs?si=Uv0Dbchi2IxmVXhI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p></p>