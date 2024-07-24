# Modifikasi-Program-Fuction


##Penggunaan Program
1. Buka Google
2. cari di kolom pencarian "Programiz ccp"
3. copy codingan yang tekah dikumpulkan, dan paste.
NOTE: (Mohon maaf sebelumnya pak, karna mengerjakan di programiz, di laptop saya tidak ada code lite, dan saya sudah mencoba untuk mendwonload tapi tidak bisa di run, jadi saya menggunakan note pad, seperti yang telah diajarkan oleh Ibu Fara).

##Penjelasan Input Data
(Pustaka dan Namespace)
<img width="182" alt="image" src="https://github.com/user-attachments/assets/983dfd24-81b8-497f-aba4-ebcb6c440e84">

- #include <iostream>: Baris ini digunakan untuk menyertakan pustaka input-output standar C++, yang memungkinkan kita menggunakan objek cout dan cin.
- using namespace std;: Baris ini digunakan untuk menghindari penulisan std:: sebelum cout dan cin.

(Deklarasi Fungsi)
<img width="307" alt="image" src="https://github.com/user-attachments/assets/45d26f30-6bc5-4c39-9a1b-20aa7050db3e">

- Baris-baris ini mendeklarasikan tiga fungsi yang akan digunakan untuk mencari nilai tertinggi, nilai terendah, dan rata-rata dari array nilai siswa.

(Fungsi main)
<img width="448" alt="image" src="https://github.com/user-attachments/assets/3ab027ef-0d74-4b66-a0c6-d70937b12b30">
<img width="443" alt="image" src="https://github.com/user-attachments/assets/a0dc99df-7423-4529-9cf9-e6b22b88b367">
int main() {
    int nilai[11] = {88, 82, 90, 90, 83, 100, 94, 95, 80, 81, 89};
    
    cout << "Data Nilai Matematika Kelas X-PPLG: 📚 " << endl;
    for (int i = 0; i < 11; ++i) {
        cout << "Nilai absen murid ke " << i+1 << ": " << nilai[i] << endl;
    }
    
    int nilaiTertinggi = cariNilaiTertinggi(nilai, 11);
    int nilaiTerendah = cariNilaiTerendah(nilai, 11);
    float rataRata = hitungRataRata(nilai, 11);
    
    cout << "Nilai Tertinggi Matematika siswa-siswi X-PPLG adalah: ✔" << nilaiTertinggi << endl;
    cout << "Nilai Terendah Matematika siswa-siswi X-PPLG adalah: ✔" << nilaiTerendah << endl;
    cout << "Nilai Rata-rata Matematika siswa-siswi X-PPLG adalah: ✔" << rataRata << endl;
    
    return 0;
}

(Deklarasi Array nilai)
<img width="443" alt="image" src="https://github.com/user-attachments/assets/3aa4fff2-8dcc-4359-9f26-af407a718fb3">
 - Array nilai berisi 11 elemen yang mewakili nilai matematika dari siswa-siswi kelas X-PPLG.

(Menampilkan Data Nilai)
<img width="392" alt="image" src="https://github.com/user-attachments/assets/13df891a-1bd8-4d6f-b7ac-f4c6941ebd6c">
 - Menampilkan nilai matematika dari setiap siswa menggunakan loop for.

(Menghitung Nilai Tertinggi, Terendah, dan Rata-rata)
<img width="382" alt="image" src="https://github.com/user-attachments/assets/3d8c8618-095c-4284-9207-27453bc9068d">
<img width="353" alt="image" src="https://github.com/user-attachments/assets/65c9a470-75e3-4ca3-9134-771e2bf8b2f7">
- Menggunakan fungsi cariNilaiTertinggi, cariNilaiTerendah, dan hitungRataRata untuk menghitung nilai tertinggi, terendah, dan rata-rata dari array nilai.

(Menampilkan Hasil)
<img width="446" alt="image" src="https://github.com/user-attachments/assets/713c0074-8ba2-40c8-b923-3f45553f109e">
 - Menampilkan hasil nilai tertinggi, terendah, dan rata-rata ke layar.

(Definisi Fungsi)
(Fungsi Nyari Nilai Tertinggi)
<img width="332" alt="image" src="https://github.com/user-attachments/assets/21208b2e-be70-49b1-b876-4c5409f7550a">
  - Fungsi ini mencari nilai tertinggi dalam array nilai dengan membandingkan setiap elemen dalam loop for.

(Fungsi Nyari Nilai Terendah)
<img width="340" alt="image" src="https://github.com/user-attachments/assets/ce43a73f-25a4-49a8-99fa-0b7b3b42caa4">
  - Fungsi ini mencari nilai terendah dalam array nilai dengan membandingkan setiap elemen dalam loop for.

(Fungsi Hitung Rata-rata)
<img width="357" alt="image" src="https://github.com/user-attachments/assets/c213f6a8-d999-4096-8a4a-9e8e5bfa8b4e">
 - Fungsi ini menghitung rata-rata nilai dengan menjumlahkan semua elemen dalam array nilai dan membaginya dengan jumlah elemen (n).


##Tampilan Akhir
<img width="448" alt="image" src="https://github.com/user-attachments/assets/3a8498e5-e7f4-4490-a1d0-4f8fdb279181">
















