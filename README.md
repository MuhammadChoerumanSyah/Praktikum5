# Praktikum5
# Lab5Web
# Lab5Web

Membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Mengenal JavaScript</title>
</head>
<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>

![img](gambarlabs5/gambarlabs5.1.png)
![img](gambarlabs5/gambarlabs5.2.png)




# Javascrip Dasar
Pemakaian Alert sebagai property window.
<html>
    <head>
        <title>alert box</title>
    </head>
    <body>
        <script language = "javascript">
        <!--
    window.alert("ini merupakan pesan untuk anda");
    //-->
        </script>
    </body>
</html>

![img](gambarlabs5/gambarlabs5.3.png)
![img](gambarlabs5/gambarlabs5.4.png)

Pemakaian method dalam objek




<html>
<head>
    <title>skrip javaScript</title>
</head>
<body>
    percobaan memakai javaScript<br>
<script language = "javaScript">
    <!--
        document.write("selamat mencoba javascript <br>");
        document.write("semoga sukses!")
    //-->
</script>
</body>
</html>

![img](gambarlabs5/gambarlabs5.5.png)
![img](gambarlabs5/gambarlabs5.6.png)

Pemakaian Prompt
<html>
<head>
    <title>pemasukan data</title>
</head>
<body>
<script language = "javaScript">
    <!--
        var nama = ("siapa nama anda?","masukkan nama anda");
        document.write("hai,"+nama)
    //-->
</script>
</body>
</html>

![img](gambarlabs5/gambarlabs5.7.png)
![img](gambarlabs5/gambarlabs5.8.png)
![img](gambarlabs5/gambarlabs5.9.png)

Pembuatan fumgsi dan cara pemanggilannya
<html>
<head>
    <title>contoh program javaScript</title>
</head>
<body>
<script language = "javaScript">
    function pesan(){
        alert ("memanggil javascript lewat body onload")
    }
    <!--
</script>
</head>
<body onload=pesan()>
</body>
</html>

![img](gambarlabs5/gambarlabs5.10.png)
![img](gambarlabs5/gambarlabs5.11.png)

# Dasar Pemrograman Di Javasript
Operasi dasar aritmatika

<html>
    <head>
        <title>contoh program javasript</title>

<script language="javascript">
            function test (val1,val2)
            {
                document.write("<br>"+"perkalian : val1*val2 "+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1/val2 "+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
                document.write(val1+val2)
                document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"modulus : val1%val2 "+"<br>")
                document.write(val1%val2)
            }
    </script>
</head>
<body>
<input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>

![img](gambarlabs5/gambarlabs5.12.png)
![img](gambarlabs5/gambarlabs5.13.png)
![img](gambarlabs5/gambarlabs5.14.png)

Seleksi kondisi (if..else)
<html>
    <head>
        <title>contoh if-else</title>
    </head>
    <body>
        <script language="javascript">
            <!--
                var nilai = prompt("nilai (0-100): ",0);
                var hasil ="";
                if (nilai >=60)
                    hasil = "Lulus";
                else
                    hasil = "tidak lulus";
                document.write("hasil: "+ hasil);
                //-->
        </script>
    </body>
</html>

![img](gambarlabs5/gambarlabs5.15.png)
![img](gambarlabs5/gambarlabs5.16.png)
![img](gambarlabs5/gambarlabs5.17.png)
![img](gambarlabs5/gambarlabs5.18.png)
![img](gambarlabs5/gambarlabs5.19.png)

Penggunaan operator switch untuk seleksi kondisi
<html>
    <head>
        <title>contoh program javascript</title>

 <script language="javascript">
            function test ()
            {
                val1=window.prompt("input nilai (1-5):")
                switch (val1)
                {
                    case "1" :
                        document.write("bilangan satu")
                        break
                    case "2" :
                        document.write("bilangan dua")
                        break
                    case "3" :
                        document.write("bilangan tiga")
                        break
                    case "4" :
                        document.write("bilangan empat")
                        break
                    case "5" :
                        document.write("bilangan satu")
                        break
                    default :
                        document.write("bilangan lainnya")
                }
            }
    </script>
</head>
    <body>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
</html>

