# Weights-Visualizer-for-CNN
What a Neural Network Captures? The filter and feature-maps can be visualized with any image to test with.

Feauture maps closer to the input of model captures a lot of fine detail in the image as we progress deeper in the model, feature map show less detail.


## Heatmaps - That Shows Triggered Points for Specific Class 
<div>
<img style='display:inline-block;' height=300px width=400px src='outputs/cat_cam.jpg'>
<img style='display:inline-block;' height=300px width=400px src='outputs/elephant_cam.jpg'> 
</div>
 

## Convnets Filters
<img width=400px src='outputs/block4_conv1.jpg'>

## Feature Map on Bird Image
  ![alt text](outputs/bird/feature_map_1_bird.jpg)

This pattern was expected as the model abstracts the features from the image into more general concepts that can be used to make a classification still it is not clear from final image the model saw a bird, we generally lose the ability to interpret these deeper feature maps
