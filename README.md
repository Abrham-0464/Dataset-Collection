Xamtaga-to-English-Translation-Dataset
This repository contains a parallel dataset for machine translation from Xamtaga to English. It includes sentence pairs from various domains, such as religion, education, media, and history, aimed at helping develop and evaluate machine translation systems for the Xamtaga language, which is considered a low-resource language.

Dataset Overview
The dataset was created by collecting parallel data from several sources:

Religious texts: Including the Bible and other religious documents, providing consistent translations.
Elementary school textbooks: Designed for Xamtanga learners, these texts cover a wide range of simple and educational sentences.
News and media: Sourced from the Amhara Mass Media Corporation (AMICO) website, covering formal communication and topics such as politics, sports, and economics.
Historical and cultural documents: Including local newspapers, magazines, and government reports that reflect the culture and history of the Xamtanga-speaking community.
The dataset includes aligned sentence pairs in both Xamtanga and English, making it suitable for training machine translation models.

Dataset Files
xamtaga_to_english_train.csv: Contains the training data with Xamtaga-English sentence pairs.

Usage
Clone the repository:

bash
Copy
git clone https://github.com/username/Xamtaga-to-English-Translation-Dataset.git
Navigate into the repository:

bash
Copy
cd Xamtaga-to-English-Translation-Dataset
The dataset files are stored in the /datasets directory. You can directly use the CSV files for training and evaluating machine translation models.

Example in Python
To load the dataset in Python using pandas:

python
Copy
import pandas as pd

# Load the training data
train_data = pd.read_csv('datasets/xamtaga_to_english_train.csv')
print(train_data.head())
License
This dataset is available under the MIT License. Feel free to use, modify, and distribute the dataset for research and academic purposes, with proper attribution.

Contributions
We welcome contributions to this dataset! If you have additional sentence pairs, corrections, or suggestions, please fork the repository and submit a pull request.
