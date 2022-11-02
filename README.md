# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2022

+ Team 5
+ Team members
	+ Sangmin Lee
	+ Donglai Xu
	+ Ferra Suryani
	+ Woonsup Kim
	+ Yayuan Wang

+ Project summary: In this project, we created two predictive models for image classification. For Model I, we built a model based on ResNet50 from Keras library with 27% accuracy. For Model II, we explored a transfer learning approach using a pre-trained CNN with VGG16 as the base model and implemented the predicted labels from Model I result, which yielded 57% accuracy. 
	
**Contribution statement**:
+ All members contributed in developing the approach of model building
+ Sangmin Lee, Donglai Xu, Yayuan Wang: research on ResNet50, model I development, split test and train on noisy labels
+ Yayuan Wang, Ferra Suryani, Woonsup Kim (presenter): Develop weakly supervising learning, and add label corrections before implementing model I. 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
