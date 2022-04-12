## Nama     : Denas Aria Pamungkas
## NIM      : 312010089
## Kelas    : TI.20.A.1
## Matkul   : Web Pemograman
## PRAKTIKUM 5

Dipertemuan kali ini akan saya akan mempelajari apa itu javascript pada html, seperti penempatan javascript pada html di internal atau pun eksternal JavaScript

### 1. Pertama yang harus kita lakukan adalah kita membuat dokumen html dengan format lab5_javascript.html Dengan Code seperti berikut ini <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal Javascript</title>
</head>
<body>
    <h1>Pengenalan Javascript</h1>
    <h3>Contoh documen.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
dan hasil inputannya sebagai berikut

![img1](https://user-images.githubusercontent.com/101621068/162909790-3b7abd04-c215-41a0-9f6f-c9e39558dbc7.png)

## Memasuki bagian Java Script Dasar

### 2. Pemakaian alert sebagai operasi window <b>

## Contoh Codingan hasil outputnya
```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>alert box</title>
</head>
<body>
   <script lang="javascript">
       window.alert("ini merupakan pesan untuk anda");
   </script>
</body>
</html>
```
Penjelasannya sebagai berikut

Pemakaian alert sebagai property window dan akan muncul di atas halaman dengan contoh hasil gambar seperti dibawah ini

![img2](https://user-images.githubusercontent.com/101621068/162909126-1f60372e-9452-45fd-84b0-046a96b02bd2.png)

### 3. Pemakaian Method Dalam Objek <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script lang="javascript">
        document.write("Selamat mencoba javascript<br>");
        document.write("Semoga sukses!");
    </script>
</body>
</html>
```

Menggunakan Method dalam objek dengan javascript, seperti contoh codingan di atas dan hasil output nya adalah sebagai berikut

![img3](https://user-images.githubusercontent.com/101621068/162910443-b209c4fb-6c18-4c2d-ab9c-2f7f4bc6043d.png)

### 4.Pemakaian Prompt <b>

## Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pemasukan data</title>
</head>
<body>
    <script lang="javascript">
        var nama = prompt("siapa nama anda?","masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
</body>
</html>
```

Penjelasannya sebagai berikut

Menggunakan Prompt pada script seperti gambar di atas dan hasil output nya dibawah ini

![img4](https://user-images.githubusercontent.com/101621068/162910902-456accac-99e8-4d7e-95ef-0c2af2d84402.png)

### 5. Pembuatan Fungsi Dan Cara Pemanggilannya <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program javascript</title>
    <script lang="javascript">
        function pesan(){
            alert ("Memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
    
</body>
</html>
```

Berikut adalah Hasil Dari codingan diatas tadi

![img5](https://user-images.githubusercontent.com/101621068/162911233-5a8f6aea-2cb8-47c4-b5e8-d7c58d3a3b85.png)

## Dasar Pemrograman di Javascript

### 6. Operasi Dasar Aritmatika <b>

## Contoh Codingan 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
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
```

Penjelasannya sebagai berikut

Operasi Dasar Artimatika dalam javascript seperti contoh gambar di bawah Merupakan Output Dari Codingan Diatas
![img6](https://user-images.githubusercontent.com/101621068/162911645-d2059104-81fb-4081-ad11-a65b8568ca5f.png)

### 7. Seleksi Kondisi (If/else) <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh if-else</title>
</head>
<body>
    <script lang="javascript">
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >=60)
        hasil = "lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil: " + hasil);
    </script>
</body>
</html>
```

Penjelasannya sebagai berikut

Ini adalah program seleksi kondisi dari if else disitu if nya jika nilai lebih sama dengan 60 berarti lulus dan else nya jika dibawah 60 berati tidak lulus, sementara saya memberi nilai 90 yang berarti hasil nya adalah lulus dan ini adalah hasil output dari codingan diatas

![img7](https://user-images.githubusercontent.com/101621068/162911907-efaf2edd-53f2-47d1-9456-43f039d3e4a8.png)

Dan Jika nilai diatas 60 Berarti Menandakan Bahwa mahasiswa itu lulus

![img8](https://user-images.githubusercontent.com/101621068/162912095-39fafd7b-1db3-4db3-83a7-59cda6b04200.png)

### 8. Penggunaan Operator switch untuk seleksi kondisi <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
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
                    document.write("bilangan lima")
                    break 
                default  :
                    document.write("bilangan lainnya")
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

Penjelasannya sebagai berikut

Membuat form input dengan function javascript dan pengondisian if/else seperti gambar di atas saya memilih angka 5 maka akan menjadi bilangan ganjil

![img9](https://user-images.githubusercontent.com/101621068/162912478-60493b62-8744-4d96-9077-1f28a821a845.png)

Penggunaan operator switch untuk seleksi kondisi, disini saya menulis program switch case sebagai seleksi kondisi dengan memasukan angka 5 sebagai angka seleksi nya kemudian output nya akan keluar argument bilangan lainnya dan ini adalah hasil outputnya

![img10](https://user-images.githubusercontent.com/101621068/162912587-4755545b-a65e-4cd8-9f2f-6ec125744e5e.png)

### 9. FORM INPUT <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form input</title>
    <script lang="javascript">
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
    <form action="" method="post" name="kirim">
        <p>BIL <input type="text" name="T1" id="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" id="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```

Penjelasannya sebagai berikut

Membuat form input dengan function javascript dan pengondisian if/else seperti gambar di atas saya memilih angka 10 maka akan menjadi bilangan genap 

![img11](https://user-images.githubusercontent.com/101621068/162912902-177d593e-52c6-4020-a368-38fc470b9ac6.png)

### 10. Form Button <b>

## Contoh Coding
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Objek Document</title>
</head>
<body>
    <script lang="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>
    <h1>Tes</h1>
    <form action="">
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script lang="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
```

Penjelasannya sebagai berikut

Disini menggunakan form button dengan function javascript dan html form button hasil nya adalah seperti contoh gambar di atas, saya memilih warna hijau dan teks biru

![img12](https://user-images.githubusercontent.com/101621068/162913224-68c6d848-8873-481b-9ede-bb5f91a8b8f7.png)

## HTML DOM

### 11. PILIHAN MENGGUNAKAN CHECKBOX DENGAN PERHITUNGAN OTOMATIS <b>

## Contoh Codingan
```html
<!DOCTYPE html>
<!-- file daftar menu.html -->
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daftar Menu</title>
  <script lang="javascript">
      function hitung(ele) {
          var total = document.getElementById('total').value;
              total = (total ? parseInt(total) : 0);
          var harga = 0;
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
  <label><input type="checkbox" value="5000" name="menu1" id="menu1" onclick="hitung(this);">Ayam Goreng Rp. 5.000</label><br>
  <label><input type="checkbox" value="500" name="menu2" id="menu2" onclick="hitung(this);">Tempe Goreng Rp. 500</label><br>
  <label><input type="checkbox" value="2500" name="menu3" id="menu3" onclick="hitung(this);">Telur Dadar Rp. 2.500</label><hr>
  <strong>Total Bayar: Rp. <input type="text" name="total" id="total"></strong>
</body>
</html>
```

Penjelasannya sebagai berikut

Disini menggunakan HTML DOM dengan input type checkbox sebagai contoh codingan di atas menghitung secara otomatis dan ini adalah hasil outputnya

![img13](https://user-images.githubusercontent.com/101621068/162913668-746214cc-d4ad-42a5-8fcc-a87f287f40ab.png)

### PERTANYAAN DAN TUGAS <b>

### 1. BUAT SCRIPT UNTUK MELAKUKAN VALIDASI PADA ISIAN FORM

## Contoh Codingan
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form Validasi</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript">
        function validasiForm() {
            var nama = document.getElementById("nama").value;
            var email = document.getElementById("email").value;
            var alamat = document.getElementById("alamat").value;
            if (nama != "" && email != "" && alamat != "") {
                return true;
            } else {
                alert('Isi Alamat Anda dengan lengkap !');
                return false;
            }
        }
    </script>
</head>
<body>
     <div class="login">
        <h2>VALIDASI DATA ANDA</h2>
        <form action="#" method="POST" onSubmit="return validasiForm()">
            <div>
                <label>Nama Lengkap:</label>
                <input type="text" name="nama" id="nama" />
            </div>
            <div>
                <label>Email:</label>
                <input type="email" name="email" id="email" />
            </div>
            <div>
                <label>Alamat:</label>
                <textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
            </div>
            <div>
                <input type="submit" value="Daftar" class="tombol">
            </div>
        </form>
    </div>
</body>
</html>
```

```css
body {
    background: #4cc9f0;
    font-family: sans-serif;
    padding: 100px;
  }
  
  h2{
      text-align: center;
      font-size: 35px;
      color: #555;
  }
  .login {
    padding: 1em;
    margin: 2em auto;
    width: 30em;
    background: #fff;
    border-radius: 3px;
  }
  
  label {
    font-size: 10pt;
    color: #555;
  } 
  
  input[type="text"],
  input[type="email"],
  textarea {
    padding: 8px;
    width: 95%;
    background: #efefef;
    border: 0;
    font-size: 10pt;
    margin: 6px 0px; 
  }
   
  .tombol {
    background: #3498db;
    color: #fff;
    border: 0;
    padding: 5px 8px;
  } 
   .tombol:hover{
      background-color: #555;
  }
  ```

  Penjelasannya sebagai berikut

  Ini adalah contoh membuat form validasi dengan menggunakan script atau javascript terdapat beberapa pengondisian, jika data tidak di isi dengan lengkap maka akan terdapat prompt isi alamat anda dengan lengkap karena harus mengisi dengan lengkap seperti contoh gambar di atas

![img14](https://user-images.githubusercontent.com/101621068/162914131-36598fe7-04af-407e-b75f-9fa4272d6fa8.png)

Sementara contoh gambar dibawah ini adalah ketika data tidak di isi dengan lengkap, maka akan ada prompt isi alamat anda dengan lengkap, tidak akan bisa disubmit karena data belum lengkap

![img15](https://user-images.githubusercontent.com/101621068/162914245-1d318f72-8b80-4277-9a4f-854f4f45e5d8.png)

## TERIMAKASIH
