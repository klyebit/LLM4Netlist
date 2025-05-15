# LLM4Netlist

LLM4Netlist is a framework for generating netlist code from natural language descriptions using Large Language Models (LLMs). 
This repository provides the training data, testing data, and data processing scripts used in our experiments.

## 📂 Repository Structure
```
LLM4Netlist/
│── data/
│   ├── example
│   ├── training/
│   ├── testing/
│   ├── processed/
│── script/
│   ├── example
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│── README.md
```

## 📊 Dataset
### Training Data
The training dataset consists of natural language descriptions and their corresponding netlist code. It is stored in the `data/training/` directory.

### Testing Data
The testing dataset follows the training data format and is in the `data/testing/` directory.

### Processed Data
After preprocessing, the processed data of LLMs is stored in `data/processed/`.

<!-- ## 🔧 Data Processing
To preprocess the dataset, run the following script:
```bash
python script/preprocess.py 
```
Similarly, for the test set:
```bash
python script/preprocess.py
``` -->

## 🚀 Training
To train the LLM4Netlist model, execute:
```bash
python script/train.py 
```

## 📈 Evaluation
To evaluate the trained model on the test set, run:
```bash
python script/evaluate.py 
```

## 📬 Contact
For any questions or issues, please open an issue or reach out to me.
