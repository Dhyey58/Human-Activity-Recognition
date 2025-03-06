# Human Activity Recognition (HAR)

## Overview
This project focuses on **Human Activity Recognition (HAR)** using smartphone sensor data. The goal is to classify six different activities—**Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, and Laying**—based on data from the accelerometer and gyroscope.

## Dataset
The dataset consists of recordings from **30 volunteers (ages 19-48)** performing the six activities while carrying a waist-mounted smartphone. Sensor readings were collected at **50Hz** and preprocessed for feature extraction.

## Methodology
1. **Data Preprocessing**
   - Applied **noise filtering** using a Butterworth low-pass filter.
   - Extracted **statistical features** from time and frequency domains.
   - Handled missing values and checked for class imbalance.

2. **Exploratory Data Analysis (EDA)**
   - Visualized key sensor features.
   - Analyzed distribution and correlations of activities.

3. **Model Training & Evaluation**
   - Implemented **Random Forest, SVM, and Neural Networks**.
   - Optimized models using **hyperparameter tuning**.
   - Evaluated performance using **accuracy, precision, recall, and F1-score**.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib
- **Machine Learning Techniques**: Classification models, Feature Engineering, Hyperparameter Tuning

## Results & Impact
- **Developed a high-accuracy activity recognition model**.
- **Identified the best-performing classifier** for real-world deployment.
- **Potential applications** in healthcare, fitness tracking, and smart homes.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/human-activity-recognition.git
   cd human-activity-recognition
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train and test models.

## Future Improvements
- Deploying the model for real-time activity monitoring.
- Enhancing feature extraction for improved classification.
- Testing additional deep learning architectures.

## License
This project is licensed under the MIT License.

---
### Contact
For any queries or contributions, feel free to reach out at [your.email@example.com](mailto:your.email@example.com).

