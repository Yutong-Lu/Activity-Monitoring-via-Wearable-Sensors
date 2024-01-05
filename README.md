# Predictive Activity Monitoring via Wearable Sensors
## Authors: Yiran Wang, Yutong Lu, Pourya Momtaz

**Datathon 5, CHL5230, Dalla Lana School of Public Health**

## Introduction
- Investigated using wearable sensor data to predict human activities via deep learning algorithms.
- Aimed to find the best model for accurate activity prediction, crucial for healthcare monitoring and tailored interventions.

## Data Engineering Process
- Utilized sequential sensor data from nine subjects, featuring activity labels and measurements from ankle and arm sensors.
- Preprocessed data by organizing subjects' data, splitting into training and test sets, and generating sequences for LSTM modeling.

## Analysis
- Explored LSTM models with different architectures, learning rates, and regularization techniques.
- Found that a learning rate of 0.001 achieved the best training accuracy, while the model struggled with imbalanced data.

## Findings
- Models performed well in predicting the majority class (Activity 0), indicating challenges with imbalanced data.
- Attempted downsampling and regularization but faced difficulties capturing patterns across all activity classes effectively.

## Conclusion
- LSTM model showed good accuracy but struggled with imbalanced data, particularly predicting other activity classes besides the majority.
Emphasized the need for robust strategies in handling imbalanced data for real-world healthcare applications.

## Resources
- [Presentation slides available](https://docs.google.com/presentation/d/1BpzwK1Uy8BAWsRNJvcCgQnRUCkHRGkVsnPbk_ptQbAY/edit#slide=id.g29d8a77b794_3_57)

## References
- Included references from studies on human activity recognition based on wearable sensor data.
- For more comprehensive details, please refer to the full report available in the provided GitHub repository.






