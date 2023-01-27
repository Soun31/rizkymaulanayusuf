#include <iostream>
using namespace std;
int main(){
	
	cout << "------------------------------------------------------" << endl;
	cout << "------------------------------------------------------" << endl;
	
	int pilihbuku,jumlah,hargabuku,total,bayar,kembali; 
	char bikin,iyakah;

do{
	system ("cls");
	cout << "----------------------------------------------------" << endl;
	cout << "  \t\t  Toko AL-Nassr  " << endl;
	cout << "----------------------------------------------------" << endl;
	cout << "\tJenis buku Yang di sediakan di toko : " << endl;
	cout << "\n\t1. Buku Komik " << endl;
	cout << "\n\t\t2. Buku Novel " << endl;
	cout << "\n\t\t\t3. Buku Sejarah " << endl;
	
	cout << "\n Pilih buku: ";
	cin  >>  pilihbuku ;
	
	system ("cls");
	switch (pilihbuku){
	case 1:
	cout << "\n ===+++===+++=== Buku Komik ===+++===+++=== " << endl;
	cout << " ++ Macam-macam Buku komik dan harganya  ++ " << endl;
	cout << "\n  A. komik JAGA UMI \t   : Rp.50.000,00" << endl;
	cout << "  B. komik KEMALA vol 1\t   : Rp.20.000,00" << endl;
	cout << "  C. komik CODERELIX \t   : Rp.40.000,00" << endl;
	cout << "  D. komik SI JUKUT \t   : Rp.45.000,00" << endl;
	cout << "  E. komik SANDHORA \t   : Rp.30.000,00" << endl;
	
	cout << "\n  Buku yang dipilih \t   : ";
	cin >> bikin;
	cout << "  Banyak buku yang dipilih : ";
	cin >> jumlah;
	
	if (bikin == 'A'){
		hargabuku = 50000;
	}else if(bikin == 'B'){
		hargabuku = 20000;
	}else if(bikin == 'C'){
		hargabuku = 40000;
	}else if(bikin == 'D'){
		hargabuku = 45000;
	}else if(bikin == 'E'){
		hargabuku = 30000;
	}else{
		cout << "\n* Tidak ada pilihan seperti itu * " << endl;
	}
	total = hargabuku * jumlah;
	cout << "  Harga buku \t\t   : Rp." << total << endl;
	
	cout << "  Pembayaran \t\t   : Rp.";
	cin >> bayar;
	
	kembali = bayar - total;
	cout << "  kembalian \t\t   : Rp." << kembali << endl;
	cout << "\n  Terimakasih sudah berbelanja di toko kami sahabat!" << endl;
	cout << "======================================================" << endl;

	cout << "\n Apakah anda ingin kembali ke menu awal (Y/N)?";
	cin >> iyakah;	
	break;
}	
	
	system ("cls");
	switch (pilihbuku){
	case 2:
	cout << "\n ===+++===+++=== Buku Novel ===+++===+++=== " << endl;	
	cout << " ++ Macam-macam Buku Novel dan harganya  ++ " << endl;
	cout << "\n  A. Novel Bisa Ini \t   : Rp.190.000,00" << endl;
	cout << "  B. Novel DILAN vol 1 \t   : Rp.120.000,00" << endl;
	cout << "  C. Novel DENGKUL !  \t   : Rp.125.000,00" << endl;
	cout << "  D. Novel SI DIDIN \t   : Rp.200.000,00" << endl;
	cout << "  E. Novel CINTA  \t   : Rp.160.000,00" << endl;
	
	cout << "\n  Buku yang dipilih \t   : ";
	cin >> bikin;
	cout << "  Banyak buku yang dipilih : ";
	cin >> jumlah;
	
	if (bikin == 'A'){
		hargabuku = 190000;
	}else if(bikin == 'B'){
		hargabuku = 120000;
	}else if(bikin == 'C'){
		hargabuku = 125000;
	}else if(bikin == 'D'){
		hargabuku = 200000;
	}else if(bikin == 'E'){
		hargabuku = 160000;
	}else{
		cout << "\n* Tidak ada pilihan seperti itu * " << endl;
	}
	total = hargabuku * jumlah;
	cout << "  Harga buku \t\t   : Rp." << total << endl;
	
	cout << "  Pembayaran \t\t   : Rp.";
	cin >> bayar;
	
	kembali = bayar - total;
	cout << "  kembalian \t\t   : Rp." << kembali << endl;
	cout << "\n  Terimakasih sudah berbelanja di toko kami sahabat!" << endl;
	cout << "======================================================" << endl;

	cout << "\n Apakah anda ingin kembali ke menu awal (O/N)?";
	cin >> iyakah;	
	break;
}
		
	system ("cls");
	switch (pilihbuku){
	case 3:
	cout << "\n ===+++===+++=== Buku Sejarah ===+++===+++===++ " << endl;	
	cout << " ++ Macam-macam Buku Sejarah dan harganya  ++ " << endl;
	cout << "\n  A. Sejarah Terbentuknya Evos\t: Rp.10.000,00" << endl;
	cout << "  B. Sejarah M1(one) Evos OURA\t: Rp.20.000,00" << endl;
	cout << "  C. Sejarah M1(one) Evos Vol 1\t: Rp.30.000,00" << endl;
	cout << "  D. Sejarah M1(one) Evos Vol 2\t: Rp.40.000,00" << endl;
	cout << "  E. Sejarah M1(one) Evos Vol 3\t: Rp.50.000,00" << endl;
	
	cout << "\n  Buku yang dipilih \t   : ";
	cin >> bikin;
	cout << "  Banyak buku yang dipilih : ";
	cin >> jumlah;
	
	if (bikin == 'A'){
		hargabuku = 10000;
	}else if(bikin == 'B'){
		hargabuku = 20000;
	}else if(bikin == 'C'){
		hargabuku = 30000;
	}else if(bikin == 'D'){
		hargabuku = 40000;
	}else if(bikin == 'E'){
		hargabuku = 50000;
	}else{
		cout << "\n* Tidak ada pilihan seperti itu * " << endl;
	}
	total = hargabuku * jumlah;
	cout << "  Harga buku \t\t   : Rp." << total << endl;

	cout << "  Pembayaran \t\t   : Rp.";
	cin >> bayar;
	
	kembali = bayar - total;
	cout << "  kembalian \t\t   : Rp." << kembali << endl;
	cout << "\n  Terimakasih sudah berbelanja di toko kami sahabat!" << endl;
	cout << "======================================================" << endl;
	
	cout << "\n Apakah anda ingin kembali ke menu awal (Y/N)?";
	cin >> iyakah;	
	break;
}
	
} while (iyakah == 'Y' || iyakah == 'y') ;
	
}


