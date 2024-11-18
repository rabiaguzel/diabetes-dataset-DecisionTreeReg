

# Karar Ağacı ile Diyabet Verisi Tahmin Modeli

Bu proje, **diabetes** veri setini kullanarak bir **karar ağacı regresyon modeli** geliştirmeyi amaçlamaktadır. Model, test verileri üzerinde tahminler yaparak performansını değerlendirmektedir. Ayrıca, modelin hiperparametre optimizasyonu için **GridSearchCV** kullanılmıştır.

## Kullanılan Kütüphaneler:
- **NumPy**: Matematiksel işlemler için
- **Matplotlib**: Sonuçları görselleştirmek için
- **Scikit-learn**: Makine öğrenmesi algoritmaları, veri işleme ve model değerlendirmesi için
- **Pandas**: Veri analizi için (eğer veriyi pandas ile işlemek isterseniz)

## Kurulum ve Kullanım

Projeyi bilgisayarınıza indirip çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Gerekli kütüphaneleri yükleyin.
2. Proje dosyasındaki Python betiğini çalıştırın.

## Model Hakkında

Model, karar ağacı regresyonunu kullanarak diyabet hastalarının ilerleyişini tahmin etmektedir. Bu projede, **max_depth**, **min_samples_split**, **min_samples_leaf** gibi hiperparametreler **GridSearchCV** ile optimize edilmiştir.

## Performans
- **MSE**: Ortalama Kare Hatası
- **RMSE**: Kök Ortalama Kare Hatası
  
-----------------------------------------

# Decision Tree Diabetes Prediction Model

This project aims to develop a **decision tree regression model** using the **diabetes** dataset. The model evaluates its performance by making predictions on the test data. Additionally, **GridSearchCV** was used for hyperparameter optimization of the model.

## Libraries Used:
- **NumPy**: For mathematical operations
- **Matplotlib**: For visualizing results
- **Scikit-learn**: For machine learning algorithms, data processing, and model evaluation
- **Pandas**: For data analysis (if you want to process data with pandas)

## Installation and Usage

You can follow these steps to download and run the project:

1. Install the required libraries.
2. Run the Python script in the project directory.

## About the Model

The model uses decision tree regression to predict the progression of diabetes in patients. In this project, hyperparameters like **max_depth**, **min_samples_split**, and **min_samples_leaf** are optimized using **GridSearchCV**.

## Performance
- **MSE**: Mean Squared Error
- **RMSE**: Root Mean Squared Error

