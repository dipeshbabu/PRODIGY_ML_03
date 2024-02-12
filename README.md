Cat vs. Dog Image Classification with SVM

This repository contains a Python notebook demonstrating a simple image classification task using a Support Vector Machine (SVM) classifier. The TensorFlow "cats_vs_dogs" dataset is utilized for training and testing. To address potential memory issues, a percentage of the dataset is loaded, and images are resized and flattened on-the-fly to reduce memory consumption. Hyperparameter optimization is performed using random search with cross-validation. The SVM model is trained, and its accuracy is evaluated on a test set.

## Dependencies

- Python 3.x
- TensorFlow
- TensorFlow Datasets
- scikit-learn
- OpenCV (opencv-python)

Install dependencies using (if not installed):

```bash
pip install tensorflow tensorflow-datasets scikit-learn opencv-python
```

````

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/dipeshbabu/PRODIGY_ML_03.git
   ```

2. Navigate to the project directory:

   ```bash
   cd PRODIGY_ML_03
   ```

3. Run the notebook:

   ```bash
   jupyter notebook PRODIGY_ML_03.ipynb
   ```

   Make sure to run the notebook in an environment that supports GPU acceleration for faster execution.

## Configuration

- Adjust the percentage of the dataset loaded in the `split` argument of `tfds.load` based on your available memory.
- Modify hyperparameter ranges and distribution in the `param_dist` dictionary for random search in the code based on your experimentation.
````
