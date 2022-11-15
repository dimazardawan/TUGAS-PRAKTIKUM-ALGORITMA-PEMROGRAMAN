//# TUGAS-PRAKTIKUM-ALGORITMA-PEMROGRAMAN
//IF ELSE DAN DO WHILE
/*kenapa membutuhkan if-else?
if-else dibutuhan karena bila ada program atau sebuah kasus yang meminta mengidenfikasi sebuah objek dan atau memilih objek maka kita dapat memakai percabangan if-else. sehingga if-else memudahkan untuk membandingkan statement jika ya atau tidak. berfungsi untuk memecahkan persoalan dan mengambil satu keputusan dari beberapa pilihan sesuai kondisi yang sedang dialami program. Substatement di dalam badan pernyataan majemuk akan dieksekusi jika kondisi kebutuhan tersebut terpenuhi.
kapan membutuhkan if-else
kita memakai if-else ketika ingin mengambil satu keputusan dari beberapa pilihan kondisi.
kenapa membutuhkan perulangan do-while?
karena do-while berfungsi untuk mengulang program sehingga memudahkan untuk menyelesaikan kasus, misalnya mencetak 5 kalimat "Saya belajar C++", kita hanya menggunakan 1 kali perintah cout dan tidak 5 kali. Pada proses pengulangan do-while kondisi akan diperiksa diakhir  sehingga pengulangan yang pertama pasti terjadi atau dengan kata  lain ada minimal 1 program yang akan dijalankan sebelum masuk  kepengulangan
kapan membutuhkan perulangan do-while?
perulangan do while digunakan ketika kita ingin mengulang sebuah perintah dalam program sehingga tidak harus menuliskannya berulang kali.*/
#include <iostream>
#include <math.h>

using namespace std;

int main()
{
	string a;
	int pil;
	double keliling, luas, panjang, lebar;
	do {
		cout << "Nama:Dimaz Ardawan\nNim:22343042" << endl;
		cout << "Praktikum Algoritma Pemograman" << endl;
		cout << "1.Mencari Keliling Persegi Panjang\n2.Luas Persegi Panjang" << endl;
		cout <<"Masukkan Pilihan" << endl;
		cin >> pil;fflush(stdin);
		if (pil == 1){
			cout << "Mencari keliling persegi panjang\n" << endl;
			cout << "Masukkan panjang" << endl;
			cin >> panjang;fflush(stdin);
			cout << "Masukkan lebar" << endl;
			cin >> lebar;fflush(stdin);
			keliling=2*(panjang+lebar);
			cout << "Keliling persegi panjang adalah" << keliling << endl;
			}
		else if (pil == 2){
			cout << "Mencari luas persegi panjang\n" << endl;
			cout << "Masukkan panjang " << endl;
			cin >> panjang;fflush(stdin);
			cout << "Masukkan lebar " << endl;
			cin >> lebar;fflush(stdin);
			luas=panjang*lebar;
			cout << "Luas persegi panjang adalah" << luas << endl;
		}
		else cout << "Input tidak tersedia\n" << endl;
		cout << "Ingin menghitung ulang?(Y/T)" << endl;
		getline (cin, a);
		cout << "\n\n" << endl;
		} while (a!="t");
		return 0;
		
		}
