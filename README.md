# Project Overview

**Exploring Sarcasm Dynamics: Insights from Reddit Corpus Analysis**

## About This Project
This project is a Colab notebook exploring sarcasm detection through machine learning techniques, applied to large-scale Reddit comment datasets.  
It demonstrates data preprocessing, manual labeling, model training, and performance evaluation, showcasing skills in Python programming, natural language processing (NLP), and deep learning model development.

---

## Motivation
Understanding sarcasm is crucial for improving natural language processing systems, especially in real-world, noisy environments like social media platforms.  
Applications include:
- **Brand Perception & Market Research**: Companies can better detect genuine customer sentiments on social media, distinguishing between negative comments and sarcastic praise.
- **Political Science & Public Opinion Monitoring**: Analysts can more accurately assess public reactions to policies, speeches, and major events, capturing nuanced opinions that traditional sentiment analysis may miss.

---

## Methodology
- **Manual Labeling**: 2,000 Reddit comments manually labeled for sarcasm.
- **Training with Self-Annotated Dataset**: SARC (Self-Annotated Reddit Corpus) dataset used for large-scale training.
- **Modeling Techniques**:  
  - Multi-Kernel Conv-GRU (Gated Recurrent Unit) model for sarcasm detection.  
  - Comparison with GPT-based models under zero-shot and few-shot settings.
- **Application Extension**:  
  - Investigated potential applications during political elections to better understand voter sentiment containing satire.

---

## Highlights
- Built and evaluated multiple sarcasm detection models.
- Achieved performance improvements by analyzing label quality and dataset characteristics.
- Compared custom models with OpenAI GPT-based sarcasm detection benchmarks.

---

## How to Run
1. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
2. Follow the code cells sequentially.
3. Install necessary packages if prompted.

---

## Requirements
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - tensorflow
  - nltk


## Future Work and Limitations

Dataset limitations (temporal/cultural variability, non-standard sarcasm markers).
Label noise issues in self-annotated corpora.
Need for further adaptation to political and marketing domains.
References

Khodak, M., Saunshi, N., & Vodrahalli, K. (2018). A Large Self-Annotated Corpus for Sarcasm. In LREC 2018.
Gole, M., Nwadiugwu, W. P., & Miranskyy, A. (2023). On Sarcasm Detection with OpenAI GPT-based Models.
And others (see detailed references in the notebook and project presentation).
Contact

Ziyuan Ma
Email: ziyuanma16@gmail.com

