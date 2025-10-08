## 📊 Dataset Summary

This dataset contains a total of **1,257,388** labeled URL entries.

Feature extraction was performed in accordance with the feature set used in the **ISCXURL2016** dataset, enabling compatibility with prior research and models built on that dataset. Extracted features include lexical characteristics (e.g., URL length, special character counts), domain-related information (e.g., TLD, use of IP addresses), and entropy-based metrics.

## 🏷️ Labeling & Verification

Each URL in the dataset is labeled as one of the following classes:

- `malware`
- `phishing`
- `spam`
- `benign`

The data was collected from various **open-source threat intelligence feeds and public URL blacklists** available on the internet. To ensure label quality and consistency, an additional verification step was applied using a machine learning model **trained on the ISCXURL2016 dataset**. This verification process helped confirm the initial labels or flag inconsistencies based on learned patterns from a well-established benchmark.

While every effort has been made to ensure the accuracy of labels, users should be aware that threat intelligence data can evolve over time, and periodic validation is recommended for critical applications.


## 📚 Citation

If you use this dataset in your research or project, please cite it as follows:

### APA Style

Osmanoğlu, M., Kaya, M. S., Ar, Y., & Özkan, M. (2025). *Malicious URL Dataset*. GitHub. https://github.com/sgmyo-ankara/malicious-url-dataset

### BibTeX

```bibtex
@misc{osmanoglu2025malicious,
  title        = {Malicious URL Dataset},
  author       = {Murat Osmanoğlu and Muhammed Saadetdin Kaya and Yılmaz Ar and Merve Özkan},
  year         = {2025},
  howpublished = {\url{https://github.com/sgmyo-ankara/malicious-url-dataset}},
  note         = {Accessed: 2025-10-08}
}
