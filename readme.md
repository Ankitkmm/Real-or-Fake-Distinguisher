## 🤖 Machine Learning Process

<img src="https://user-images.githubusercontent.com/54859521/156918096-1516ea9b-59c4-4ab6-a774-d6e660d76a84.png" align="right"  width="28%"/>
<h3> 📊 Getting the Data and EDA Process </h3>

_The dataset was taken from Kaggle and you can find it [here](https://www.kaggle.com/hamzaboulahia/hardfakevsrealfaces)._ <br>

The Dataset contains 1288 faces out of which

- 589 are Real
- 700 are Fake

<br>

The "fake" faces collected in this dataset are generated using the StyleGAN2, which present a harder challenge to classify them correctly even for the human eye.

![image](https://user-images.githubusercontent.com/54859521/156918357-a2c60191-24f4-4bf1-a054-fb005f397968.png)
![image](https://user-images.githubusercontent.com/54859521/156918366-6a5e35e5-7f09-4784-978a-7e7db51649a1.png)

# 📈 Results
The model with least Validation Loss was saved during the training and reloaded before obtaining the final results.
The model was able to classify all of the samples correctly.
Classification Report:


Report Title     precision    recall  f1-score   support

        Real       1.00      1.00      1.00        59
        Fake       1.00      1.00      1.00        70

    accuracy                           1.00       129
   macro avg       1.00      1.00      1.00       129
weighted avg       1.00      1.00      1.00       129
