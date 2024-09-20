# dolartl_yilsonu_tahmin_projesi

Bu proje, ARIMA modelini kullanarak Dolar/TL kuru tahmini yapmayı amaçlamaktadır. Zaman serisi verilerini analiz ederek, gelecekteki döviz kuru için tahminler sağlar.

## Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerinin kurulu olması gerekmektedir:

- **pandas**: Veri manipülasyonu ve analizi için.
- **numpy**: Sayısal hesaplamalar ve dizi işlemleri için.
- **matplotlib**: Grafiklerle veriyi görselleştirmek için.
- **statsmodels**: Zaman serisi modelleme ve istatistiksel analizler için.
- **pmdarima**: ARIMA modelini otomatik olarak optimize etmek için.
- **scikit-learn**: Model performansı değerlendirme metrikleri için.

Bu kütüphaneleri şu komutla yükleyebilirsiniz:

```bash
pip install pandas numpy matplotlib statsmodels pmdarima scikit-learn
```

## Nasıl Çalıştırılır
1. Proje dosyasını (`Dolar-TL-Predict-Turkish.ipynb`) indirin.
2. Gerekli kütüphanelerin kurulu olduğundan emin olun.
3. Jupyter Notebook'u açın ve tüm hücreleri sırayla çalıştırın. Notebook, her bloğun düzgün bir akışla çalıştırılması için yapılandırılmıştır.

## Proje İçeriği
Proje dört ana bölümden oluşmaktadır:
1. **Veri Yükleme ve Ön İşleme**: Zaman serisi verilerinin hazırlanması ve temizlenmesi.
2. **Model Eğitimi**: Veriler üzerinde ARIMA modelini eğitme.
3. **Tahmin ve Değerlendirme**: Gelecekteki değerlerin tahmini ve modelin performansını değerlendirme.
4. **Sonuçların Görselleştirilmesi**: Tahmin edilen sonuçların grafiklerle gösterilmesi.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Dolar/TL Year-End Prediction Project

This project aims to predict the USD/TRY exchange rate using the ARIMA model. By analyzing time series data, the project provides a forecast for future exchange rates.

## Requirements
To run this project, you need to install the following Python libraries:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations and array operations.
- **matplotlib**: For visualizing data with graphs.
- **statsmodels**: For time series modeling and statistical analysis.
- **pmdarima**: For automatic ARIMA model optimization.
- **scikit-learn**: For performance evaluation metrics.

You can install them using the following command:

```bash
pip install pandas numpy matplotlib statsmodels pmdarima scikit-learn
```

## How to Run
1. Download the project file (`Dolar-TL-Predict-Turkish.ipynb`).
2. Ensure all required libraries are installed.
3. Open the Jupyter Notebook and run all cells in order. The notebook is structured to ensure each block is run sequentially for a smooth workflow.

## Project Contents
The project consists of four main parts:
1. **Data Loading and Preprocessing**: Preparing and cleaning the time series data.
2. **Model Training**: Training the ARIMA model on the data.
3. **Prediction and Evaluation**: Forecasting the future values and evaluating model performance.
4. **Visualization of Results**: Displaying the predictions through graphs.

---
