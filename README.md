# 3D Graphics Application

This repository is for term project ISDN5300 Advanced Digital Design.
Student: TRUONG Quang Trung


# Introduction

First, we run object segmentation which is processed by the baseline, mentioned in the report. 
Second, we run this **graphics application** which includes showing video segmentation and visualizing 3D objects which correspond to target objects.

# How to run:
**Server:** We need to run a port on localhost. I provide many ways for this purposes, up to you machine.
Node.js http-server
Node.js has a simple HTTP server package. To install: npm install http-server -g
To run (from your local directory): http-server . -p 8000
 
Python server: If you have Python installed, it should be enough to run this from a command line (from your working directory):
- Python 2.x
	>python -m SimpleHTTPServer
 
- Python 3.x
	>python -m http.server
 
This will serve files from the current rendering project directory at localhost under port 8000, i.e in the address bar type: http://localhost:8000 with html files as follows.

- Visualize segmentation results:
	>css3d_youtube.html
- 3D object visualization
	>webgl_gpgpu_birds_gltf.html
