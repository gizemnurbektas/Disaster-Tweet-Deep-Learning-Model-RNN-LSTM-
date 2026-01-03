# Disaster-Tweet-Deep-Learning-Model-RNN-LSTM
Disaster Tweet Classification using RNN & LSTM

Bu proje, Twitter üzerinden paylaşılan metinlerin gerçek bir afet (disaster) içerip içermediğini tahmin etmek amacıyla geliştirilmiştir. Model, Doğal Dil İşleme (NLP) teknikleri ve Derin Öğrenme (RNN & LSTM) mimarileri kullanılarak oluşturulmuştur.

📌 Proje Amacı

Afet anlarında sosyal medyada paylaşılan mesajların otomatik olarak analiz edilmesi,

Gerçek afet bildirimlerinin hızlıca tespit edilmesi

Acil durum yönetimi ve kriz müdahalesine destek sağlanması

amaçlanmaktadır.

🧠 Kullanılan Yöntemler

Metin ön işleme (Text Preprocessing)

Tokenization & Padding

Word Embedding

Recurrent Neural Network (RNN)

Long Short-Term Memory (LSTM)

📂 Veri Seti

Kaggle – Disaster Tweets Dataset

Tweet metinleri ve ikili etiket:

1 → Gerçek afet tweet’i

0 → Afet içermeyen tweet

Örnek Sütunlar:

text : Tweet içeriği

target : Sınıf etiketi

⚙️ Kullanılan Teknolojiler

Python

Jupyter Notebook

TensorFlow / Keras

NumPy

Pandas

Matplotlib / Seaborn

🏗️ Model Mimarisi

Embedding Layer

RNN / LSTM Layer

Dense (Fully Connected) Layer

Sigmoid aktivasyon fonksiyonu

Model, binary classification problemi olarak ele alınmıştır.

📊 Performans Değerlendirmesi

Accuracy

Loss grafikleri

Eğitim ve doğrulama sonuçları karşılaştırması

▶️ Projeyi Çalıştırma

Repository’yi klonlayın:

git clone https://github.com/kullanici_adi/disaster-tweet-rnn-lstm.git


Gerekli kütüphaneleri yükleyin:

pip install -r requirements.txt


Jupyter Notebook’u açın:

jupyter notebook disastertweetrnnlstm.ipynb

🚀 Geliştirme Fikirleri

GRU modeli eklenmesi

Transformer / BERT tabanlı modellerle karşılaştırma

Gerçek zamanlı tweet analizi

Çok dilli destek

👩‍💻 Hazırlayan

Gizem Bektaş
Makine Öğrenmesi & Derin Öğrenme Projesi
