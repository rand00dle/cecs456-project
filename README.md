# cecs456-project

### Randolf Pangilin JR
### Machine Learning Project

# Project Structure

```bash
cecs456-project/
│
├── chest_xray/              # Dataset
├── src/
│   ├── __init__.py          # Marks src as a package
│   ├── data_loader.py       # Loads and preprocesses the dataset
│   ├── model.py             # Defines the neural network model architecture
│   ├── train.py             # Trains and evaluates the model
├── notebooks/
│   ├── code.ipynb          # Main notebook
├── venv/ 
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
```

# How to run the code (if you don't have the dependencies installed in your kernel):
### 1. Create and activate virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # MacOS
venv\Scripts\activate  # Windows
```

### 2. Install Dependencies:

```bash
pip install -r requirements.txt
```

### 3. Use the virtual environment (venv) as kernel in .ipynb
### 4. Run cells in code.ipynb

## Dataset
The chest X-ray dataset is not included in this repository due to size limitations. 
Please download the dataset from [Kaggle Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) and place it in a folder named `chest_xray` in the root directory.

```bash
mkdir chest_xray
```

Once downloaded, the folder structure should look like this:
```bash
project/
│-- chest_xray/
│   ├── train/
│   ├── val/
│   └── test/
```

