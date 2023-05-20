# Multi-Label Emotion Classification in Urdu
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dejah-madhusankar/)
##  ML Models to decode compound emotions conveyed in a Urdu-based text 
Welcome to my repo! This is one of my humble attempts at working with common ML Models, with a motive to contribute towards a need-of-the-day issue.

### Purpose
The comfort of anonymity offered by today's social media enables a convenient outspread of hate-speech and incitement to threats. These often target individuals and communities, and worsen users' experience. With over 230 million Urdu speakers generating massive content daily, manual moderation falls short. Thus automated emotion-analysis becomes a demand of high relevance.

## Project Description
This project uses ML algorithms to automate emotion-analysis in the Urdu language. It takes in a piece of Urdu text, and identifies the multiple combination of emotions (hence, multi-label), that may be conveyed by it. The identified emotions are categorised to fall under _Ekman’s six basic emotions and neutrality._

### Repo structure
There are **5 Jupyter notebooks** (written to execute on Google's Colaboratory) each containing the code for training and testing each ML model-combination. I've also uploaded the training and testing data I used during development.

 - [Training Data]()
     - Has 7800 tweets in the Urdu language
     - Contains 8 columns of data. Each Urdu text is accompanied by corresponding emotion-labels (1's signify the presence of a particular emotion)

 - [Testing Data]() - Has 1950 Urdu sentences for testing

### Setup Instructions
1. Go to Google Colab and create a new notebook.
2. Clone the Repository - In a new code cell, type the following command: 
`!git clone https://github.com/dejah22/Multi-Label-Emotion-Classification-in-Urdu.git`
3. Use `cd` to change to the directory of the cloned repository and open the desired `.ipynb` file.

    ### Tips
    1. Install any missing dependencies or required libraries using: `!pip install`
    2. Save your changes back to GitHub

## Project Recognition and Acknowledgments :)
I would first like to thank Avanthika K and Dr. Bharathi B for working on this project with me. Kudos guys!

Upon completion, we submitted out work to Task A - EmoThreat: Emotions and Threat Detection in Urdu, FIRE 2022. I sincerely express my gratitude to them, for letting us adopt their dataset, as well as for supporting our work.
The working-notes of this project has also been published as a [paper](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=10rvNFUAAAAJ&citation_for_view=10rvNFUAAAAJ:u5HHmVD_uO8C) in the FIRE 2022 Conference.

