# Buat Laporan di Sini

Mahija Ibad Pradipta
5024221026
Pemrograman Lanjut (B)

Tugas Utama :
Pada assignment 0 ini Anda diharapkan dapat melakukan perintah dasar GitHub dan membuat program sederhana dalam bahasa C++. Program "Hello World" ini harus Anda ubah sehingga dapat menampilkan nama yang diinputkan oleh user. Sebagai contoh berikut merupakan contoh input / output dari program yang diinginkan:

.\myapp.exe
Silahkan inputkan nama Anda: Budi Ani
Hello Budi Ani

Tugas Tambahan :
Tugas lain yang harus dilakukan adalah mengubah nama file output dari myapp ke MyApp. Perlu diingat bahwa nama file pada Linux bersifat case-sensitive sehingga Anda perlu memperhatikan kecil-besar dari huruf tersebut.

Jawaban :
A) Pada tugas utama, source code sesuai dengan output yang diminta adalah :

#include <iostream>
using namespace std;

int main() {
string nama;
cout << "Silahkan inputkan nama Anda : ";
getline(cin, nama);  
cout << "Hello " << nama;
return 0;
}

line 21 menggunakan 'namespace std;' agar dapat mempersingkat kode.
line 24 menggunakan 'string' untuk menyimpan text berupa nama yang akan diinput.
line 26 menggunakan 'getline' agar bisa menerima input yang memiliki spasi, dan 'cin' untuk mengambil input dari keyboard.
line 25 & 27 menggunakan 'cout' untuk menampilkan teks ke layar.

B) Pada tugas tambahan untuk merubah nama file output yaitu di file makefile diline 11 bagian 'APPNAME'
