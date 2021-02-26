# Neural Style Transfer Implementation
Implementing 'A Neural Algorithm of Artistic Style' paper in Tensorflow/Keras.   
I took on this project to help further my understanding of how neural networks work.

### Original Images:
#### Style image:
"Rain's Rustle" by Leonid Afremov

<img src = "https://github.com/kathleenisrad/style-transfer-implementation/blob/main/images/style_images/starry_night.jpg"> 


#### Content image:
Random cat image I found online
<img src = "https://github.com/kathleenisrad/style-transfer-implementation/blob/main/images/content_images/cat.jpg"> 


### Visualizations of images at different convolutional layers
In the paper, they visualize the outputs of the VGG19 model at different layers, so I do the same with my images:  

#### Style image:
> From left to right, top to bottom: Visualizations of the style image at   
> 'block1_conv1', 'block2_conv1', 'block3_conv1', 'block4_conv1', 'block5_conv1'

<img src = "https://github.com/kathleenisrad/style-transfer-implementation/blob/main/assets/style.png">


#### Content image:
> From left to right, top to bottom: Visualizations of the content image at   
> 'block1_conv1', 'block2_conv1', 'block3_conv1', 'block4_conv1', 'block5_conv1'

<img src = "https://github.com/kathleenisrad/style-transfer-implementation/blob/main/assets/cat.png">
