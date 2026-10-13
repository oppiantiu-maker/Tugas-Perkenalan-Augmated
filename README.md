
# Scene Perkenalan Diri

## Identitas Mahasiswa
- Nama: [Nama Lengkap]
- NIM: [NIM]
- Mata Kuliah: [Nama Mata Kuliah]

## Deskripsi Proyek
Proyek ini merupakan scene perkenalan diri sederhana berbasis
A-Frame dan WebXR. Scene menampilkan lantai, langit, objek 3D,
teks nama dan NIM, serta objek yang berputar secara otomatis.

## Teknologi
- HTML
- A-Frame
- WebXR

## Link Demo
[Masukkan tautan GitHub Pages setelah aktif]

## Jawaban Refleksi

### 1. Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?
Pada scene ini, kamera menghadap ke arah sumbu Z negatif sehingga
objek yang ditempatkan pada posisi Z negatif berada di depan kamera.
Karena itu, posisi tersebut memudahkan objek terlihat saat scene pertama kali dibuka.

### 2. Mengapa WebXR hanya aktif pada HTTPS atau localhost?
WebXR membutuhkan secure context agar browser dapat mengakses
fitur perangkat dan sensor secara aman. HTTPS dan localhost
termasuk konteks yang memenuhi persyaratan keamanan tersebut.

### 3. Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame.
WebXR Device API menyediakan akses ke perangkat dan sesi
Virtual Reality atau Augmented Reality melalui browser.
Three.js digunakan untuk membuat dan merender grafis 3D,
sedangkan A-Frame memudahkan pembuatan scene 3D menggunakan
elemen HTML dan komponen yang dibangun di atas three.js.
