# Sign-Language-Detection
This project is designed to detect sign language gestures using image data and machine learning techniques. It provides a full pipeline for creating a dataset of hand gestures, training a classifier, and running inference on new hand gesture images.

# Project Overview
This project includes Python scripts to collect images for training, preprocess those images, and train a model that can classify hand gestures as sign language characters. The model can be used to detect sign language gestures from real-time images or videos.

# Features
- **Image Collection**: Capture images of hand gestures for different sign language characters.
- **Dataset Creation**: Preprocess and structure the image data for training.
- **Model Training**: Train a classifier to recognize the hand gestures.
- **Inference**: Test the trained model on new images or video feeds.
  
# Installation
1. Clone the Repository <br>
```bash
git clone https://github.com/HenriMichael/Sign-Language-Detection.git
cd Sign-Language-Detection
```
2. Install Dependencies <br>
Ensure you have Python installed, then install the required dependencies from requirements.txt:<br>
```bash
pip install -r requirements.txt<br>
```
3. Run the Project<br>
To collect images for the dataset:<br>
```bash
python collect_imgs.py
```
To create a dataset from collected images:
```bash
python create_dataset.py
```
To train the classifier:
```bash
python train_classifier.py
```
To run inference on new images:
```bash
python inference_classifier.py
```
# Project Structure
- **collect_imgs.py**: Script for collecting images for training.
- **create_dataset.py**: Processes the collected images into a dataset format suitable for training.
- **train_classifier.py**: Trains the machine learning classifier to recognize hand gestures.
- requirements.txt: Lists the dependencies required for the project.
- **inference_classifier.py**: Runs inference on new images to classify hand gestures.
- **requirements.txt**: Lists the dependencies required for the project.
- **data/**: Folder where training data is stored.

# License
This project is licensed under the terms specified in the License file.
