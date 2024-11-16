# CS230-Project
Multitask Deep Learning for Depth Estimation and Object Classification


We aim to investigate distance estimation and object classification for commonly encountered street objects (cars, trucks, trash cans, etc). Our proposed pipeline will allow computers to analyze RGB images, and infer from the data both how far away each pixel is from the camera, and what the object in the image is. We propose a multitask learning model that enables prediction of both how far away each pixel is away from the camera, as well as what the camera is looking at. Importantly, we train on a Redwood 3D Scan, a dataset collected by civilians equipped with RGB-D cameras; we hope it will be optimal for everyday robotics use cases where accurate and complete knowledge of the surrounding objects is crucial. 
