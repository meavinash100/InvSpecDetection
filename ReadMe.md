### Fast.AI Implementation for the Invasive Species Detection Kaggle Competition
### Using ResNet34 Architecture with PyTorch as Back end

#### Description: 
Tangles of kudzu overwhelm trees in Georgia while cane toads threaten 
habitats in over a dozen countries worldwide. These are just two invasive species of 
many which can have damaging effects on the environment, the economy, and even human health. 
Despite widespread impact, efforts to track the location and spread of invasive species 
are so costly that they’re difficult to undertake at scale.

Currently, ecosystem and plant distribution monitoring depends on expert knowledge. 
Trained scientists visit designated areas and take note of the species inhabiting them. 
Using such a highly qualified workforce is expensive, time inefficient, and insufficient 
since humans cannot cover large areas when sampling.

#### Data & Objective: The data set contains pictures taken in a Brazilian national forest. 
In some of the pictures there is Hydrangea, a beautiful invasive species original of Asia. 
Based on the training pictures and the labels provided, the participant should predict the 
presence of the invasive species in the testing set of pictures. 

* URL: https://www.kaggle.com/c/invasive-species-monitoring/data

#### Summary Results:
* Base model: ResNet34
  * Without precomputation: 92.13% accuracy
  * With precomputation: 90.07% accuracy
  * With Differential Learning Rate: 97.65% accuracy
  * With Test Time Augmentation: 97.81% accuracy
  * Submission on the Test Set(without TTA): 98.64% accuracy
