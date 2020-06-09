# Grading-the-bowl

Grading the Echogenicity of Fetal Bowel 
 
**Background**: Hyper-echogenicity of the bowel refers to an increased ability of the bowel to reflect sound waves that are transmitted towards
it in an ultrasound screening. In the resulting image acquired from the reflected waves, it is expressed in an unusually bright tissue in
comparison to its surroundings. The anomaly is usually detected in second-trimester sonographies, and is thought to be associated with 
several pathologies. In this repo you can find  my describtion and partially implemention a model to diagnose it. 

• **Objective**: To grade ultrasound images of fetal abdomen according to bowel echogenicity level, within the range 0-6. 
In this project is assumed that the bowel cannot be identified visually in the image, and thus define it as everything within the 
abdomen that is not identified as bones, stomach (labeled in the image below) or clearly visible artifacts\noise.  

• **Input**: Images of fetal (both healthy and pathological) abdomen area, containing the bowel, stomach, bones, amniotic fluid etc. 
you may assume that the number of images is as large as you need for the algorithm to work.
Moreover, you may assume the existence of labels as needed, but my algorithims aims and have ideas to require minimal clinical effort. 

• **Output**: A discrete grading of the bowel echogenicity, ranging from 0 (as dark as the surrounding amniotic fluid) to 6 
(as bright as the bones). 

![GitHub Logo](/bowl.png)
Format: ![Alt Text](url)


