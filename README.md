# Pusula_Gokay_Gol
GÖKAY GÖL gokaygol2@gmail.com

 Proje Açıklaması:
Bu proje, ilaçların yan etkilerini analiz etmek ve bu yan etkileri tahmin edebilecek makine öğrenmesi modelleri oluşturmak amacıyla geliştirilmiştir. Proje kapsamında verilen veri seti üzerinde *Keşifsel Veri Analizi (EDA)* yapılmış, veriler işlenmiş ve farklı makine öğrenmesi algoritmaları uygulanmıştır. Sonuç olarak, en yüksek doğruluğa sahip model belirlenmiştir.

Dosya Yapısı:
- *Side_Effect.ipynb*: Tüm analizlerin ve modelleme işlemlerinin yer aldığı Jupyter Notebook dosyası.
- *RandomizedSearchCV*: En iyi modelin kaydedildiği pickle dosyası.

Kullanılan Kütüphaneler:
Bu projede kullanılan Python kütüphaneleri şunlardır:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Projenin Kurulumu:

Projeyi çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. Gerekli Python kütüphanelerini yükleyin:
    bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    
2. *Side_Effect.ipynb* dosyasını bir Jupyter Notebook veya Colab ortamında açın ve adım adım çalıştırın.

3. Eğer en iyi modeli yükleyip kullanmak isterseniz, aşağıdaki gibi pickle dosyasını yükleyebilirsiniz:
    python
    import pickle
    model = pickle.load(open("RandomizedSearchCV", "rb"))
