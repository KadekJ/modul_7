# modul_7
![alt text](https://github.com/KadekJ/modul_7/blob/master/form%20create.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/hasil%20form%20create.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/hasil%20form%20create%20fix.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/edit.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/edit2.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/edit3.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/edit4.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/delete.png)
![alt text](https://github.com/KadekJ/modul_7/blob/master/delete2.png)

1. Berikan contoh kode keneksi untuk ke database pd php?
- $connect = mysqli_connect($host, $uname, $pass, $db);
2. Bagaimana cara anda membuat database pada phpMySQl!
-$result = mysqli_query($connect,$query);
3. Berikan code query untuk menampilkan sebuah data yang ada pada ke database?
-"SELECT * FROM dosen WHERE id_dosen = $id_dosen";
4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?
-$query = "UPDATE dosen SET nama_dosen = '$nama_dosen', telp = '$telp' WHERE id_dosen = $id_dosen";
5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?
-$query = "DELETE FROM dosen WHERE id_dosen = $id_dosen";
