# Python


### Program Perhitungan Penjumlahan Dengan Menggunakan Bahasa Pemograman Python
    print "Berikut ini Program Perhitungan Penjumlahan Dengan Menggunakan Bahasa Pemograman Python"
    praktikum = "Algoritma Pemrograman 2B"
    nama = Input("Masukkan Nama Anda : ")
    npm = Input("Masukkan NPM Anda : ")
    print ( " Halo, Nama saya " + nama + ", NPM Saya Adalah " + npm + " Sekarang Saya Belajar " + praktikum )
    nilai a = Input("Masukkan nilai a : ")
    nilai b	= Input("Masukkan nilai b : ")
    Hasil = a + b
    print (" Maka : " + " Hasil = a + b " + Hasil = a + b)
    
### Program Menghitung Kubus
    print ("Program Keliling, Luas, dan Volume Kubus")
    print
    def Keliling(x):
    return (12*x)

    def Luas(x):
    return (6*x*x)

    def Volume(x):
    return (x*x*x)
    x = int(raw_input("Masukkan Panjang Sisi Kubus :"))

    print 
    print ("Menu")
    print ("1. Keliling") 
    print ("2. Luas")
    print ("3. Volume")

    y = int(raw_input("Masukkan Pilihan Anda :"))
    print
    if y == 1:
    print "Keliling Kubus adalah " ,Keliling(x)
    elif y == 2:
    print "Luas Kubus adalah " ,Luas(x)
    elif y == 3:
    print 
    print "Volume Kubus adalah " ,Volume(x)
    else:
    print "Tidak Ada Pilihan"