![img](gambarlabs5/gambarlabs5.20.png)
![img](gambarlabs5/gambarlabs5.21.png)
![img](gambarlabs5/gambarlabs5.22.png)
![img](gambarlabs5/gambarlabs5.23.png)
![img](gambarlabs5/gambarlabs5.24.png)
![img](gambarlabs5/gambarlabs5.25.png)

# Pembuatan Form
<html>
    <head>
        <script language="javascript">
            function test () {
                var val1=document.kirim.T1.value 
                if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
                else
                document.kirim.T2.value="bilangan ganjil"
            }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20">
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
        </form>
    </body>
</html>

![img](gambarlabs5/gambarlabs5.26.png)
![img](gambarlabs5/gambarlabs5.27.png)

Form Button.
<html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language="javascript">
            <!--
                function ubahWarnaLB(warna) {
                    document.bgColor = warna;
                }
                function ubahWarnaLD(warna) {
                    document.fgColor = warna;
                }
            //-->
        </script>

<h1>tes</h1>
        <form>
            <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
            <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLD('WHITE')">
            <input type="button" value="Teks Kuning" onClick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Teks Biru" onClick="ubahWarnaLD('BLUE')">
        </form>
        <script language = "javascript">
            <!--
                document.write("Dimodifikasi terakhir pada" + document.lastModified);
                //-->
        </script>
    </body>
</html>


![img](gambarlabs5/gambarlabs5.28.png)
![img](gambarlabs5/gambarlabs5.29.png)

# HTML DOM
Pilihan menggunakan checkbox dengan perhitungan otomatis
<!--
    File: daftar_menu.html
    //-->
<html>
 <head>
            <title>Daftar Menu</title>
<script>
    function hitung (ele) {
                    var total = document.getElementById('total').value;
                        total = (total ? parseInt(total) : 0);
                    var harga = 0
                    if (ele.checked) {
                        harga = ele.value;
                        total += parseInt(harga);
                    } else {
                        harga = ele.value;
                        if (total > 0)
                        total -= parseInt(harga);
                    }
                    document.getElementById('total').value = total;
                }
            </script>
        </head>
        <body>
            <h1>Daftar Menu Makanan</h1>
            <label><input type="checkbox" value="10000" id="menu1" onClick="hitung(this);"/>Shawarma Rp. 10.000</label><br />
            <label><input type="checkbox" value="40000" id="menu2" onClick="hitung(this);"/>Yakiniku Rp. 40.000</label><br />
            <label><input type="checkbox" value="20000" id="menu3" onClick="hitung(this);"/>Nasi Padang  Rp. 20.000</label><br />
            <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
        </body>
    </html>

![img](gambarlabs5/gambarlabs5.30.png)
![img](gambarlabs5/gambarlabs5.31.png)

# Pertanyaan dan Tugas
1 . Buat script untuk melakukan validasi pada isian form

# Jawaban 
Membuatvalidasi nama, No.Telp,Email

# 1. Nama
Disini saya akan memberikan validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh MuhammadChoerumanSyah (benar), MuhammadChoerumanSyah4 (salah)
![img](gambarlabs5/gambarlabs5.32.png)

Penjelasan
•	Membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai,pesan)
•	Data yang boleh dimasukkan adalah berupa "a-zA-Z"
•	Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"


![img](gambarlabs5/gambarlabs5.33.png)
![img](gambarlabs5/gambarlabs5.34.png)

# No Telp
Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123AB (salah).

![img](gambarlabs5/gambarlabs5.36.png)
Penjelasan:
•	var numberEXP = /^[0-9]+$/; merupakan variabel numberEXP yang diberi batasan validasi angka 0-9
•	Arti Match pada "if(nilai.value.match(numberEXP))" adalah string.match(), mencari string menggunakan Reguler Expression (Regex)
•	Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"


![img](gambarlabs5/gambarlabs5.35.png)

# Email
Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: herumansyah135@gmail.com (benar), herumansyah135@gmail. (salah)
![img](gambarlabs5/gambarlabs5.37.png)
• membuat variabel email"var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/;" berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"
![img](gambarlabs5/gambarlabs5.38.png)
# Berikut Penulisan Form Yang Benar 
![img](gambarlabs5/gambarlabs5.39.png)
![img](gambarlabs5/gambarlabs5.40.png)
![img](gambarlabs5/gambarlabs5.41.png)

## Alhamdulillah ##





