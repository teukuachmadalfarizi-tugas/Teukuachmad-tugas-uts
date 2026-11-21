RESUME MATERI PYTHON OOP

(OBJECT ORIENTED PROGRAMMING)

Identitas Mahasiswa

- Nama: Teuku Achmad Alfarizi Ramaya
- NIM: 14022500115
- Kelas: 3B
- Program Studi: Sistem Informasi
- Mata Kuliah: Pemrograman Berorientasi Objek (PBO)

---

1. Pengertian Python OOP

Python OOP (Object Oriented Programming) adalah konsep pemrograman yang menggunakan objek sebagai dasar dalam pembuatan program. OOP membantu programmer membuat kode yang lebih terstruktur, mudah dipahami, dan dapat digunakan kembali.

Dalam OOP, program dibuat menggunakan class dan object yang memiliki atribut serta method.

2. Pengertian Class

Class adalah cetakan atau rancangan yang digunakan untuk membuat sebuah objek.

Contoh:

class Mahasiswa:
    nama = "Teuku"
    jurusan = "Sistem Informasi"

Class di atas merupakan rancangan untuk membuat objek mahasiswa.

3. Pengertian Object

Object adalah hasil atau bentuk nyata dari sebuah class. Object memiliki data dan fungsi sesuai dengan class yang digunakan.

Contoh:

class Mahasiswa:
    def __init__(self, nama):
        self.nama = nama

mahasiswa1 = Mahasiswa("Teuku")

print(mahasiswa1.nama)

Output:

Teuku

4. Atribut

Atribut adalah variabel yang digunakan untuk menyimpan data atau informasi di dalam sebuah class.

Contohnya:

- Nama mahasiswa.
- NIM mahasiswa.
- Jurusan mahasiswa.
- Alamat mahasiswa.

5. Method

Method adalah fungsi yang berada di dalam sebuah class dan digunakan untuk menjalankan suatu perintah.

Contoh:

class Mahasiswa:
    def belajar(self):
        print("Mahasiswa sedang belajar")

m1 = Mahasiswa()
m1.belajar()

6. Constructor (init)

Constructor adalah method khusus yang otomatis dijalankan ketika sebuah objek dibuat.

Contoh:

class Teman:
    def __init__(self, nama, hobi):
        self.nama = nama
        self.hobi = hobi

teman1 = Teman("Teuku", "Main Game")

print(teman1.nama)
print(teman1.hobi)

7. Empat Konsep Utama OOP

A. Encapsulation

Encapsulation adalah konsep untuk membungkus data dan method dalam sebuah class serta mengatur akses terhadap data tersebut.

Tujuannya agar data lebih terkontrol dan tidak mudah diubah secara sembarangan.

B. Inheritance

Inheritance adalah konsep pewarisan sifat atau atribut dari class induk kepada class anak.

Contohnya, class Mahasiswa dapat mewarisi atribut dan method dari class Manusia.

C. Polymorphism

Polymorphism adalah kemampuan beberapa objek menggunakan method dengan nama yang sama tetapi memiliki perilaku atau hasil yang berbeda.

D. Abstraction

Abstraction adalah konsep menyembunyikan detail proses yang rumit dan hanya menampilkan bagian penting yang perlu digunakan.

8. Penggunaan Self

"self" digunakan untuk mengakses atribut dan method milik objek itu sendiri di dalam class.

Contoh:

class Mahasiswa:
    def __init__(self, nama):
        self.nama = nama

    def tampilkan(self):
        print(self.nama)

9. Kelebihan Python OOP

1. Kode program lebih terstruktur.
2. Mudah dipahami dan dikembangkan.
3. Kode dapat digunakan kembali.
4. Memudahkan perawatan program.
5. Cocok untuk membuat program berskala besar.

10. Contoh Penerapan Python OOP

Contoh penerapan OOP dalam kehidupan sehari-hari adalah program percakapan dua teman.

Dalam program tersebut terdapat:

- Class: "Teman"
- Object: "teman1" dan "teman2"
- Atribut: "nama" dan "hobi"
- Method: "sapa()", "tanya_kabar()", dan "pamitan()"

Program tersebut menunjukkan bagaimana class dan object digunakan untuk membuat simulasi percakapan menggunakan Python.

11. Kesimpulan

Dari materi Python OOP, saya memahami bahwa Object Oriented Programming merupakan konsep pemrograman yang menggunakan class dan object untuk membuat program lebih terstruktur.

Materi yang dipelajari meliputi class, object, atribut, method, constructor, self, serta empat konsep utama OOP yaitu encapsulation, inheritance, polymorphism, dan abstraction.

Dengan mempelajari Python OOP, saya dapat memahami cara membuat program yang lebih rapi, mudah dikembangkan, dan dapat digunakan kembali.

---

Disusun oleh:

Teuku Achmad Alfarizi Ramaya

NIM: 14022500115

Kelas: 3B Sistem Informasi
