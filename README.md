# Health-Claims-NLP

## 1. Introduction
A health claim is a description of the link between a substance's ingredients and health concerns that is found on food packaging. It can help consumers to make clearer shopping decisions. In order to avoid misleading health claims for consumers, the European Food Safety Authority (EFSA) has established regulations and issued official authoritative health claims to guide manufacturers. However, the fact that each EU member state is individually responsible for the interpretation and implementation of its own local laws and regulations can create new problems for manufacturers and consumers from different linguistic and cultural backgrounds. Therefore, to address this issue, this study uses the standardised automated assessment metric SacreBLEU and compares the translation quality of two multilingual translation models, mBART50 and M2M-100, on multilingual health claims authorised by the EU. In the English to other languages direction, the M2M-100 model scored 36.8 better than mBART50's 31.0, while in the other languages to English direction, the mBART50 model scored 31.9 slightly better than M2M-100's 29.0.


## 2. Steps to execute this Project.
1. All data files for this dataset are placed in the ./Data/ directory.

2. Go to the project folder and use the requirements.txt file to install the packages required to run this project. Run this command "pip install -r . \requirements.txt"

3. Go to ./Reference/, which contains project-related references.

4. Go to the ./munge/ directory and run the health claims.ipynb file, this will generate a distribution map of the dataset and store it in the . /Plot/ directory.

5. In the ./munge/, run the file "Multilingual_translation_models_ipynb", which will perform all the model creation and evaluation work.
