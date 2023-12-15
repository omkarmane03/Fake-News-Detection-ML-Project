# Fake News Detection ML Project

Fake news on different platforms is spreading widely and is a matter of serious concern, as it causes social wars and permanent breakage of the bonds established among people. A lot of research is already going on focused on the classification of fake news.
Here we will try to solve this issue with the help of machine learning in Python.
Before starting the code, download the datasets.

## Workflows

Steps to be followed:
1. Importing Libraries and Datasets
2. Data Preprocessing
3. Preprocessing and analysis of News column
4. Converting text into Vectors
5. Model training, Evaluation, and Prediction


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/omkarmane03/Fake-News-Detection-ML-Project
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n summary python=3.8 -y
```

```bash
conda activate summary
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


```bash
Author: Omkar Mane
Data Scientist
Email: omkarmane009@gmail.com

```
## Prediction:
### Input:
NOGALES, Arizona, Dec 15 (Reuters) - Her daughter's school shut down, Yomara said, after a shootout between rival gangs competing for control of drug and migrant trafficking routes in their southern Mexican town of Chicomuselo. Then, she said, produce vendors cleared out of the market after they faced demands to affiliate with the gangs; she feared her husband Carlos would be forcibly recruited if he turned up for his job on a construction site.

### Output:
LR Prediction: Not A Fake News 
DT Prediction: Not A Fake News 
GB Prediction: Not A Fake News 
RF Prediction: Not A Fake News

Absolutely right; the prediction is correct.

The model we have made is producing accurate results, considering the accuracy of all the models, which was almost 99%, so we can say machine learning can be used as a tool for detecting fake news.


### Conclusion:
Fake news detection using machine learning algorithms is a promising approach to combating fake news. Machine learning algorithms can analyze large datasets and identify patterns that are commonly found in fake news articles. By detecting fake news articles before they are widely disseminated, machine learning algorithms can prevent the harm caused by fake news. However, it is important to use diverse datasets and other techniques, such as fact-checking, to verify the authenticity of news articles.