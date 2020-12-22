# Human-activity-Recognition

Research in the field of Human Activity Recognition (HAR) has gained momentum over the last decade with the advent of wearable sensors that can collect physical data of the user. HAR has applications in multiple fields. Previous studies include performing HAR using multiple sensors or smartphones. But a smartwatch that is worn on the dominant hand gives more sensitive data than smartphone. The main objective of this study is to classify simple and daily life activities using accelerometer data from an easily available smartwatch, along with location information.

This study also proposes the use of location information in order to enhance the performance. The addition of location information has improved the accuracy of the model with every algorithm. Only accelerometer sensor data is used. This is because the type of sensors embedded in a smartwatch may vary from product to product. Although the accuracy can be expected to increase with the increase in the number of sensors, the smartwatch is limited in size and weight. Accelerometer is well suited for measuring hand movements and is built into all smartwatches that are available in market today. In this study the importance of accelerometer data over gyroscope is also shown.

2 models with/without location are performed.
## The algorithms used are:
- Support Vector Machine: ThunderSVM
- Decision Tree: Sklearn
- Random Forest: Sklearn
- Artificial Neural Network: Keras. Hidden Layers 1-8
- SMOTE: imblearn, for balancing datasets

## Accuracy achieved: 
95% for with location model, Random Forest algorithm


