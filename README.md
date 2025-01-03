# Natural-Disaster-Damage-Identification-Using-CNNs
Natural disaster damage classification using CNNs, identifying six categories with data augmentation, stratified splitting, and class balancing. Optimized with Adam optimizer and evaluated using precision and recall metrics

📋 Project Overview
Natural disasters cause significant damage worldwide. This project leverages deep learning to automate damage classification, helping stakeholders assess and respond efficiently.

Categories:
🌵 Drought
🌍 Earthquake
🌪️ Hurricane
🌄 Landslide
🏡 No Damage
🔥 Wild Fire

🗂️ Dataset
Stratified dataset split into training, validation, and testing sets.
Data Augmentation techniques:
Rotation, flipping, zooming, brightness adjustment, and shifting.
Balancing techniques to handle class imbalance.


🛠️ Model Architecture
CNN with 4 convolutional blocks, max-pooling, and dense layers.
Dropout layer to prevent overfitting.
Final layer: Softmax for multi-class classification.

⚙️ Optimization & Evaluation
Optimizer: Adam with custom hyperparameters.
Metrics: Accuracy, Precision, and Recall for robust performance evaluation.
Utilized class weights to address class imbalance.


🔍 Key Features
Data Augmentation: Enhanced generalization.
Class Weights: Improved performance on minority classes.
Interactive Notebook: View the entire workflow in natural-disaster-damage-classification.ipynb.

🎯 Results
Achieved reliable classification across all categories with an emphasis on precision and recall for disaster-related classes. 🏆

🚀 Getting Started
Requirements
Install dependencies using:
pip install -r requirements.txt

Run the Project
 1. Clone the repository:
git clone https://github.com/reema-abdelrazeq/natural-disaster-classification.git
  2. Open the notebook:
jupyter notebook natural-disaster-damage-classification.ipynb


🙌 Acknowledgments
I acknowledge the following data sources for enabling this project:

🔥 Wildfire
Data Source: Forest Fires - Open Government Portal, Canada.
License: Creative Commons 4.0 Attribution (CC-BY) license Quebec.
Number of Images: 5,089
🌪️ Hurricane
Data Source: Detecting Damaged Buildings Post-Hurricane.
Citation: DOI: 10.21227/sdad-1056
Original Paper: ArXiv: 1807.01688
Number of Images: 5,111
🌄 Landslide
Original Dataset: Created by IARAI for landslide4sense 2022. The dataset initially included images without annotations.
Current Version: Simplified and cleaned to remove zero annotation masks.
Number of Images: 1,980
🌍 Earthquake
Data Source: Satellite and UAV images sourced from the HGM KURE application and screenshots from Google Maps.
Dataset Composition:
Damaged buildings: 1,237 images
Undamaged buildings: 1,498 images
Total: 2,735 images
Citation:
Tasci, B., Acharya, M. R., Baygin, M., Dogan, S., Tuncer, T., & Belhaouari, S. B. (2023). Inception and concatenation residual block-based deep learning network for damaged building detection using remote sensing images. International Journal of Applied Earth Observation and Geoinformation, 123, 103483.
Number of Images: 1,237
You can explore the complete dataset used in this project on Kaggle: https://www.kaggle.com/code/reemaabbelrazeq/natural-disaster-damage-identification-using-cnns

📧 Contact
Have questions? Reach out at reemaabdelrazeq5@gmail.com.

🌟 Don't forget to give this repository a ⭐ if you find it helpful!
