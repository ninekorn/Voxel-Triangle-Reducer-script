# Voxel-Triangle-Reducer-script

it's not really a LOD (level of detail) solution - It's a vertex and triangle reducer for voxel based minecraft chunks.

Using unity 2017.4.26f1 - my script is making faces of minecraft chunks faces merge together as rectangles or square faces to cover larger areas and bring the number of vertices and triangles displayed on the screen to a lower amount.

The chunk creation is based on the old Minecraft tutorial of Craig Perko here https://www.youtube.com/watch?v=YpHQ-Kykp_s&ab_channel=CraigPerko. There are a lot of Triangulation techniques and scripts everywhere that one can use to achieve 3d terrain but i wanted to code my own vertex/triangle reducer without using LOD for this project. It's very basic, and not necessarily useful if there are not a lot of faces on the same axis plane.

thank you for reading me.
steve chassé

This is how the Craig Perko original chunk looks:
<img src="https://i.ibb.co/dGnGqm3/47k-Tris-And28k-Verts-normal-Chunk.png" alt="47k-Tris-And28k-Verts-normal-Chunk" border="0">

I built my own version of a face reducer without changing the LOD (level of detail) and it is still using the Craig Perko old minecraft tutorial way of making the triangles and index and vertex for the chunk. For this chunk seed, the tris are reduced approx 15 fold and the verts reduced by approx 5 times. It's pretty much dependant on how bumpy the terrain is. The unity project image above and below contain other scripts but you only need the one i uploaded to achieve this. it took more than 2 weeks to invent it without references. if someone invented it before me, who knows... probably and they probably have a better algorithm too. i will try and upgrade this later.
<img src="https://i.ibb.co/6bR9fv3/3k-Tris-And6k-Verts-Reduced-Faces-Chunk.png" alt="3k-Tris-And6k-Verts-Reduced-Faces-Chunk" border="0">




