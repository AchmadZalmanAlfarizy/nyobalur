Deskripsi Kelas calculator
Kelas calculator memiliki beberapa atribut dan metode yang digunakan untuk melakukan operasi matematika dasar. Berikut adalah deskripsi lengkapnya:

Atribut
first: Menyimpan nilai pertama.
second: Menyimpan nilai kedua.
Konstruktor
public calculator(long first, long second): Konstruktor untuk menginisialisasi nilai first dan second.
Metode
public long addFucn(long first, long second): Menghitung penambahan antara first dan second dan mengembalikan hasilnya.
public long subFucn(long first, long second): Menghitung pengurangan first dari second dan mengembalikan hasilnya.
public long mulFucn(long first, long second): Menghitung perkalian antara first dan second dan mengembalikan hasilnya.
public long getFirst(): Mengembalikan nilai first.
public long getSecond(): Mengembalikan nilai second.
Metode main
Metode main digunakan untuk menjalankan aplikasi kalkulator dengan mengambil input dari argumen baris perintah dan menampilkan hasilnya.

Deskripsi Kelas Uji Mytest
Kelas Mytest adalah kelas uji yang menggunakan framework pengujian JUnit untuk menguji fungsi-fungsi dalam kelas calculator. Terdapat tiga metode pengujian yang menguji operasi penambahan, pengurangan, dan perkalian dalam calculator.

