# Business Understanding
Olahraga merupakan salah satu kegiatana positif yang bisa dilakukan oleh hamper semua orang. Banyak faktor yang mempengaruhi seseorang yang hendak melakukan olahraga. Salah satunya adalah membakar lemak pada tubuh demi mendapatkan bentuk tubuh yang ideal.
Progres olahraga dapat diketahui apabila terdapat bagian tubuh yang secara signifikan berubah dari waktu ke waktu secara manual.
Pesatnya Teknologi membuat hal yang tadinya manual dapat diotomatisasi menggunakan teknologi terkini, yaitu Kecerdasan Buatan. Orang yang awalnya melihat perkembangan diri secara manual, dapat melihat secara detail apa saja yang mengalami perubahan. Pada konteks ini adalah pembakaran lemak ataupun kalori dalam tubuh. Berdasar pada masalah tersebut, Machine Learning, sebagai subset daripada Kecerdasan Buatan hadir. Sehingga Pengguna dapat melihat secara langsung kalori yang terbakar menggunakan teknologi ini.

# Data understanding
Dataset ini memberikan gambaran umum yang mendetail mengenai rutinitas olahraga, atribut fisik, dan metrik kebugaran anggota gym. Dataset ini berisi 973 sampel data gym, termasuk indikator performa utama seperti detak jantung, kalori yang terbakar, dan durasi latihan. Setiap entri juga mencakup data demografis dan tingkat pengalaman, sehingga memungkinkan analisis yang komprehensif mengenai pola kebugaran, perkembangan atlet, dan tren kesehatan.  
Kondisi Data
Data dalam dataset ini telah dibersihkan, oleh karena itu, saya membuat tiruannya dengan hanya berjumlah 100 dataset yang masih kotor, diantaranya, yaitu :
1.	Data sebelumnya memiliki nilai yang tidak valid, yaitu Berat badan dan BMI, memiliki min value di bawah 0
2.	Semua kolom memiliki missing value
3.	Sebagian data memiliki duplikasi

# Fitur pada dataset diantaranya, yaitu :
1.	Age: Age of the gym member.
2.	Gender: Gender of the gym member (Male or Female).
3.	Weight (kg): Member’s weight in kilograms.
4.	Height (m): Member’s height in meters.
5.	Max_BPM: Maximum heart rate (beats per minute) during workout sessions.
6.	Avg_BPM: Average heart rate during workout sessions.
7.	Resting_BPM: Heart rate at rest before workout.
8.	Session_Duration (hours): Duration of each workout session in hours.
9.	Calories_Burned: Total calories burned during each session.
10.	Workout_Type: Type of workout performed (e.g., Cardio, Strength, Yoga, HIIT).
11.	Fat_Percentage: Body fat percentage of the member.
12.	Water_Intake (liters): Daily water intake during workouts.
13.	Workout_Frequency (days/week): Number of workout sessions per week.
14.	Experience_Level: Level of experience, from beginner (1) to expert (3).
15.	BMI: Body Mass Index, calculated from height and weight.

# Preprocessing Data
Tahapan preprocessing data, diantaranya, yaitu Pengumpulan data(Data Gathering), kemudian Penilaian Data(Asessing Data), dan terakhir, yaitu Pembersihan Data (Data Cleaning)
1.	Pengumpulan Data (Data Gathering)
Data diambil dari akun kaggle vala khorasani, namun data ini sudah dibersihkan, jadi penulis membuat data set tiruan akan data set tersebut.
2.	Penilaian Data (Asessing Data)
Data memiliki beberapa masalah, diantaranya, yaitu ada nilai yang hilang pada setiap kolom, data yang tidak sesuai atau invalid, dan juga terdapat duplikasi data
3.	Pembersihan Data (Data Cleanig)
