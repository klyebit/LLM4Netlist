# LLM4Netlist

LLM4Netlist is a framework for generating netlist code from natural language descriptions using Large Language Models (LLMs). 
This repository provides the training data, testing data, and data processing scripts used in our experiments.

## 📂 Repository Structure
```
LLM4Netlist/
│── data/
│   ├── train/
│   ├── test/
│   ├── processed/
│── scripts/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│── README.md
```

## 📊 Dataset
### Training Data
The training dataset consists of natural language descriptions and their corresponding netlist code. It is stored in the `data/train/` directory.

### Testing Data
The testing dataset follows the training data format and is in the `data/test/` directory.

### Processed Data
After preprocessing, the processed data of LLMs is stored in `data/processed/`.

## 🔧 Data Processing
To preprocess the dataset, run the following script:
```bash
python scripts/preprocess.py --input data/train --output data/processed/train
```
Similarly, for the test set:
```bash
python scripts/preprocess.py --input data/test --output data/processed/test
```

## 🚀 Training
To train the LLM4Netlist model, execute:
```bash
python scripts/train.py --train_data data/processed/train --output models/
```

## 📈 Evaluation
To evaluate the trained model on the test set, run:
```bash
python scripts/evaluate.py --test_data data/processed/test --model models/best_model.pth
```

## 📬 Contact
For any questions or issues, please open an issue or reach out to me.
