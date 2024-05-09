#LLM-TWEEP Classifier : Using Gemini and GPT to Classify Tweepfake Tweets 


## Overview
This repository hosts the materials and findings of our project that evaluates and compares the performance of two state-of-the-art large language models, GPT-3.5 Turbo and Gemini, in classifying AI-generated and human-generated texts. Conducted as part of Major Project at IGDTUW, under the supervision of Dr. Ankita and Dr. Rishbah Kaushal.

## Project Description
With the increasing integration of AI-generated content into digital communications, especially on social media, distinguishing between human and AI-generated texts has become a significant challenge. This project investigates the effectiveness of the GPT-3.5 Turbo and Gemini models in this domain, utilizing various metrics and scenarios to assess their accuracy and reliability.

### Objectives
- Evaluate and compare the accuracy, precision, recall, and F1-score of the GPT-3.5 Turbo and Gemini models.
- Analyze the performance of each model under different classification scenarios, particularly in handling ambiguous categories such as 'Foul Language' and 'Cannot Say'.
- Identify the most suitable model for AI content moderation in social media environments based on specific performance criteria.

## Methods
We utilized the TweepFake dataset, which comprises both human and AI-generated tweets, to test the models' classification capabilities. Google Colab was employed for its GPU support to efficiently manage the computational demands of the project. The models were evaluated across five different scenarios:
1. Exclude ‘Foul Language’ and ‘Cannot Say’.
2. Map ‘Foul Language’ as Human and ‘Cannot Say’ as AI.
3. Map ‘Foul Language’ as AI and ‘Cannot Say’ as Human.
4. Map both ‘Foul Language’ and ‘Cannot Say’ as Human.
5. Map both ‘Foul Language’ and ‘Cannot Say’ as AI.

## Results
Both models showed robust performance; however, they exhibited distinct advantages and limitations across different scenarios:
- GPT-3.5 Turbo was generally more effective at identifying AI-generated content but had a higher rate of false positives.
- Gemini was more conservative, leading to fewer false positives but at times missed identifying AI content.

## Conclusions
The study concludes that the selection between GPT-3.5 Turbo and Gemini should be based on the operational needs—whether the focus is on maximizing AI content detection or minimizing false positives.

## Repository Structure
- `Dataset/` - Contains the datasets used.
- `Code/` - Python scripts and Jupyter notebooks for analysis.

## Usage
Details on how to set up and run the analysis scripts are provided in the `scripts/` directory.

## Acknowledgements
Special thanks to Dr. Ankita and Dr. Rishabh Kaushal, Information Technology Department, and Indira Gandhi Delhi Technial University For Women for their support and guidance throughout this project.


## Contact
For queries, please reach out:
- Hiteshi 
- Email: hiteshi012802@gmail.com
- GitHub: @hiteshi10

- Shreel Trivedi 
- Email: shreel2020@gmail.com
- GitHub: @shreel143

We hope this repository serves as a useful resource for those exploring AI-driven content analysis. Feel free to use and adapt these materials for your own research or projects.
