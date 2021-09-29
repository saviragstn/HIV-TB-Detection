# HIV-TB-Detection
Tuberculosis Detection in HIV Patients Using Microarray Data with Principal Component Analysis-Support Vector Machine  

The dataset is from the NCBI (GEO Dataset Browser) website.
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE50834

Human Immunodeficiency Virus (HIV) adalah virus yang menyerang sistem kekebalan tubuh, khususnya sel darah putih yang disebut sel Cluster of Differentiation 4 (CD4). Salah satu infeksi oportunistik yang paling sering dijumpai dan merupakan penyebab utama kematian pada penderita HIV adalah Tuberculosis (TB). Berdasarkan World Health Organization (WHO) pada tahun 2015, koinfeksi HIV/TB menyebabkan 390.000 kematian di seluruh dunia. 
Microarray adalah teknologi untuk menganalisis struktur ribuan ekspresi gen yang terdapat dibagian tubuh tertentu secara bersamaan. Data microarray memiliki dimensi yang besar sehingga diperlukan suatu metode machine learning untuk mempermudah analisis. Metode machine learning yang dilakukan yaitu reduksi dimensi dan proses klasifikasi, sehingga model klasifikasi data microarray menghasilkan akurasi yang baik. 

Tujuan penelitian ini yaitu untuk menganalisis hasil performansi dari model klasifikasi deteksi TB pada penderita HIV, menggunakan metode Principal Component Analysis (PCA) sebagai reduksi dimensi dan metode Support Vector Machine (SVM) sebagai metode klasifikasi. Kernel SVM yang digunakan yaitu Linear, Polynomial, dan RBF.Pada saat pembangunan model digunakan metode GridSearchCV untuk mencari nilai terbaik dari parameter bebas SVM, dan juga digunakan K-Fold Cross Validation = 10.
