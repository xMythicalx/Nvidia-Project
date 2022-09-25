# Sports Balls

In this project, we distinguish between different types of balls such as a basketball, rugby/football, soccer ball, and many more. This project is for young kids who don't know what types of balls they're looking at. 

![A tennis ball](![tennis](https://user-images.githubusercontent.com/110697443/192128837-380ad740-b71e-40a1-91ef-70317b3d95df.jpg))

## The Algorithm
This project is made with Jetson Nano. The dataset of this model, a retrained version of ResNet18, contains a large amount of balls. It uses the imagenet program when you run it.
## Running this project

P.S. Follow this link before doing this project --> https://github.com/dusty-nv/jetson-inference/blob/master/docs/building-repo-2.md
1. Go to the web on your monitor and save whatever picture you want under jetson-inference/build/aarch64/bin/images
2. Go to VSCode
3. Go to terminal
4. Use this --> ./imagenet images/[] images/test/{} (Inside [], put the name of the picture that you downloaded(Ex. basketball.jpeg), Inside {}, use a file to output to(Ex. basketball.jpg)
5. Scp the Jetson Nano's output file onto your computer to view the results.

[View a video explanation here](video link)
