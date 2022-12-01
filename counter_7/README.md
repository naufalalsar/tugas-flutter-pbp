## Muhammad Naufal Zaky Alsar - 2106752041

## counter_7 (Tugas 7)

### Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya

Stateful merupakan widget yang dapat berubah sesuai dengan statenya sedangkan stateless widget tidak berubah apapun statenya.


### Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya

1. Row

Row beguna untuk menyimpan widget dalam horizontal

2. FloatingActionButton

Merupakan button yang berada paling atas disemua aplikasi sehingga tidak akan tertutup oleh apapun


### Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut

Fungsi dari setState() adalah memberitahu bahwa terjadi perubahan state maka yang harus dikerjakannya adalah menjalankan build lagi


### Jelaskan perbedaan antara const dengan final

const nilainya harus diketahui saat compile time sedangkan final nilainya harus diketahui saat run time


### Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas

Saya membuat fungsi increment dan decrement untuk menambah atau mengurangi counter. Saya juga membuat fungsi check untuk mengetahui apakah textnya harus ganjil atau genap. Setelah itu saya menambahkan dua floating button di dalam row agar buttonnya ada di suatu garis horizontal.

## Tugas 8

### Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement.

Navigator.push adalah cara kita untuk menambahkan page yang akan dituju di top of stack navigator. Di lain sisi, Navigator.pushReplacement akan menghapus top of stack saat ini (page tempat kita berada), lalu menambahkan page yang dituju di top of stack navigator

### ListView: Sebagai tempat menampung Card yang berisikan widget ListTile untuk yang memuat data budget yang telah ditambahkan.

ListTile: Berfungsi sebagai wadah untuk mengisi ListView Jumlahnya variatif sesuai dengan data budget yang ditambahkan.
Card: Membungkus ListTile dalam bentuk kartu.
Drawer: membuat drawer untuk navigasi page dari aplikasi.
SizedBox: berfungsi untuk memberikan jarak antar widget.
SingleChildScrollView: berfungsi untuk memberikan fungsionalitas scrollable terhadap child-nya.
Expanded: berfungsi untuk menampung widget agar memiliki properti expand.
TextFormField: berfungsi sebagai form yang meminta input teks.
DropdownButton: button yang berfungsi meminta pilihan user dari items yang ada.
DropdownHideUnderline: menghapus underline dari dropdown button.
TextButton: Agar user dapat mensubmit form dan menyimpan data budget.
Align: berfungsi untuk memberikan alignment untuk suatu widget.

### Sebutkan jenis-jenis event yang ada pada Flutter (contoh: onPressed).

onPressed
onSaved
onClick
onTap
onLongPress
onChanged
onHover
dan lain-lain

### Jelaskan bagaimana cara kerja Navigator dalam "mengganti" halaman dari aplikasi Flutter.

Cara kerjanya seperti stack dan di top of stack merupakan halaman sekarang dan jika ingin pindah maka akan di pop stacknya.

### Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas

Membuat 2 file baru dan mengisinya sesuai kententuan soal dengan form dan listview dan membuat class buat menyimpan data-datanya menggunakan list.
