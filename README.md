# Lung-Disease-Classification-using-CNN-ML
## Hybrid feature fusion from multiple CNNs with Bayesian-optimized ML classifiers.

📘 Deskripsi Proyek

Proyek ini mengusulkan pendekatan Hybrid Deep Learning–Machine Learning untuk klasifikasi citra paru-paru.
Model ini menggunakan tiga pre-trained CNN — VGG16, DenseNet201, dan InceptionV3 — untuk mengekstraksi fitur citra. Fitur yang dihasilkan dari ketiga model tersebut digabungkan (feature fusion) guna meningkatkan representasi informasi yang relevan.

Selanjutnya, Principal Component Analysis (PCA) digunakan untuk mereduksi dimensi fitur, sementara Bayesian Optimization diterapkan untuk menyesuaikan hyperparameter dari algoritma machine learning seperti: —Support Vector Machine (SVM) — Decision Tree — k-Nearest Neighbor (k-NN)

Tujuannya adalah meningkatkan akurasi dan stabilitas model dalam mendeteksi beberapa jenis penyakit paru seperti:

🟩 Normal

🟥 COVID-19

🟦 Pneumonia

🟨 Tuberculosis

⚙️ Tools & Framework

- Python 3.x

- TensorFlow / Keras

- Scikit-learn

- NumPy, Pandas, Matplotlib, Seaborn

- Jupyter Notebook
