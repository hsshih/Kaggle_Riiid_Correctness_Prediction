# Kaggle_Riiid_Correctness_Prediction
Predict student answer correctness on an AI TOEIC test prep engine in this [Kaggle competition](https://www.kaggle.com/c/riiid-test-answer-prediction). Two methods attempted:

1. Feature engineering + neural network for tabular data from fast.ai (AUC-ROC 0.74, [code](https://github.com/hsshih/Kaggle_Riiid_Correctness_Prediction/blob/main/my-riiid-answer_correctness-rapids-fastai.ipynb))
2. Treat individual student's answers as a time series and use a self-attention model based on the paper [A Self-Attentive model for Knowledge Tracing (Pandey & Karypis 2019)](https://arxiv.org/pdf/1907.06837.pdf) (AUC-ROC 0.764, [code](https://github.com/hsshih/Kaggle_Riiid_Correctness_Prediction/blob/main/Riiid-sakt.ipynb))

Final highest score on leaderboard: 0.82
