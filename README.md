# multimodal-housing-price-prediction
Multimodal ML model that predicts housing prices by combining image features (CNN) with structured tabular data.

##  Objective

* Predict house prices accurately
* Combine visual and structured data
* Explore multimodal learning techniques



##  Methodology

###  Image Processing (CNN)

* Used CNN (ResNet/VGG) for feature extraction
* Extracted deep visual features from house images

### Tabular Data

* Data cleaning and preprocessing
* Feature scaling and encoding

###  Feature Fusion

* Combined image features + tabular features
* Created a unified dataset

### Model Training

* Regression model trained on fused data

### Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)



## Results

* Multimodal model outperformed tabular-only model
* CNN captured visual quality of houses
* Lower RMSE achieved after feature fusion



##  Tech Stack

* Python
* TensorFlow / PyTorch
* Scikit-learn
* OpenCV / PIL




