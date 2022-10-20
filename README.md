# EPSSN
Repository of Learning Pseudo Front Depth for 2D Forward-Looking Sonar-based Multi-view Stereo (IROS 2022).
# Dataset
We make the simulation dataset open source. Three types of data were generated. The artificial scene, the terrain (seabed), and spheres. They were generated using our simulator [here](https://github.com/sollynoay/Sonar-simulator-blender).   
Artificial scene is a simulation of objects in a water tank. There are bricks, concretes, arcs in the water tank.   
Terrain simulates the seabed of oceanic environment. We use the A.N.T lanscape add-on in Blender to generate the terrain.  
Spheres assumes there are submerging objects during robot navigation. Those spheres have the same size, but existed in different positions in the sonar coordiante. 3D reconstruction using a single image cannot solve this problem well considering the ill-posedness. The proposed method using 2~3 images can acquire good results of the position of the sphere.  
Google drive links are as follows.  
[Artificial](https://drive.google.com/file/d/1fhRJKSzRiTdAJbWU2mZppIa9zbfyv5s4/view?usp=sharing)|[Terrain](https://drive.google.com/file/d/1defldD1h6STK11qxvplnIlVJ7cGz3-X1/view?usp=sharing)|[Sphere](https://drive.google.com/file/d/1FmwkCGw9L3ajGjLTahiBeOI-PCk0u101/view?usp=sharing)
