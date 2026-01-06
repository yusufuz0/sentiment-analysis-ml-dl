Duygu Sınıflandırmasında Derin Öğrenme ve Makine Öğrenmesi Modelleri ile Çalışmalar 

Kullanılan Teknolojiler:

🐍 Python

📊 Pandas

➗ Numpy

🔤 re (Regular Expressions)

🧠 scikit-learn

🧪 TensorFlow / Keras

🤗 Hugging Face Transformers

💾 joblib

☁️ Google Colab

📁 Google Drive




Modelleme & Algoritmalar:

📉 Logistic Regression

📊 Naive Bayes

🔄 LSTM 

🤖 BERT 

📈 TF-IDF 


Bu projede, Python programlama dili ve Google Drive entegresyonu kullanılarak Google Colab ortamında 40.000 tweet içeren bir veri seti üzerinde duygu analizi yaptım. Veri setinde tweet ID, duygu etiketi ve içerik olmak üzere üç sütun vardı. Duygu etiketlerinde 13 farklı sınıf bulunuyordu, ancak bazı sınıflar çok azdı ve bu da model performansını etkiliyordu. Bu yüzden nadir görülen bazı duyguları çıkararak daha dengeli bir veri seti oluşturdum.
Veri temizliği ve düzenlemesini pandas ve numpy ile yaptım. Metinlerdeki gereksiz karakterleri ve gürültüyü azaltmak için re modülünü kullandım. Metinleri makine öğrenmesine uygun hale getirmek için TF-IDF yöntemiyle sayısal vektörlere dönüştürdüm.
Modelleme aşamasında önce Logistic Regression ve Naive Bayes gibi klasik makine öğrenmesi modellerini kullandım. Naive Bayes modelinde, nadir sınıfları çıkarınca doğruluk oranı ciddi şekilde arttı. Daha sonra TensorFlow ve Keras ile LSTM modeli tasarladım. LSTM, metinlerin sıralı yapısını öğrenerek daha iyi sonuç verdi. Ayrıca overfitting’i önlemek için dropout teknikleri kullandım.
Son olarak, Hugging Face Transformers kütüphanesini kullanarak BERT modelini eğittim. Bu modelde sadece "neutral", "sadness" ve "happiness" sınıflarına odaklandım ve %68 doğruluk elde ettim. Bu çalışma sayesinde doğal dil işleme ve model eğitimi konusunda önemli deneyimler kazandım. Veri ön işleme, dengesiz veriyle başa çıkma, model hiperparametreleri optimizasyonu gibi kritik konularda kendimi geliştirdim.
