# Merhaba, ben Osman Karabağ 👋

**Görüntü işleme** ve **veri bilimi** alanlarında çalışıyorum. Derin öğrenme ile görüntülerden anlam çıkaran ve veriden tahmin üreten uçtan uca projeler geliştiriyorum. Modeli eğitmekle kalmıyor, API ve arayüzle kullanılabilir hâle getiriyorum.

- 🖼️ **Odak:** Görüntü sınıflandırma (CNN), görüntü ön işleme, modelin servis edilmesi
- 📊 **Veri bilimi:** Keşifsel veri analizi, öznitelik mühendisliği, gradient boosting, hiperparametre optimizasyonu
- 🤝 **Ekip çalışması:** YZTA Bootcamp'te Scrum Master
- 🔌 **Ek olarak:** Arduino ve IoT ile gömülü sistemler

<p>
  <a href="https://www.linkedin.com/in/osman-karaba%C4%9F/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

## 🛠️ Kullandığım Teknolojiler

**Görüntü işleme / derin öğrenme**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Pillow](https://img.shields.io/badge/Pillow-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Veri bilimi / makine öğrenmesi**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logoColor=black)
![Optuna](https://img.shields.io/badge/Optuna-6A5ACD?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Servis ve dağıtım**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Diğer**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

---

## 🖼️ Görüntü İşleme

### [🌱 AgroKlinik: Yapay Zeka ile Bitki Hastalığı Teşhisi](https://github.com/Sltsn/YZTA-Bootcamp-AgroKlinik)
*YZTA Bootcamp ekip projesi · Scrum Master*

Bitki fotoğraflarından hastalık tespiti yapan web uygulaması.
- TensorFlow ile eğitilmiş **CNN tabanlı görüntü sınıflandırma** modeli
- Görüntü ön işleme hattı: RGB dönüşümü, 224×224 yeniden boyutlandırma, normalizasyon
- **FastAPI** ile `/predict` uç noktası üzerinden gerçek zamanlı tahmin
- Teşhis, şiddet ve tedavi için **Gemini tabanlı 3 ajanlı** öneri sistemi

`TensorFlow` `CNN` `Pillow` `FastAPI` `Gemini` `Multi-Agent`

---

## 📊 Veri Bilimi

### [📉 Telco Müşteri Kaybı (Churn) Tahmini](https://github.com/osmankarabag/telco-customer-churn-prediction)
Telekom müşterilerinin aboneliği bırakıp bırakmayacağını tahmin eden uçtan uca makine öğrenmesi projesi.
- 7.043 müşteri, 21 özellik (IBM Telco veri seti)
- **10 model karşılaştırması**, en iyisi LightGBM: **ROC-AUC 0.84, Recall 0.79**
- Sınıf dengesizliği için `class_weight` ve eşik optimizasyonu
- FastAPI servisi, web arayüzü ve **Docker** desteği

`LightGBM` `XGBoost` `scikit-learn` `FastAPI` `Docker`

### [🧠 Bilişsel Performans Tahmini (Datathon)](https://github.com/osmankarabag/DATATHON)
Uyku, stres ve yaşam alışkanlıklarından bilişsel performans skorunu tahmin eden regresyon hattı.
- Eksik değer ve aykırı değer analizi, encoding, öznitelik mühendisliği
- CatBoost, LightGBM ve XGBoost ile **stacking ensemble**
- **Optuna** ile Bayesian hiperparametre optimizasyonu, OOF RMSE **1.219**

`CatBoost` `LightGBM` `XGBoost` `Optuna` `Ensemble`

### [🤖 Yapay Zeka Çalışmaları](https://github.com/osmankarabag/Artificial-Intelligence-Python)
Veri ön işleme, doğrusal ve polinom regresyon, istatistiksel model seçimi üzerine adım adım çalışmalar.

`pandas` `scikit-learn` `statsmodels` `Jupyter`

---

## 🔌 Gömülü Sistemler ve IoT

| Proje | Açıklama |
|---|---|
| [Arduino Soğutma Sistemi](https://github.com/osmankarabag/Arduino-sogutma-sistemi) | LM35 ile sıcaklık ölçen, 25 kHz PWM ile fanı kontrol eden sistem |
| [MPU6050 + Servo + SD Kart](https://github.com/osmankarabag/IOT-mpu6050-sdkart-servo) | İvmeölçer verisine göre servo kontrolü ve SD karta kayıt (Wokwi) |

## 🧩 Diğer Projeler

| Proje | Teknoloji | Açıklama |
|---|---|---|
| [Mobil Öğrenci Bilgi Sistemi](https://github.com/osmankarabag/mobil-ogrenci-bilgi-sistemi) | Flutter, Firebase | Öğrenci, not ve devamsızlık yönetimi yapan mobil uygulama |
| [Öğrenci Otomasyonu](https://github.com/osmankarabag/Python-ile-ogrenci-otomasyonu) | Python | Öğrenci kaydı, not ortalaması ve harç hesaplama |
| [Bakkal Otomasyonu](https://github.com/osmankarabag/grocery-automation) | Python | Ürün, veresiye ve gelir takibi |
| [Python Projeleri](https://github.com/osmankarabag/beginner_and_intermediate_level_projects_python) | Python | Başlangıç ve orta seviye algoritma ve oyun projeleri |
| [Nesne Tabanlı Programlama](https://github.com/osmankarabag/Nesne-Tabanli-Programlama-OOP-) | Java | Dosya tabanlı öğrenci ve ders otomasyonu |
| [OOP Çalışmaları](https://github.com/osmankarabag/OOP-Project) | Java | Nesne yönelimli programlama ödevleri ve sınav çözümleri |

---

<div align="center">

![GitHub İstatistikleri](https://github-readme-stats.vercel.app/api?username=osmankarabag&show_icons=true&hide_border=true&locale=tr)

</div>
