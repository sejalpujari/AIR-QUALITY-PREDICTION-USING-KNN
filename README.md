Air Quality Prediction Using KNN
This project aims to predict the Air Quality Index (AQI) using the K-Nearest Neighbors (KNN) algorithm. It utilizes environmental factors like Sulfur Dioxide (SO2), Nitrogen Dioxide (NO2), and Particulate Matter (PM) to predict the AQI and categorize the air quality. The model is built using Python, Scikit-learn, and a simple Tkinter GUI for user interaction.

Features
KNN-based Prediction: Uses K-Nearest Neighbors (KNN) for AQI prediction.
User-friendly Interface: A GUI developed using Tkinter where users can input pollutant levels.
Real-Time AQI Prediction: Predicts AQI based on user-provided pollutant data.
Evaluation Metrics: Includes performance evaluation with R-squared and RMSE values.
Visualization: Displays results using Matplotlib for model comparison.
Requirements
You need to have Python installed along with the following libraries:

scikit-learn
numpy
matplotlib
tkinter (usually pre-installed with Python)
How to Run the Project
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/air-quality-prediction-using-knn.git
cd air-quality-prediction-using-knn
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the GUI:

bash
Copy code
python air_quality_prediction_knn.py
Input pollutant values in the provided input fields and click on the "Calculate AQI" button to get the AQI prediction.

Project Structure
plaintext
Copy code
├── air_quality_prediction_knn.py   # Python script with KNN model and GUI
├── data.csv                        # Sample air quality dataset
├── README.md                       # Project documentation
├── requirements.txt                # Project dependencies
Model Overview
This project uses K-Nearest Neighbors (KNN) algorithm to predict the Air Quality Index (AQI) based on four major pollutants:

Sulfur Dioxide (SO2)
Nitrogen Dioxide (NO2)
Respirable Particulate Matter Index (PM)
Suspended Particulate Matter (SPM)
The KNN model is trained on a dataset and evaluates AQI based on the distance of the input features (pollutant values) from the nearest neighbors in the dataset.

Model Evaluation
R-squared on Train Data: 0.999
RMSE on Test Data: 3.97
Example Usage
Pollutant	Example Input
Sulfur Dioxide (SO2) (µg/m³)	25
Nitrogen Dioxide (NO2) (µg/m³)	30
Respirable Particulate Matter (PM) (µg/m³)	40
Suspended Particulate Matter (SPM) (µg/m³)	50
When these values are entered into the GUI, the model will predict the AQI and categorize it.
