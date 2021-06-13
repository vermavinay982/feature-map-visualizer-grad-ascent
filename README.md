# Weights-Visualizer-for-CNN
What a Neural Network Captures? The filter and feature-maps can be visualized with any image to test with.

Feauture maps closer to the input of model captures a lot of fine detail in the image as we progress deeper in the model, feature map show less detail.


## Heatmaps - What makes Cat different from Monkey
<div>
<img style='display:inline-block;' height=300px width=400px src='outputs/cat_cam.jpg'>
<img style='display:inline-block;' height=300px width=400px src='outputs/elephant_cam.jpg'> 
<img style='display:inline-block;' height=300px width=400px src='outputs/pug_cam.jpg'> 
<img style='display:inline-block;' height=300px width=400px src='outputs/sq_monkey_cam.jpg'> 
</div>
 

## Convnets Filters - What Activates the ConvNet Most
<div>
<img style='display:inline-block;' height=200px width=200px src='outputs/block4_conv1.jpg'>
<img style='display:inline-block;' height=200px width=200px src='outputs/block3_conv1.jpg'>
<img style='display:inline-block;' height=200px width=200px src='outputs/block2_conv1.jpg'>
<img style='display:inline-block;' height=200px width=200px src='outputs/block1_conv1.jpg'>
</div>


## Feature Map on Bird Image - How Input Changes 
  <img style='display:inline-block;' height=400px width=800px src='outputs/bird/loop_bird.gif'>

This pattern was expected as the model abstracts the features from the image into more general concepts that can be used to make a classification still it is not clear from final image the model saw a bird, we generally lose the ability to interpret these deeper feature maps
