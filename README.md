# Fine-tuning a Model for Transliteration

## Introduction
You have a Facebook penfriend from Poland. His name is Alexandre, but it's  written as Aleksandre in Poland. Recently, he traveled abroad and posted a photo with Stany Zjednoczone (the United States) as the geolocation. You can't understand where he is since the geolocation is in Polish. This frustrates you, so you decide to fine-tune a transformers model so that all Polish names and toponyms are automatically anglicized (converted to their English equivalents).

---
## Learning Outcomes
In this project, you will learn how to fine-tune a T5 model to convert Polish names and locations into their English (anglicized) equivalents. You will gain practical skills in corpus creation, setting specific parameters for fine-tuning, monitoring the training process, and evaluating fine-tuning results.

---

## Project Structure
```
├── data/# Directory containing the dataset for fine-tuning
│   ├── polish_names.csv # CSV file with Polish names and their English equivalents
│   └── toponyms_of_poland.csv # CSV file with Polish toponyms and their English equivalents
├── anglicization.ipynb # Jupyter notebook for fine-tuning the T5
├── .gitignore # ignored files in version control
└── README.md # Project documentation
```
---

## Prerequisites
- [T5 transformers](https://hyperskill.org/learn/step/36803)
- [Train and test sets](https://hyperskill.org/learn/step/17181)

---

## **The flow**
Fork → Clone → Branch → Implement → PR → Review

* Fork this repo to your own GitHub account
* Create a new branch for each task (e.g., task-1) if applicable (if there is any code that has to be implemented)
* Implement the solution based on the markdown descriptions
* Push the branch to the forked repo
* Create a Pull Request from the fork back to the main repo
* We will review the PR and provide feedback through GitHub