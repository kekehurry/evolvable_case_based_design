# Evolvable-Case-based-Design

This repository is the interface of the evolvable case-based design system: an AI support system for urban morphology generation. This system can automaticllay learn the morphological pattern in the datasets and allows users to untorl the floor space index(FSI) and ground space index(GSI) of the generated results.
 
The dataset and pretrained checkpoints is available at: 
[Baidu NetDisk (code:esi4)](https://pan.baidu.com/s/1adqooxSNpH4T7rpmq14nYA) or [Dropbox](https://www.dropbox.com/scl/fo/a3rekgah7au7t7k71kxrd/AK4QI30rER6Jhpb4n3Xv5LM?rlkey=zjd2gp0vczpbj627uunw6fnv9&st=4xtww64e&dl=0)

# 1 Installation
``` 
pip install -r requirement.txt
``` 

# 2 Usage
+ download the repository.
+ download the pretrained checkpoints and place them inside "checkpoints\Shenzhen".
+ run the interface:  
``` 
streamlit run app.py
``` 
![interface](/static/interface.jpg)

# 3 Project Contributor and Contact
This project is supervised by Professor Yubo Liu (liuyubo@scut.edu.cn) and Associate Professor Qiaoming Deng (dengqm@scut.edu.cn). Kai Hu (arhukai@mail.scut.edu.cn) provided technical support for algorithms and data collection. If you have any questions regarding to this project, please feel free to contact the authors.

# 4 Cite Our paper
```
@article{liu2024,
  title = {Evolvable Case-Based Design: {{An}} Artificial Intelligence System for Urban Form Generation with Specific Indicators},
  shorttitle = {Evolvable Case-Based Design},
  author = {Liu, Yubo and Hu, Kai and Deng, Qiaoming},
  year = {2024},
  month = oct,
  journal = {Environment and Planning B: Urban Analytics and City Science},
  volume = {51},
  number = {8},
  pages = {1742--1757},
  issn = {2399-8083, 2399-8091},
  doi = {10.1177/23998083231219364},
}
```
