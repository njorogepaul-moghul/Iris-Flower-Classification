# 🌸 Iris Flower Classification Project

## 📌 Project Overview
This project aims to classify **Iris flower species** (*Setosa, Versicolor, Virginica*) based on their sepal and petal measurements.  
We explored the dataset, engineered new features, trained multiple models, evaluated performance, and finally prepared the models for deployment.



## 📂 Dataset
- **Source:** Iris dataset (Fisher’s dataset)
- **Features:**
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm

- **Target:** Species (Setosa, Versicolor, Virginica)



## 🔬 Feature Engineering
We created additional features to improve predictive power:
- `Petal ratio = PetalLengthCm / PetalWidthCm`
- `Sepal ratio = SepalLengthCm / SepalWidthCm`
- `Petal area = PetalLengthCm * PetalWidthCm`
- `Sepal area = SepalLengthCm * SepalWidthCm`
- `Petal_Sepal_length_Aspect ratio = PetalLengthCm / SepalLengthCm`
- `Compactness = (SepalWidthCm + PetalWidthCm) / (SepalLengthCm + PetalLengthCm)`



## ⚙️ Models Trained
We trained and tested the following models:
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)
5. Gradient Boosting Classifier



## 📊 Model Performance
| Model                | Accuracy | Precision | Recall | F1-score |
|-----------------------|----------|-----------|--------|----------|
| Logistic Regression   | 0.93     | 0.93      | 0.93   | 0.93     |
| Decision Tree         | 0.88     | 0.88      | 0.88   | 0.88     |
| Random Forest         | 0.91     | 0.91      | 0.91   | 0.91     |
| Support Vector Machine| 0.91     | 0.91      | 0.91   | 0.91     |
| Gradient Boosting     | 0.88     | 0.88      | 0.88   | 0.88     |

✅ **Logistic Regression performed best with 93% accuracy**.



## 🔎 Insights
- Strong positive correlations were found between:
  - `PetalLengthCm` and `PetalWidthCm`
  - `PetalLengthCm` and `SepalLengthCm`
  - `PetalWidthCm` and `SepalLengthCm`
- Feature ranges:
  - Sepal Length: 4.0 – 8.0 cm
  - Sepal Width: 2.0 – 4.5 cm
  - Petal Length: 1.0 – 7.0 cm
  - Petal Width: 0.1 – 2.5 cm



## ✅ Conclusion
- We successfully trained ML models to predict Iris flower species.  
- Logistic Regression was the best performer.  
- Our models are now ready for **deployment**.  


## 🚀 Next Steps
- Deploy the best models (Logistic Regression, Random Forest, SVM) in a **Streamlit web app**.  
- Provide a user-friendly interface where users can input sepal & petal dimensions to predict species.

- [** click here to launch Iris flower app**](https://irisflowerapp-ripwlmfmctrzqphjapj97t.streamlit.app/)

