# LATIHAN2DPBO2022
Repository ini bertujuan untuk memenuhi tugas latihan 2 pada mata kuliah Desain Pemograman Berorientasi Objek. 

Nama : Sabian Annaya Havid
Program Studi/Kelas : Ilmu Komputer/C2
NIM : 2005021

*Saya Sabian Annaya Havid mengerjakan Latihan dalam mata kuliah Desain Pemograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.*

# Penjelasan Program
## ![Untitled-1](https://user-images.githubusercontent.com/99664611/154848295-eddaf9e2-2afd-4847-bf29-19d27e742fe2.png)

Pada desain kelas, Produk menjadi orang tua dari kelas hardware. Hardware menjadi orang tua dari kelas memori yang secara otomatis menjadi perantara antara kelas Produk dan kelas Memori. 

### Mengapa demikian?
[Breakdown semua atribut masing-masing kelas]
- **Produk**: price [int], idProduct [string]
- **Hardware**: brand [string], model [string]
- **Memory**: Frequency [int], sizeMemory [string], supportCuda [boolean]

Produk dipilih menjadi orang tua dari hardware dan memory karena memiliki *primary key* dari produk itu sendiri, yaitu *idProduct*. lalu disusul oleh hardware karena memiliki atribut yang lebih mudah diingat dan mencolok (dilihat dari sisi customer). Lalu, memory menjadi kelas anak dari kelas hardware karena merupakan data detail dari hardware itu sendiri.

Pada semua program baik **CPP**, **JAVA**, **Python**, dan **PHP** memiliki metode get-set untuk mengakses atribut pada masing-masing kelas, metode get-set juga dapat digunakan apabila sebuah kelas memiliki orang tua yang memiliki atribut sehingga kelas anak juga bisa mengakses atribut tersebut.

User dapat menginput data dengan jumlah yang diinginkan, juga disediakan data template yang dibuat secara hardcode.

# Hasil Menjalankan Program CPP:
## ![tesCPP](https://user-images.githubusercontent.com/99664611/154848315-eaffc3b4-2835-4aee-82d3-017845848b0c.png)

*https://github.com/TNAlthea/LATIHAN2DPBO2022/tree/main/CPP*

# Hasil Menjalankan Program JAVA:
## ![tesJAVA](https://user-images.githubusercontent.com/99664611/154848324-db2e0784-dcff-4e41-8e3b-4d0ab4c99626.png)

*https://github.com/TNAlthea/LATIHAN2DPBO2022/tree/main/JAVA*

# Hasil Menjalankan Program PYTHON:
## ![tesPY](https://user-images.githubusercontent.com/99664611/154850629-3ede3e12-518e-437d-b26d-15a890df72a5.png)

*https://github.com/TNAlthea/LATIHAN1DPBO2022/tree/main/LATIHAN%20B/PY*

# Hasil Menjalankan Program PYTHON:
## ![tesPHP](https://user-images.githubusercontent.com/99664611/154853776-f31361f6-649e-4c4a-984a-fcb5bab3070d.png)

*https://github.com/TNAlthea/LATIHAN2DPBO2022/tree/main/PHP*

