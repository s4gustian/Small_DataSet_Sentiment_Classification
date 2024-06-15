# Small_DataSet_Sentiment_Classification
Dataset for Sentiment Classification Task in Bahasa Indonesia 

Kami menyediakan dataset untuk shared task klasifikasi teks (sentimen) dalam bahasa Indonesia, dengan problem klasifikasi sebagai berikut:
1. Studi kasus adalah pengukuran sentimen terhadap tokoh publik, dengan skenario bahwa tim peneliti atau konsultan diminta untuk melakukan klasifikasi dengan cepat. Sehingga tidak memungkinkan melakukan pembentukan data training yang cukup untuk melatih metode klasifikasi yang berbasis pembelajaran mesin (machine learning). Sehingga hanya sedikit data yang diberikan label oleh anotator yang ditunjuk. Dalam skenario ini, hanya 300 sample teks (sumber dari media sosial) yang diberikan label kelas positif, negatif atau netral (ada 3 kelas), masing-masing 100 sample.
2. Dataset yang tersedia untuk isu sentimen terhadap tokoh publik ini tersedia dalam 2 versi data, yang masing-masing terdiri atas 300 sample.
3. Disediakan juga dataset klasifikasi sentimen dengan topik yang lain yang dapat dimanfaatkan oleh peserta shared task ini untuk menambah dataset yang kecil untuk pelatihan metode ML mereka. Peserta dapat memanfaatkan dataset lain dengan cara apa pun.
4. Peserta dapat mengembangkan metode klasifikasi masing-masing sehingga dapat melakukan prediksi terhadap data test yang tersedia dengan hasil yang memuaskan.
5. Data test yang diberikan dalam shared task ini, tidak memiliki label. Proses scoring dilakukan dengan cara mengirimkan file hasil prediksi ke suatu sistem leaderboard (papan ranking), dan score evaluasi akan otomatis langsung ditampilkan di dalam sistem.
6. Official score dalam shared task ini adalah F1-score, karena dihitung berdasarkan perimbangan kelas yang ada di dalam data testing. Score ini adalah score yang umum dipakai dalam banyak penelitian shared task di dunia (silakan lihat referensi pada SemEval, HASOC, dan lain-lain yang terkait dengan task classification).

Distribusi dataset yang tersedia:

Dataset Kaesang v1:	
   (N=300)	(pos:net:neg = 100	: 100 : 100)            
Dataset Kaesang v2:	
   (N=300)	(pos:net:neg = 100	: 100 : 100)        
Dataset Program Vaksin Covid:
   (N=8000)	(pos:net:neg = 463	:  6664	:  873)            
Dataset Open Topic:
   (N=7569)	(pos:net:neg = 1505 : 3408	: 2656)                  

Dataset Testing Kaesang 
   (N=924 sample)                           		

Data Testing tidak diberikan informasi mengenai distribusi kelasnya, sehingga tugas peserta shared task untuk melakukan prediksi sebaik mungkin menggunakan metode yang dikembangkan.

Catatan Penting:
1. Apabila anda menggunakan dataset yang kami sediakan di atas, bila anda menggunakan semua dataset untuk melaksanakan penelitian shared task ini, anda diharuskan mendaftarkan tim peneliti anda di dalam link berikut:https://forms.gle/jhUyGAsyUYs7AdMk9
2. Setelah mengisi link, anda diminta menghubungi kami di email sagustian.learning [at] gmail [dot] com, dan mengonfirmasi pendaftaran ke nomor WA : 0821.8484-4118 (chat only)
3. Anda akan diberikan password untuk membuka data, dan link untuk pendaftaran username dan tim, agar dapat mensubmit hasil penelitian anda di leader board (papan ranking).
4. Bila anda hanya tertarik melakukan penelitian mandiri untuk klasifikasi sentimen, dan anda tidak berpartisipasi di dalam shared task ini, anda dapat menggunakan data set yang tersedia secara gratis, dengan syarat, anda mensitasi salah satu paper berikut:


Penggunaan dataset Kaesang (training dan testing) atau Dataset Open Topic:

Agustian dkk. (2024), Arah baru penelitian klasifikasi teks: Memaksimalkan Kinerja Klasifikasi Sentimen dari Data Terbatas, <to be appeard in journal....>

Agustian dkk. (2024), New Directions in Text Classification Research: Maximizing Sentiment Classification Performance from Limited Data, <to be appeared in Journal ...>

Agustian dkk. (2024), Addressing Small Dataset Challenges in Sentiment Classification through Machine Learning and Optimization, <to be appeared in Proceeding of ICAAC 2024, Bali, Indonesia >

Penggunaan dataset Sentimen Program Vaksin Covid (pilih salah satu atau beberapa):

Yohana P, Agustian S, Kurnia Gusti S (2022) Klasifikasi Sentimen Masyarakat terhadap Kebijakan Vaksin Covid-19 pada Twitter dengan Imbalance Classes Menggunakan Naive Bayes, SNTIKI (Seminar Nasional Teknologi Informasi, Komunikasi dan Industri) (2022) 

Ash Shiddicky, Agustian S (2022), Analisis Sentimen Masyarakat Terhadap Kebijakan Vaksinasi Covid-19 pada Media Sosial Twitter menggunakan Metode Logistic Regression, Jurnal CoSciTech (Computer   Science and Information Technology) (2022) 3(2) p99-106

Sahbuddin M, Agustian S (2022) Support Vector Machine Method with Word2vec for Covid-19 Vaccine Sentiment Classification on Twitter, JOURNAL OF INFORMATICS AND TELECOMMUNICATION ENGINEERING (2022)   6(1) p288-297
 
