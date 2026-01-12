# Heart Disease Prediction – Veri Analizi Dönem Projesi

Bu proje, **Veri Analizi** dersi kapsamında hazırlanmış bir dönem projesidir. Projede Kaggle platformundan alınan bir kalp hastalığı veri seti kullanılarak **makine öğrenmesi tabanlı bir sınıflandırma problemi** çözülmüştür.

## 📌 Proje Amacı

Bu çalışmanın amacı, hastaya ait klinik ve demografik özellikleri kullanarak **kalp hastalığı riski olup olmadığını tahmin eden** bir makine öğrenmesi modeli geliştirmektir. Proje boyunca ham veriden anlamlı sonuçlar çıkarılmış, veri ön işleme yapılmış ve model performansı akademik metriklerle değerlendirilmiştir.

## 📊 Kullanılan Veri Seti

* Kaynak: **Kaggle – Heart Disease Prediction Dataset**
* Problem Türü: **Sınıflandırma (Classification)**
* Target Değişken: `Heart Disease` (0 = Yok, 1 = Var)

## 🔍 Proje Adımları

### 1️⃣ Veri Keşfi ve Ön İşleme (EDA)

* Veri setinin genel yapısı incelendi (`head`, `info`, `describe`)
* Eksik veriler kontrol edildi ve gerekli temizlik işlemleri yapıldı
* Aykırı değer ve dağılım analizleri gerçekleştirildi
* Görselleştirmeler ile değişkenler arasındaki ilişkiler incelendi
* Özellikler **StandardScaler** ile ölçeklendirildi

### 2️⃣ Model Kurulumu

* **Logistic Regression** algoritması kullanıldı
* Veri eğitim ve test setlerine ayrıldı
* **GridSearchCV** ile hiperparametre optimizasyonu yapıldı
* En iyi model parametreleri belirlendi

### 3️⃣ Model Değerlendirme

Model performansı birden fazla metrik kullanılarak değerlendirildi:

* Accuracy
* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve
* ROC-AUC Score

**Elde Edilen En İyi Accuracy:** %90.83

## 📈 Sonuçlar

Elde edilen sonuçlar, Logistic Regression modelinin kalp hastalığı tahmininde yüksek başarı sağladığını göstermektedir. Model performansı yalnızca doğruluk üzerinden değil, ROC-AUC ve Confusion Matrix gibi metriklerle de çok yönlü olarak değerlendirilmiştir.

## 🛠️ Kullanılan Teknolojiler

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook

## 📂 Repo İçeriği

* `Heart_Disease_Prediction.ipynb` → Proje kodları ve analizler
* `README.md` → Proje açıklaması

## 👤 Hazırlayan

* **Mert Kutlukaya**

## 🔗 GitHub

Bu repository herkese açık (Public) olarak paylaşılmıştır ve akademik incelemeye uygundur.

---

Bu proje, Veri Analizi dersi kapsamında eğitim amaçlı hazırlanmıştır.
