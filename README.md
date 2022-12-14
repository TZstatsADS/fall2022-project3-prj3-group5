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

+ Project summary: In this project, we created two predictive models for image classification. For Model I, we built a transfer learning model based on ResNet50 from Keras library with 29% training accuracy. For Model II, we add weakly supervised learning features to the model by correcting the noisy label with CNN architecture, which yielded 52% training accuracy. 
	
**Contribution statement**:
+ All members contributed in developing the approach of model building
+ Sangmin Lee, Yayuan Wang: research on ResNet50, model I development, split test and train on noisy labels
+ Donglai Xu: Research on ResNet50. Write codes and build a transfer learning model as model I. Write codes and build a label cleaner for weakly supervise learning with Yayuan Wang. Generate plots and model description. Clean and anotate all the coding part and complete the test data prediction part. 
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
