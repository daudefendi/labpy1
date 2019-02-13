# labpy1
# CARA MEMBUAT PROGRAM UNTUK MENENTUKAN BILANGAN TERBESAR DAN TERKECIL
Halo Teman-teman, hari ini saya akan berbagi bagaimana cara membuat program sederhana untuk menentukan suatu bilangan terbesar atau terkecil pada bilangan, sebelumnya kita sudah membuat tutorial bagaimana cara membuat sebuah repositori baru di github.
syarat agar bisa membuat programnya adalah sebagai berikut :

1. mempunyai account di github
2. install git client
3. install sublime text atau notepad dll (digunakan untuk membuat script)
4. install python
oke langsung saja kita praktekan cara membuatnya, check this out !!!

# PERTAMA
kita akan mendownload terlebih dahulu sublime text, agar memudahkan kita dalam membuat script program yang akan kita biat, cara nya 
buka google kemudia search "sublime text editor", kemudian enter dan klik download for windows jika kalian menggunakan OS WINDOWS.
Berikut contoh gambarnya :

# ![1](https://user-images.githubusercontent.com/46699723/52687564-276b2580-2f85-11e9-97ab-a3ff7a738022.png)
# ![2](https://user-images.githubusercontent.com/46699723/52687568-276b2580-2f85-11e9-98c5-032b08cd724f.png)

# ![3](https://user-images.githubusercontent.com/46699723/52687572-2803bc00-2f85-11e9-9713-f4d4484c9c20.png)

# KEDUA
  Setelah kita berhasil menginstall sublime, sekarang kita akan membuat script nya terlebih dahulu, 
  dengan cara buka sublime text klik "File" kemudian klik "New FILE" kemudian save file tersebut menggunakan format 
  python yaitu .py, misalnya "project1.py", dengan menyimpan file dengan format python akan memudahkan kita dalam membuat 
  script dan juga menggunkan sublime text ini mempermudah dalam membuat script dengan tampilan tulisan yang berwarna-warni 
  kita dapat mengetahui mana command atau perintah yang benar ataupun salah dalam suatu script. Berikut Contoh Gambarmya :
  
# ![4](https://user-images.githubusercontent.com/46699723/52687573-2803bc00-2f85-11e9-87dc-f9f53d45c988.png)

# ![5](https://user-images.githubusercontent.com/46699723/52687574-289c5280-2f85-11e9-9b81-fdfcf90239f7.png)

# ![6](https://user-images.githubusercontent.com/46699723/52687576-289c5280-2f85-11e9-8145-191a2ac5e2d1.png)

# KETIGA
  Setelah menyimpan file dalam bentuk python (.py) sekarang kita akan membuat scriptnya terlebih dahulu di sublime text yang
  sudah kita simpan tadi. Mari Kita mulai membuat scriptnya.
  
# SCRIPT 1
  print ('Program Untuk Menentukan Bilangan Terbesar dan Terkecil')
  perintah diatas (SCRIPT 1) digunakan untuk menampilkan Judul/Title Program yang akan kita buat.
  
  # ![7](https://user-images.githubusercontent.com/46699723/52687578-2934e900-2f85-11e9-90fe-e172511c7e78.png)
  
# SCRIPT 2
  def pengulangan():
    print ('masukkan 3 bilangan yang diinginkan!')
    a=int(input('bilangan1 = '))
    b=int(input('bilangan2 = '))
    c=int(input('bilangan3 = '))
  Perintah kedua yaitu menggunakan *def* 
  yang mana fungsi nya ialah perintah standar dalam python untuk mendefinisikan sebuah 
  fungsi.
  Perintah *int* 
  yang mana fungsinya ialah mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).
  Perintah *input* 
  yang mana fungsinya ialah untuk menerima baris input dari user dan mengembalikannya dalam bentuk string.
  
  # ![8](https://user-images.githubusercontent.com/46699723/52687579-2934e900-2f85-11e9-8c12-d5e4aeda6155.png)

  
# SCRIPT 3 
# ![9](https://user-images.githubusercontent.com/46699723/52687581-29cd7f80-2f85-11e9-8516-b2889120530e.png)           

Perintah *if*
 if dalam Python dijalankan untuk memeriksa apakah kondisi ini adalah bernilai benar atau salah.
 Perintah *if else*
 if-else adalah membuat statemen untuk kondisi yang bernilai true dan false.
 Perintah *elif*
 Masalahnya bagaimana jika kita mempunyai banyak kondisi untuk dieksekusi dalam Python ? Dengan artian bahwa tidak hanya 
 satu kondisi saja yang bernilai True bisa jadi dua kondisi atau berapapun kondisi yang bernilai true. 
 Solusinya adalah Chained Conditionals atau Kondisi Berantai yaitu dengan menggunakan fungsi if, elif dan else.


# KEEMPAT
 print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya':
        return pengulangan()
    if x=='tidak':
        print('terimakasih telah menggunakan program ini. DAUD YUSUF EFENDI T1.18.A1')

pengulangan()

Perintah *return* berfungsi mengulang kembali sebuah perintah ke awal bila dilakukan perintah mengulang.
# ![10](https://user-images.githubusercontent.com/46699723/52688086-54203c80-2f87-11e9-8e0e-b531851ab595.png)

Baiklah kita telah selesai membuat script dan hasil scriptnya digambar sebagai berikut :
# ![11](https://user-images.githubusercontent.com/46699723/52687583-2a661600-2f85-11e9-9dd0-55b4848a8925.png)

# KEEMPAT
Setelah menyelesaikan scriptya mari kita uji coba apakah work atau tidak nya script yang kita buat, kita akan membuat 3 kali percobaan. berikut hasilnya di gambar :

Percobaan 1
# ![12](https://user-images.githubusercontent.com/46699723/52687584-2a661600-2f85-11e9-9665-20d63bb3511c.png)

Percobaan 2
# ![13](https://user-images.githubusercontent.com/46699723/52687585-2afeac80-2f85-11e9-8fca-ffe99ff90206.png)

Percobaan 3
# ![14](https://user-images.githubusercontent.com/46699723/52687586-2afeac80-2f85-11e9-96de-6b31dfe905e8.png)

SELESAI
# ![15](https://user-images.githubusercontent.com/46699723/52687587-2b974300-2f85-11e9-91ef-abec11d6bf4d.png)


Demikianlah Cara membuat program sederhana untuk menentukan bilangan terbesar dan terkecil.








  
