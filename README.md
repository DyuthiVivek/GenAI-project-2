## Thermal to RGB

Create a HuggingFace user access token and add it in the files.

1. `thermal-data-preprocessing.ipynb`: contains the data pre-processing.
Add this kaggle dataset https://www.kaggle.com/datasets/deepnewbie/flir-thermal-images-dataset/data as an input to the file.
2. `thermal-rgb-controlnet-training.ipynb`: contains the ControlNet training code.
3. `evaluation.ipynb`: contains code for qualitative and quantitative evaluation for the trained ControlNet models.
4. `thermal_rgb_controlnet_demo`: contains code for the demo gradio application for inference on the trained model.

## Sketch2Webpage

1. `synthetic.ipynb`: contains code to create the synthetic dataset from original HTML files (https://huggingface.co/datasets/SALT-NLP/Sketch2Code).
2. `sketch2webpage-controlnet original preprocess.ipynb`: contains code to pre-process original dataset and create a dataset which can be used by the model. Inputs to this code are the original dataset (https://www.kaggle.com/datasets/soardraspi/sketch2code-dataset-v1-cleaned) and the CSV file with pairs (https://www.kaggle.com/datasets/soardraspi/sketch2webpage-pairs-csv). Final dataset can be found here: https://huggingface.co/datasets/swetha3456/sketch2webpage-dataset-v2
