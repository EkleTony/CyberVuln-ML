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

## License
The dataset is released under the **MIT License**. You are free to use, modify, and distribute it with proper attribution. However, if using this dataset in academic or research work, please **cite the following paper**:

```
@inproceedings{ekle2024enhanced,
  title={Enhanced Categorization of Cybersecurity Vulnerabilities},
  author={Ekle, Ocheme Anthony and Ulybyshev, Denis},
  booktitle={2024 IEEE 15th Annual Ubiquitous Computing, Electronics \& Mobile Communication Conference (UEMCON)},
  pages={800--806},
  year={2024},
  organization={IEEE}
}
```

