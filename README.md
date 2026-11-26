# Cat breed classification

This notebook compares three image classification models on photographs of American Bobtail, Domestic Long Hair and Domestic Medium Hair cats.

## What is in the repo

- `cat.ipynb` — dataset split, model training and evaluation in Google Colab
- `cat.html` — exported notebook for reading without Colab

The notebook splits the images into training, validation and test sets (70/15/15), then trains ResNet50, DenseNet121 and MobileNetV3Small with TensorFlow/Keras. It includes plots and confusion matrices for comparing the models.

## Running the notebook

Open `cat.ipynb` in Google Colab, upload the dataset as `cat.zip`, and check that extraction creates `/content/cat/` with one folder per breed. Run the cells in order. The notebook expects a Colab environment and uses paths under `/content/`; it has not been packaged as a standalone app.

The dataset archive is not included in this repository. Results in the notebook are from its saved run and may differ when retrained. Before using the models elsewhere, document the dataset source and licence, pin dependency versions, and validate predictions on an independent dataset.
