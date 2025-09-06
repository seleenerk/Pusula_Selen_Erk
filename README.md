# Pusula Data Science Case – [Selen Erk]

## 👤 Katılımcı Bilgileri
- **Ad Soyad:** Selen Erk
- **E-posta:** selenerk131410@gmail.com  

##  Proje Özeti
Bu proje, Pusula Internship Data Science Case kapsamında hazırlanmıştır.  
Amaç: Sağlık verileri üzerinde **EDA (Exploratory Data Analysis)** ve **data preprocessing** adımlarını uygulayarak makine öğrenmesine hazır bir veri seti üretmektir.  

Çalışmada:  
- Eksik veriler incelendi.  
- Kategorik değişkenler encode edildi.  
- Çoklu değer içeren kolonlar (KronikHastalik, Alerji, Tanilar, UygulamaYerleri) çoklu-hot encoding ile ayrıştırıldı.  
- Sonuç olarak **model-ready dataset** oluşturuldu.  

##  Dosya Yapısı
Pusula_DS_Starter/
├── data/
│ └── processed/
│ └── model_ready.csv # Model için hazır veri seti
├── notebooks/
│ └── 01_eda_and_preprocessing.py # EDA & preprocessing script
├── requirements.txt # Gerekli Python paketleri
└── README.

## ⚙️ Kurulum ve Çalıştırma
1. Sanal ortam oluştur ve aktif et:
   ```bash
   python -m venv venv
   venv\Scripts\activate    # Windows
   source venv/bin/activate # Mac/Linux

2. Gerekli paketleri yükle:
   pip install -r requirements.txt

3. Script’i çalıştır:
   python notebooks/01_eda_and_preprocessing.py
