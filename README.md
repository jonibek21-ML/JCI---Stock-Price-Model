# JCI-Stock-Price-Model
# 📈 Aksiya narxini bashorat qilish (RNN, LSTM va GRU yordamida)

Ushbu loyiha **Deep Learning** asosida aksiya narxlarini bashorat qilishni ko‘rsatadi. Loyihada ketma-ket ma’lumotlar bilan ishlash uchun uch xil model ishlatilgan:

* RNN
* LSTM
* GRU

Modellar tarixiy ma’lumotlar asosida kelajakdagi qiymatlarni bashorat qiladi va ularning natijalari o‘zaro taqqoslanadi.

---

## 🚀 Loyiha haqida

Time-series (vaqt qatori) ma’lumotlarini bashorat qilish moliyaviy tahlilda juda muhim hisoblanadi.

Ushbu loyihada:

* Dataset yuklandi va tozalandi
* Ma’lumotlar normalization qilindi
* Time-series sequence yaratildi
* RNN, LSTM va GRU modellar train qilindi
* Modellar natijalari grafik orqali taqqoslandi

Asosiy maqsad: qaysi model yaxshiroq ishlashini aniqlash.

---

## 📂 Dataset haqida

Loyihada **JCI stock dataset** ishlatilgan.

Dataset quyidagi ustunlardan iborat:

* Open
* High
* Low
* Close
* Volume

Preprocessing bosqichlari:

* Keraksiz ustunlar olib tashlandi
* MinMaxScaler yordamida normalization qilindi
* Sequence uzunligi 30 qilib belgilandi

---

## 🧠 Ishlatilgan modellar

Loyihada 3 xil Deep Learning modeli ishlatilgan:

### 1️⃣ RNN

Oddiy ketma-ket model
Qisqa bog‘liqliklarni o‘rganadi

### 2️⃣ LSTM

Uzun bog‘liqliklarni yaxshi o‘rganadi
Time-series uchun eng mashhur model

### 3️⃣ GRU

LSTM ga qaraganda tezroq ishlaydi
Kamroq parametr bilan yaxshi natija beradi

---

## ⚙️ Train sozlamalari

Model train qilishda quyidagi parametrlar ishlatilgan:

Loss function:

MSELoss

Optimizer:

Adam

Sequence uzunligi:

30

Framework:

PyTorch

Dataset taqsimoti:

Train — 80%
Test — 20%

---

## 📊 Natijalar

Model natijalari quyidagilar bilan taqqoslandi:

* Haqiqiy qiymatlar
* RNN bashoratlari
* LSTM bashoratlari
* GRU bashoratlari

Natijalar grafik orqali vizual tarzda solishtirildi.

---

## 🛠️ Ishlatilgan texnologiyalar

Loyihada quyidagi texnologiyalar ishlatilgan:

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 📁 Loyiha strukturasi

```
Stock-Price-Prediction
│
├── Project.ipynb
├── JCI_data.csv
└── README.md
```

---

## 📈 Kelajakdagi yaxshilashlar

Kelajakda loyihani quyidagicha kengaytirish mumkin:

* Transformer model qo‘shish
* Hyperparameter tuning qilish
* Kattaroq dataset ishlatish
* Streamlit orqali web app qilish

---

## 👨‍💻 Muallif

**Jonibek Abdurahmonov**

Machine Learning va Deep Learning yo‘nalishida real loyihalar ustida ishlovchi dasturchi 🚀
