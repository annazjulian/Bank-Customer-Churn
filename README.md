# Bank-Customer-Churn
Artikel ini berisi tentang Prediksi Customer Churn di Bank menggunakan metode random forest. Data diambil dari kaggle.com. Dalam datasetnya ada beberapa fitur diantaranya yang digunakan untuk analisis yaitu credit score, geography, gender, age, tenure, Balance, NumOfProducts, HasCrCard,IsActiveMember,EstimatedSalary dan Exited itu sendiri yang merupakan data mengenai customer yang churn dan tidak.


Mengenai data preprocessingnya sudah dilakukan seperti handle missing value, encoding fitur yang masih categorik untuk dijadikan numerical untuk keperluan pemodelan. Dilihat dari pemodelannya menggunakan tuning random forest, yang paling bagus dengan decision tree sebanyak 5 dan kedalaman 40. Untuk hasil akhir recallnya, sebanyak 0.22, masih perlu dicari dengan pemodelan lain.

