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
<!-- To train the LLM4Netlist model, execute: -->
# Model Training: Supported Fine-Tuning Tools & Frameworks
Our model training workflow supports fine-tuning with leading open-source tools and frameworks, enabling flexible and efficient model adaptation.

## Supported Tools & GitHub Links
- [Firefly]([https://github.com/yangjianxin1/Firefly](https://github.com/yangjianxin1/Firefly))
- [unsloth]([https://github.com/unsloth/unsloth](http://github.com/unslothai/unsloth))
- [LLaMA-Factory]([https://github.com/hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory))

## 📈 Evaluation
<!-- To evaluate the trained model on the test set, run:
```bash
python script/evaluate.py 
``` -->

## 📬 Contact
For any questions or issues, please open an issue or reach out to me.


## References
```text
@misc{Firefly,
  author = {Jianxin Yang},
  title = {Firefly(流萤): 中文对话式大语言模型},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/yangjianxin1/Firefly}},
}

@software{unsloth,
  author = {Daniel Han, Michael Han and Unsloth team},
  title = {Unsloth},
  url = {http://github.com/unslothai/unsloth},
  year = {2023}
}

@inproceedings{zheng2024llamafactory,
  title={LlamaFactory: Unified Efficient Fine-Tuning of 100+ Language Models},
  author={Yaowei Zheng and Richong Zhang and Junhao Zhang and Yanhan Ye and Zheyan Luo and Zhangchi Feng and Yongqiang Ma},
  booktitle={Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 3: System Demonstrations)},
  address={Bangkok, Thailand},
  publisher={Association for Computational Linguistics},
  year={2024},
  url={http://arxiv.org/abs/2403.13372}
}
```


