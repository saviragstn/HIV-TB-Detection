# HIV-TB-Detection
Tuberculosis Detection in HIV Patients Using Microarray Data with Principal Component Analysis-Support Vector Machine  

The dataset is from the NCBI (GEO Dataset Browser) website.
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE50834

Deteksi Tuberculosis pada penderita HIV menggunakan PCA sebagai metode fitur ekstraksi dan SVM sebagai metode klasifikasi. Kernel SVM yang digunakan yaitu Linear, Polynomial, dan RBF.
Pada saat pembangunan model digunakan metode GridSearchCV untuk mencari nilai terbaik dari parameter bebas SVM, dan juga digunakan K-Fold Cross Validation = 10.
