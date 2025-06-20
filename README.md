# Face-Recognition

Ini adalah kode untuk face recognition attendance. Kode ini menggunakan dataset lokal berupa file foto pada folder yang sama.
contoh:
kode berada di D:/python/facerecognition
folder dataset berada di D:/python/facerecognition dengan kumpulan foto foto user terkait

nanti setelah di run dia akan meregenerate file untuk encoding nya dan juga spreadsheet untuk attendance
Kode ini juga disertai fungsi berupa liveness dimana wajah user harus bergerak untuk melakukan attendance maka dari itu jika melakukan attendance lewat foto tidak akan bisa

untuk kodenya sendiri ini dibuat menggunakan python 12.4
jika terdapat error pada dlib, maka ikuti langkah langkah berikut:
1. Install CMake (windows)
2. Install Visual Studio 2022
3. Setelah langkah kedua, buka aplikasinya dan install Visual Studio C++
4. Buka kode kembali dan install
   "py -m pip install dlib face_recognition"
