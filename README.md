# aygaz_ai_bootcamp
Aygaz AI Bootcamp'te yapmış olduğum görüntü işleme temelli yapay zeka projem

---

# Proje Adı: CIFAR-10 Veri Seti ile Özel CNN Modeli Eğitimi

Bu proje, CIFAR-10 veri seti üzerinde özel olarak tasarlanmış bir Convolutional Neural Network (CNN) modeli kullanarak bir sınıflandırma görevi gerçekleştirir. Bu README dosyası, projenin yapısı, gereksinimleri ve kullanımı hakkında bilgi sağlamak için oluşturulmuştur.

## Veri Seti

Bu projede CIFAR-10 veri seti kullanılmıştır. CIFAR-10, 10 farklı sınıfa ait 60,000 renkli (32x32 piksel) görüntüden oluşan bir veri setidir. Veri seti içerisindeki sınıflar arasında uçak, araba, kuş, kedi, geyik, köpek, kurbağa, at, gemi ve kamyon gibi nesneler bulunmaktadır.

##Gerekli Kütüphaneler:
- numpy 
- pandas 
- matplotlib
- seaborn 
- tensorflow 
- sklearn.model_selection'dan train_test_split, cross_val_score, GridSearchCV
- sklearn.metrics'ten accuracy_score, f1_score, recall_score, precision_score, confusion_matrix, roc_curve, roc_auc_score, auc
- keras
- keras.datasets'ten cifar10
- tensorflow.keras.utils'ten to_categorical
- tensorflow.keras.models'ten Sequential
- tensorflow.keras.layers'dan Dense, Conv2D, MaxPooling2D, Flatten, Dropout
- tensorflow.keras.optimizers'ten Adam
- sklearn.metrics'ten classification_report


## Veri Ön İşleme

- Veri seti X_train, y_train, X_test ve y_test olarak bölünür.
- Bölünmüş verilerin boyutları yazdırılır.
- Veri seti içindeki görüntülerin boyutları yazdırılır.
- Veri seti içindeki görüntüler görselleştirilir.
- Veriler normalize edilir.

## Model Oluşturup Eğitme

Bu adımda, özel olarak tasarlanmış bir CNN modeli kullanılarak veriler eğitilir. Model, veri setindeki görüntülerin özelliklerini öğrenerek sınıflandırma görevini gerçekleştirir.

## Kullanım

Proje dosyasını açarak Colab veya Jupyter Notebook ortamında çalıştırabilir ve kodları inceleyebilirsiniz. Kod hücrelerinin yanındaki açıklamaları okuyarak projenin adımlarını takip edebilirsiniz.

## Notlar

- Proje dosyası "Proje.ipynb" adıyla Colab ortamında bulunmaktadır.
- Gerekli kütüphaneler projenin başında yüklenmelidir.
- Veri seti olarak CIFAR-10 kullanılmıştır.

---
