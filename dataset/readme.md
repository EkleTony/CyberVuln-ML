# Dataset Collection

## Data Collection
The dataset was sourced from the CVE Security Vulnerability Database, containing **123,000 records** from **1999 to 2019**. It includes **15 attributes** such as CVE-ID, CVSS score, and attack details. Records with multiple vulnerability types were split, expanding the dataset to **162,789 records**.

## Data Preprocessing
- **Removed missing values** (28,430 records, ~17%).
- **Selected features**: 'CVE Description' as input, 'Vulnerability Type' as label.
- **Encoded labels**: 13 vulnerability types using `LabelEncoder`, resulting in **134,397 records**.

## Text Vectorization
- **Preprocessing**: Lowercased text, removed punctuation, stopwords, and URLs.
- **Tokenization & Lemmatization**: Converted text into root words.
- **TF-IDF Transformation**: Used to weight important terms for classification.

This dataset supports machine learning models for cybersecurity vulnerability classification.


