Heyyo Selamat Malam

Tulisan ini akan dibuat dalam bahasa indonesia dikarenakan saya belum menguasai betul.
For non-Indonesian reader, please translate to your preference language.



Kembali ke topik utama, apasih converter dc to dc? Jadi konverter DC to DC sesuai namanaya adalah konverter dari listrik DC ke listrik DC. Loh apa yang beda emangnya? Jadi yang umum di masyarakat adalah ada perbedaan tegangan. Contohnya 12V to 5V, 12V to 3.3V, atau malah dari 3.3V naik ke 5V. Lho kok bisa? bisa dong! Saya akan mencoba membahas dengan kasus yang umum terjadi dan analogi yang sederhana.

Umumnya, perangkat elektronik non-listrik PLN bersumber daya dari baterai, contohnya jam tangan, handphone, earbuds, dan masih banyak lagi. Nah ini poin pertama, baterai pasti memiliki spesifikasi tegangan dan arus. Jika kita mengingat rumus fisika kelas 2 SMP, P=V.I atau Daya sama dengan tegangan dikali arus. Dengan begitu, secara eksplisit nilai jual tak hanya terletak pada Voltase, tapi juga besarnya Daya, ini adalah dasarnya.

Terkadang mahasiswa atau pelajar yang sedang menggarap projek elektronik mendapati tegangan kerja komponen adalah 3.3V, yang mana ini akan sulit karena bukan tegangan baterai pasaran. Apa solusinya? yang bersangkutan dapat mencari di amazon baterai 3.3v, pasti ada, namun mahal di ongkir. Ada solusi lain? jelas ada. Inilah saatnya converter DC to DC beraksi. dengan harga yang relatif terjangkau, yang bersangkutan dapat menrubah tegangan baterai yang ada ke tegangan yang diperlukan. Nah ini poin kedua.

Masalah selesai? 60% sudah, tinggal ybs mencari referensi instalasi di internet. ada buaaaannnyaaakkk. Lalu kembali ke tujuan utama laman ini dibuat, bagaimana sih cara kerjanya? rugi di mana? di kimia ada pertukaran setara, apa yang dikorbankan? Jadi yang dikorbankan untuk menaikkan tegangan adalah perngurangan arus maksimal, dan yang dikorbankan untuk menaikkan arus adalah penurunan tegangan. Secara lebih detail, dari sisi elektron, ketika menaikkan tegangan maka akan menaikkan eneregi potensial dan ketika menaikkan arus maka menaikkan jumlah elektron yang dapat mengalir per detik. Lebih detailnya dapat dilihat pada tabel berikut.


![Tabelnya ges](https://github.com/username/repo-name/blob/main/Prinsip%20Kerja%20Rangkaian%20Converter%20DC%20to%20DC/Tabel%20perbandingan.PNG?raw=true)



##################################################



Jadi, taman-teman disini pasti pernah mendengar tentang perubahan tipe listrik PLN menjadi listrik tipe DC. Saya akan mengulas sedikit tentang fenomena tersebut, semoga tidak merembet ke mana-mana pembahasannya :). 

Seperti yang kita tahu, listrik PLN di negara Indonesia memakai tegangan 220V. Itu angka diatas kertas, aslinya naik turun. Anda dapat membuktikannya dengan adanya summber bacaan ataupun tutorial penyetabil listrik. Yang mana tutorial tersebut tidak akan ada jika tidak ada masalah. Analogi yang menurut saya cocok diterapkan pada elemen-elemen negara wakanda kita tercinta.

Kembali ke listrik PLN, listrik ini digunakan oleh mayoritas penduduk indonesia sebagai sumber listrik utama. Nah, sampai sini akan timbul pertanyaan "ohh, jadi semua elektronik di rumah cuma bisa aku hidupin pake colokan listrik PLN ya?". Jawabannya, TETOOOOTT, anda salah. Jika ditilik dari komponen-komponen elektronika pasif dan aktif, mereka hanya memerlukan suntikan listrik sesuai dengan spesifikasinya. Jika kurang akan tidak menyala. Jika kelebihan, sudah jelas akan DHUARR!!. (engga sih, lebay aja itu)

Jadi, tidak perlu selalu dicolok ke listrik PLN, kita bisa menghidupkannya dengan catu daya lain, misalnya motor generator, baterai, atau Genset. Jika seperti itu, akan timbul pertanyaan lagi "memangnya bedanya apa, Kak Gem?". Bedanya adalah spesifikasi tiap catu daya. Saat membeli catu daya, yang pertama kali dilihat adalah Voltasenya, lalu jika sudah sesuai kita perlu mengecek kebutuhan arus komponen kita seberapa untuk menentukan berapa Ampere yang harus kita beli. Biasanya, untuk segmen konsumsi rumahan, perbedaan harga yang mencolok terjadi pada besaran Ampere yang ditawarkan. Sedangkan perbedaan tegangan masih tidak begitu jauh harganya.
