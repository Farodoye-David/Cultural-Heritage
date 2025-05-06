🏛️ Cultural Heritage Recognition Using Deep Learning
This project uses deep learning to recognize and classify cultural heritage artifacts from images — helping preserve and understand valuable cultural items like sculptures, pottery, and architecture.

⚙️ Installation
# Clone the repository
git clone https://github.com/Farodoye-David/Cultural-Heritage.git

# Navigate into the project directory (ensure the folder name matches the repo)
cd Cultural-Heritage

# Install required Python packages
pip install -r requirements.txt

📁 Dataset
Uses a labeled dataset of cultural artifacts.
I classified the artefacts into 3 major divisions. You can access it through this google drive link - https://drive.google.com/drive/folders/1kVtpl_l_yr8gppgzs3xLtTpLuvLrHRWO?usp=sharing

📊 Results
Achieved seemingly high accuracy in recognizing different classes of artifacts. It will increase when I gather additional dataset and group it correctly.
Classification Report:
                                             precision    recall  f1-score   support

                 Altar and Shrine Objects      0.88      0.83      0.85       214
           Ceremonial Regalia and Objects      0.78      0.76      0.77       147
    Palace Architecture and Ornamentation      0.76      0.83      0.80       180


                             accuracy                           0.81       541
                            macro avg       0.81      0.81      0.80       541
                         weighted avg       0.81      0.81      0.81       541

📌 Future Work
. Support object detection

. Expand dataset coverage

. Deploy as a simple web app
