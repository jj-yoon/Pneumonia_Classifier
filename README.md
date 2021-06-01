# Overview

The contents of this repo show the development process of an image classification model with deep learning to identify pediatric patients' chest x-ray images as normal (pneumonia negative) or sick (pneumonia positive). The model utilizes convolutional neural networks achieving accuracy ratings of 95%. The model is also tuned to reduce the amount of false negatives so that no one suffers from the misdiagnosis.

## Problem

According to the United Nations Children's Fund (UNICEF), more than 800,000 children die of pediatric pneumonia worldwide each year. Pneumonia is an infection of the lung's air sacs (inflammation of the alveoli). The symptoms of pneumonia vary amongst affected individuals ranging from cough (with mucous), fever, shortness of breath, fatigue, nausea/vomiting, and/or confusion. Diagnosis of pneumonia requires examination of medical history, physical state, and a combination of diagnostic tests. Although a straightfoward process, infants and children are much more difficult to diagnose because they are unable to communicate and many of the diagnostic tests are invasive. On a worldwide scale, many of the tests are not as accessible because of the costs.

## X-Ray Image Classification

Machine learning can quickly diagnose pediatric pneumonia with non-invasive x-ray imaging and image classification models. Although the process of training the models are time-consuming, the accuracies of the sophisticated models will help save time when diagnosing patients and performing further research.

### The Data

[Data](https://data.mendeley.com/datasets/rscbjbr9sj/3) consists of pediatric x-ray chest images that are presorted into normal and pneumonia labelled directories.

[Example of Normal]

[Example of Pneumonia]

### The Model

The model is made up of convolutional layers that identify features of the image tensors that run through the filters. The images then pass through the remaining hidden layers before the classification ends.
[tensor]
[process]
[stats]

## Conclusion

Use X-Ray Imaging with CNN for quick, accurate, and noninvasive diagnosis.
Future Developments:
Increase Training Data  Increase Accuracy
Further Research on Trends
Build onto Model for Other Applications (COVID)