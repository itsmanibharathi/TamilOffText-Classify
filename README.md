# offensive_language_classification
### Overview 
This project aims to classify Tamil social media commands as offensive or non-offensive. We employ various methods including traditional machine learning algorithms and Deep learning algorithms. The dataset used for training and evaluation is collected from the HASOC fire 2020 event, comprising diverse social media comments.

### Business Understanding

Offensive text classification in Tamil is crucial for various applications such as social media monitoring, content moderation, and hate speech detection. By accurately identifying offensive language, we can create safer online environments and promote respectful communication.

### Data Understanding
The project utilizes a dataset obtained from HASOC fire 2020, comprising various social media platforms such as Twitter, Instagram, etc. The dataset consists of offensive and non-offensive comments written in the Tamil language.

- Offensive comments: 9381
- Non-offensive comments: 28833

The dataset exhibits class imbalance, with a significantly higher number of non-offensive comments compared to offensive ones. To address this issue, the Synthetic Minority Over-sampling Technique (SMOTE) is employed as a balancing technique. SMOTE helps mitigate the class imbalance problem by generating synthetic samples of the minority class, thus creating a more balanced distribution for training the classification models.

Additionally, the dataset contains some English words interspersed within the Tamil text. To ensure consistency and facilitate analysis, all English words are fully translated into Tamil using the Azure Translator service. This translation process enhances the quality and coherence of the dataset, enabling more effective training and evaluation of the classification models.

<p align="center">
<img src="https://github.com/itsmanibharathi/TamilOffText-Classify/assets/76097762/001d41e6-9cdb-4934-ba09-6d81edb8d919" alt="Dataset count" width="250" height="300" align="left">
<img src="https://github.com/itsmanibharathi/TamilOffText-Classify/assets/76097762/0af2085d-86ea-4880-b495-450b0e74936c" alt="Dataset count" width="250" height="300" >
<img src="https://github.com/itsmanibharathi/TamilOffText-Classify/assets/76097762/6a165e6c-cef3-49e0-96b7-ba1d39d41100" alt="Dataset count" width="250" height="300" align="right" >
</p>

