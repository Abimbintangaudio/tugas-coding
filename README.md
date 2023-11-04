# tugas-coding
# PENJELASAN NOMOR 1

        String name = "Abim Bintang Audio ";
        String NPM = "G1A023073" ;
        System.out.println("Nama : " + name);
        System.out.println("NPM : " + NPM);
        System.out.println("=============");

code diatas merupakan code untuk nama dan NPM kita dengan menggunakan kode string dan  System.out.println untuk mengeprint string

perulangan for
        
        for (int i = 0 ; i<=100 ; i++){

 for merupakan kode yang digunakan untuk mengulangi sejumlah pernyataan atau blok kode secara berulang.

 perulangan if else 

                if (i>= 10 ) {
                System.out.println(name);
                }
                else {
               System.out.println(i);

if else adalah salah satu konstruksi dasar dakam pemograman yang digunakan untuk mangambil keputusan berdasarkan kondisi tertentu.

![Screenshot (111)](https://github.com/Abimbintangaudio/tugas-coding/assets/149797285/dac2b226-aee2-465e-b1ea-5fb4d8650e51)

# PENJELASAN nomor 2

input data dengan kode int

int start = 1;
        int end = 100;
        int countOdd = 0;
        int countEven = 0;

int adalah tipe data yang digunakan untuk merepresentasikan bilanagan bulat. 

perulangan if else while 

                while (start <= end) {
                if (start % 2 == 0) {
                countEven++;
            } else {

 if else while adalah yang digunakan untuk menjalankan sekelompok pernyataan berulang kali selama kondisi tertentu tetap benar.

![Screenshot (112)](https://github.com/Abimbintangaudio/tugas-coding/assets/149797285/39fe2ba4-5a16-42c9-84ce-ff6f9690682c)

 # PENJELASAN nomor 3

scanner 

                 Scanner input = new Scanner(System.in);
                 
scanner adalah alat yang sangat berguna dalamm pemograman java untuk mengambil input dari pegunaan, memprossnya, dan menggunakan dalam progam tersebut.

input data dengan kode int

        System.out.print("Masukkan tanggal lahir (1-31): ");
        int tanggal = input.nextInt();

        System.out.print("Masukkan bulan lahir (1-12): ");
        int bulan = input.nextInt();

        String zodiak = determineZodiac(tanggal, bulan);
        System.out.println("Zodiak Anda adalah " + zodiak);

        input.close();

sama seperti int di atas yang digunakan untuk merepresentasikan bilangan bulat.

return

          return "Aries";
        } else if ((bulan == 4 && tanggal >= 20) || (bulan == 5 && tanggal <= 20)) {
            return "Taurus";
        } else if ((bulan == 5 && tanggal >= 21) || (bulan == 6 && tanggal <= 20)) {
            return "Gemini";
        } else if ((bulan == 6 && tanggal >= 21) || (bulan == 7 && tanggal <= 22)) {
            return "Cancer";
        } else if ((bulan == 7 && tanggal >= 23) || (bulan == 8 && tanggal <= 22)) {
            return "Leo";
        } else if ((bulan == 8 && tanggal >= 23) || (bulan == 9 && tanggal <= 22)) {
            return "Virgo";
        } else if ((bulan == 9 && tanggal >= 23) || (bulan == 10 && tanggal <= 22)) {
            return "Libra";
        } else if ((bulan == 10 && tanggal >= 23) || (bulan == 11 && tanggal <= 21)) {
            return "Scorpio";
        } else if ((bulan == 11 && tanggal >= 22) || (bulan == 12 && tanggal <= 21)) {
            return "Sagittarius";
        } else if ((bulan == 12 && tanggal >= 22) || (bulan == 1 && tanggal <= 19)) {
            return "Capricorn";
        } else if ((bulan == 1 && tanggal >= 20) || (bulan == 2 && tanggal <= 18)) {
            return "Aquarius";
        } else {
            return "Pisces";

return adalah kata kunci yang digunakan untuk mengembalikan nilai dari suatu fungsi atau metode. dan juga dapat menghentikan eksekusi fungsi dan mengembalikan nilai kembali ke pemanggil 

![Screenshot (113)](https://github.com/Abimbintangaudio/tugas-coding/assets/149797285/20304ffd-ab4c-4f58-ab3b-50c34a255e60)

# PENJELASAN nomor 4

data array 

        String [] hewan = {
        "kuda" , "kucing" , "ular" , "monyet" , "ikan"

string pada data array adalah tipe data yang digunakan untuk merepresentasikan teks atau rangkain karakter. string pada java yaitu "welcome to java" sedangkan array adalah struktur data yang digunakan untuk menyimpan koleksi elemen dengan tipe data yang sama.

perulangan for 

        for (int i=0 ; i< hewan.length; i++){
        System.out.println(hewan[i]);

perulangan for sama seperti yang diatas yaitu untuk mengulang sejumlah pernyataan dan blok kode secara berulang 

 ![Screenshot (114)](https://github.com/Abimbintangaudio/tugas-coding/assets/149797285/5e7345cf-d715-447d-8249-d92fec98af12)
