# Rock vs Mine Prediction using Sonar Data

## Project Overview
This project develops a Machine Learning model to classify underwater objects as **Rock (R)** or **Mine (M)** using sonar signal data. Sonar waves reflected from objects are analyzed to identify their type automatically.

## Objective
To build an automated system that accurately distinguishes between rocks and mines using sonar signals, improving underwater safety and detection efficiency.

## Dataset
This project uses the Sonar (Rock vs Mine) Dataset.

- Total Features: 60 numerical attributes
- Target Classes:
  - R → Rock
  - M → Mine
- Each feature represents sonar signal strength at different frequencies

## Technologies Used
- Python
- Jupyter Notebook / VS Code / Google Colab

### Libraries
- NumPy — Numerical operations
- Pandas — Data manipulation
- Scikit-learn — Machine learning model
- Matplotlib / Seaborn (optional) — Visualization

## Algorithm Used
**Logistic Regression**

- Supervised learning algorithm
- Suitable for binary classification
- Predicts Rock or Mine based on sonar signals

## Project Workflow
1. Import required libraries
2. Load the dataset
3. Data preprocessing
4. Feature and label separation
5. Train-test split
6. Model training
7. Model evaluation
8. Prediction on new input

## Results
The model successfully classifies underwater objects with good accuracy and provides reliable predictions for new sonar inputs.

## Applications
- Naval defense systems
- Underwater mine detection
- Marine exploration
- Submarine navigation safety

## Future Scope
- Use larger and real-time datasets
- Apply advanced machine learning techniques
- Integrate with underwater vehicles
- Enable real-time detection systems

## How to Run

1. Install Python (3.x recommended)
2. Install required libraries:

   pip install numpy pandas scikit-learn matplotlib seaborn

3. Download the dataset and place it in the project folder
4. Open the notebook or script
5. Run all cells

## Output
The system predicts whether the input sonar data corresponds to:

👉 Rock  
👉 Mine  

## Author
Mantripragada Varsha Vardhini

