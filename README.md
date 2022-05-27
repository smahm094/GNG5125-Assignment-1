#### *GNG5125 Data Science Applications*
#### *Spring-Summer 2022*
#### *Yinruo Jiang (300274815), Rasheeq Mohammad (6849734) , Shahin Mahmud (300274789)*
#### *Assignment 1: Text Classification*

---

# gng5125_g12_a1.ipynb

Classify the author given a set of texts belonging to the same genre and language.

1. Data Preparation
2. Feature Engineering
3. Modeling
4. Prediction

Note:
* The code can be executed using Jupyter Notebook or Google Colab.
* The contractions and wordcloud Python libraries need to be installed.
* The following texts have been provided in the form of UTF-8 encoded text files (downloaded from Project Gutenberg).
    * pg18458.txt (Star Born written by Andre Norton)
    * pg32825.txt (The Goddess of Atvatabar written by William R. Bradshaw)
    * pg164.txt (Twenty Thousand Leagues under the Sea (slightly abridged) written by Jules Verne)
    * pg62.txt (A Princess of Mars written by Edgar Rice Burroughs)
    * pg139.txt (The Lost World written by Arthur Conan Doyle)

## Requirements

Software:
* Python version: 3.9.12
* Anaconda version: 4.12.0
* Visual Studio Code version: 1.67.2
    * Jupyter
    * Juypter Keymap
    * Juypter Notebook Renderers
    * Pylance
    * Pylint
    * Python
* Google Colab

*The code was developed using the Visual Studio Code IDE, but can be executed in Jupyter Notebook or Google Colab.*

Libraries:
* collections
* contractions (install manually using pip install contractions)
* nltk
* pandas
* random
* re
* seaborn
* sklearn
* unicodedata
* wordcloud (install manually using pip install wordcloud)

## Usage

Given the required Python packages are installed, each section of the code can be executed.
