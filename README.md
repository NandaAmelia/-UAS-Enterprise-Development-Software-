# -UAS-Enterprise-Development-Software-

Nama : Nanda Amelia
Nim : 191402015

Link Youtube : https://youtu.be/0UWO0xgXQMM


Tutorial OutSystems Reactive Web - Logic ( Defining Logic Exercise )
![2](https://user-images.githubusercontent.com/66839985/147528268-d2ddf435-ac0f-4bd8-9a2a-07c04034a030.jpg)

1.	Buka aplikasi OutSystems, kemudian Select open file

![3](https://user-images.githubusercontent.com/66839985/147528278-e3415061-e4e8-4aa9-ae03-24868e55f7d7.jpg)

2.	ubah jenis file menjadi OutSystems Application Pack (.oap), cari lokasi Quickstart Masukkan file Exercise.oap 

![4](https://user-images.githubusercontent.com/66839985/147528282-bb798b7f-708e-4729-9612-efcac83d27fc.png)

Pilih konfirmasi baru, pilih Lanjutkan

![5](https://user-images.githubusercontent.com/66839985/147528286-14bfccc5-5e7a-4846-8db2-fce776583e7b.jpg)

3.	setelah berhasil diinstall klik Logic exerchise

![6](https://user-images.githubusercontent.com/66839985/147528287-900abb3a-b269-442f-b420-9953d67642af.jpg)

4.	Buka Aplikasi di servise studio

![7](https://user-images.githubusercontent.com/66839985/147528290-8850ac89-d891-4076-8f1e-bcb9131b8a7b.jpg)

-------

Negative Or Positive 
•	Dengan mengklik tombol dengan nomor, aplikasi akan menampilkan pesan yang menunjukkan apakah nomor tersebut positif atau negatif.

1.	Klik interface dan Home, ada 3 tindakan layar

![8](https://user-images.githubusercontent.com/66839985/147528296-df4e587c-3220-4bd8-ab09-a5f5f262db63.jpg)

2.	Tiap layar memiliki empat tombol yang memanggil Tindakan Layar Negatif Atau Positif. Masing-masing tombol ini terkait dengan tindakan layar tersebut dengan nilai yang berbeda untuk Parameter Input Angka.

Klik 2 kali pada button NegativeorPositive

Drag dan drop if diantara start dan end

![9](https://user-images.githubusercontent.com/66839985/147528298-bc8865a4-ead4-48e4-8c8d-59aa34de787b.jpg)

3.	Set condition dengan Number < 0
Drag messsge di sebelah if 

![10](https://user-images.githubusercontent.com/66839985/147528300-0ca92a20-fc4a-44d8-ab7d-294593858e4c.jpg)

4.	Set message property dengan “Negative number.”

![11](https://user-images.githubusercontent.com/66839985/147528303-26cc402e-d09d-4b5e-ad97-26addccf64c9.jpg)

5.	Seret Akhir dan letakkan di sebelah kanan Pesan, lalu buat konektor di antara keduanya.

![12](https://user-images.githubusercontent.com/66839985/147528305-df15bfbc-e8db-48ef-980e-6ec437f36f69.jpg)

-	Terbitkan modul, dan uji empat tombol di dalam tombol Negatif atau Positif? daerah.
-	Buka aplikasi di browser untuk memvalidasi bahwa setiap tombol menampilkan pesan info yang benar.
-	Perhatikan bahwa ketika tombol dengan 0 ditekan, pesan umpan balik Angka Positif ditampilkan

6.	Drag dan drop if dan letakkan diantara start dan if yang ada

![13](https://user-images.githubusercontent.com/66839985/147528310-d7c64cbe-9a8d-4bcd-9753-721e6a64485b.jpg)

7.	Atur Kondisi If baru ke : “Number Is ZERO”

![14](https://user-images.githubusercontent.com/66839985/147528313-04e835ce-8356-46f8-b087-249823503434.jpg)

Seret simpul Akhir dan letakkan di sebelah kanan Pesan yang baru dibuat, lalu hubungkan keduanya. Alirannya akan terlihat seperti ini
Publikasikan modul dan uji kembali tombol yang ada di dalam Negatif atau Positif? daerah.


![15](https://user-images.githubusercontent.com/66839985/147528317-ef38a320-9832-43f2-8b0c-aaa8453dfe15.jpg)

---------

•	implementasikan Screen Action lainnya. Yang ini akan menganalisis nomor tertentu dan mengembalikan salah satu opsi berikut: "<1K", "<10K", "<100K" atau ">=100K".

1.	klik 2 kalo pada layat OrderOfMagnitude

![16](https://user-images.githubusercontent.com/66839985/147528320-cda2a0cd-4782-48cc-8762-13bb933c92ee.jpg)

2.	Tarik node Switch dan letakkan di antara Start dan End.

![17](https://user-images.githubusercontent.com/66839985/147528322-067a6157-3bf5-429b-afa3-bdf9152b030e.jpg)

3.	Seret Message dan letakkan di sebelah kanan Switch

![18](https://user-images.githubusercontent.com/66839985/147528324-155bea70-7399-4281-9c6f-2196d53522ad.jpg)

4.	Setel properti Message dari elemen yang baru ditambahkan ke "<1K", lalu buat konektor dari Switch ke Message.

![19](https://user-images.githubusercontent.com/66839985/147528327-513f3be9-43c3-4651-895f-56acf33b8f97.jpg)

5.	Atur Kondisi Konektor 1 yang dibuat pada langkah sebelumnya ke Nomor < 1000

![20](https://user-images.githubusercontent.com/66839985/147528328-eec91960-07b7-4fe6-9386-86c831051927.jpg)

6.	Seret Pesan lain dan letakkan di bawah yang sudah ada

Ulangi tiga langkah sebelumnya untuk membuat logika Anda terlihat seperti berikut:

![21](https://user-images.githubusercontent.com/66839985/147528330-e46a479e-fc51-4de0-bf5e-1bf19c8c992d.jpg)
![22](https://user-images.githubusercontent.com/66839985/147528331-57241098-2e35-49f8-9060-46e9a0678745.jpg)

7.	Seret satu simpul Akhir dan jatuhkan ke kanan aliran, lalu hubungkan tiga Pesan yang ada ke simpul Akhir itu., aliran nya akan terlihat seperti ini

![24](https://user-images.githubusercontent.com/66839985/147528333-26a80dab-63f5-4300-9d65-68c7be252316.jpg)

Publikasikan modul untuk menyimpan perubahan terbaru ini.
Klik tombol Open in Browser dan uji lima tombol yang ada pada area Order of Magnitude.

-----

•	implementasikan logika Screen Action terakhir yang akan menghitung faktorial suatu bilangan.

Faktorial adalah fungsi matematika yang direpresentasikan sebagai n! dan pada dasarnya adalah perkalian semua bilangan antara n dan 1. Di bawah ini Anda memiliki beberapa contoh fungsi faktorial
4! = 4 x 3 x 2 x 1 = 24
7! = 7 x 6 x 5 x 4 x 3 x 2 x 1 = 5040

1.	Beralih ke tab Logic, klik kanan folder Server Actions, lalu pilih Add Server Action

Atur Nama Tindakan Server ke CalcFactorial.

![25](https://user-images.githubusercontent.com/66839985/147528334-1e733b70-9db7-4221-8b1f-17c6877eaec4.png)

2.	Klik kanan Tindakan Server CalcFactorial dan pilih Tambahkan Parameter Input

![26](https://user-images.githubusercontent.com/66839985/147528340-07d64c87-d161-4532-a0b9-9f422837ab34.jpg)

3.	Atur Nama Parameter Input ke N, dan pastikan Tipe Data diatur ke Integer.

![27](https://user-images.githubusercontent.com/66839985/147528342-db4d70c1-3098-42c1-b7d4-1c073f0710dd.jpg)

4.	Klik kanan CalcFactorial dan pilih Add Output Parameter

![28](https://user-images.githubusercontent.com/66839985/147528345-2ab12bcb-7602-4112-b871-ee760d40f0da.jpg)

5.	Atur Nama Parameter Output ke Hasil, pastikan Tipe Data diatur ke Integer, dan Nilai Defaultnya adalah 1.

![29](https://user-images.githubusercontent.com/66839985/147528348-22da95eb-5ac7-4882-839b-8f1c496a6ec5.jpg)

6.	Seret If dan jatuhkan di antara Awal dan Akhir
Atur Kondisi If ke
T > 1

![30](https://user-images.githubusercontent.com/66839985/147528349-0b9b424c-3713-4427-bcdd-f7e6a5f38dd8.jpg)

7.	Tarik assign dan letakkan disebelah if

![31](https://user-images.githubusercontent.com/66839985/147528350-83fc3db7-4944-4da3-b370-55d2b204f406.jpg)

8.	Buat dua conector seperti ini

![32](https://user-images.githubusercontent.com/66839985/147528351-3b69f735-4730-4130-8e01-5e5cd4779ee2.jpg)

9.	Klik kanan Folder Pengecualian dan pilih Tambahkan Pengecualian Pengguna

![33](https://user-images.githubusercontent.com/66839985/147528353-79d8ea4f-ef5f-4bbf-8881-fd981a759d3d.png)
![34](https://user-images.githubusercontent.com/66839985/147528356-f4fbae1c-167c-42d9-81bc-8e3f039afd80.jpg)

10.	Seret If lain dan letakkan di antara Start dan yang sudah ada

![35](https://user-images.githubusercontent.com/66839985/147528357-deda8dca-3360-4a6f-9591-fd76dfdde701.jpg)

Setel Nama Pengecualian ke NegativeNumberException

![36](https://user-images.githubusercontent.com/66839985/147528361-ce1a95c7-4581-465c-b899-0fd4f82a1537.jpg)

11.	Pilih elemen Raise Exception, dan di propertinya atur Exception Message ke "Number must be positive.".

![37](https://user-images.githubusercontent.com/66839985/147528364-ffdac0ca-3340-4b97-b980-ba1be99d3fb5.jpg)

12.	Kembali ke interface dan klik factorial

![38](https://user-images.githubusercontent.com/66839985/147528366-36f3da0e-0ce5-4694-8083-a2af36b35e2b.jpg)

13.	Tarik tindakan Run Server Action dan letakkan diantara start dan end

![39](https://user-images.githubusercontent.com/66839985/147528370-94149ce3-c940-4048-b3ac-bab7ba19de97.jpg)

14.	Pada dialog, pilih Tindakan Server CalcFactorial yang kita buat dan implementasikan pada langkah sebelumnya, lalu klik OK.

![40](https://user-images.githubusercontent.com/66839985/147528373-2bc09f00-8d2f-4f0a-85f2-07e45e737b36.jpg)

15.	Di properti, atur argumen N ke parameter input Number.

![41](https://user-images.githubusercontent.com/66839985/147528375-eb8d117b-07b1-4b95-9540-e1f1aa16388f.jpg)

16.	Seret Pesan dan jatuhkan di antara Tindakan Jalankan Server dan Akhir

![42](https://user-images.githubusercontent.com/66839985/147528379-d3852066-4939-48f6-8c0b-5dbd823cf59c.jpg)

Klik dua kali Pesan, dan atur ekspresinya ke
"Faktorial dari " + Bilangan + " adalah " + CalcFactorial.Hasil
1! = 1
3! = 6
8! = 40320
-5! = (Pengecualian Nomor Tidak Valid)





~ TERIMA KASIH ~
