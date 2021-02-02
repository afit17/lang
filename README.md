# Python


### Program Perhitungan Penjumlahan Dengan Menggunakan Bahasa Pemograman Python
    #print "Berikut ini Program Perhitungan Penjumlahan Dengan Menggunakan Bahasa Pemograman Python"

praktikum = "Algoritma Pemrograman 2B"
nama = Input("Masukkan Nama Anda : ")
npm = Input("Masukkan NPM Anda : ")
print ( " Halo, Nama saya " + nama + ", NPM Saya Adalah " + npm + " Sekarang Saya Belajar " + praktikum )
nilai a = Input("Masukkan nilai a : ")
nilai b	= Input("Masukkan nilai b : ")
Hasil = a + b
print (" Maka : " + " Hasil = a + b " + Hasil = a + b)
    
### Sintak Besar Kecil
    #include <stdio.h>

    int a, b, c, max, min;
    void fungsi_bk(){
        if (a > b){
            max = a;
            min = b;
        }
        else{
            max = b;
            min = a;
        }
        if (c > max)
            max = c;
        if (c < min)
            min = c;
    }

    void main(){
        printf("Masukan bilangan 1 : ");
        scanf("%d", &a);
        printf("Masukan bilangan 2 : ");
        scanf("%d", &b);
        printf("Masukan bilangan 3 : ");
        scanf("%d", &c);
        fungsi_bk();
        printf("\nBilangan terbesar : %d\n", max);
        printf("Bilangan terkecil : %d", min);
    }
