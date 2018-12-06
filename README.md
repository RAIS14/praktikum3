# praktikum3

\*Latihan1 #Menentukan Bilangan Terbesar dari Banyak Bilangan.


````
Alur Algoritma.
	1.Mendeklarasikan int i,max,a, dan x.
	2.mendeklarasikan variabel a dan x sebagai nilai inputan.
	3.Mendeklarasikan variabel i sebagai perulangan.
	4.Mendeklarasikan variabel max sebagai pengingat nilai.
	5.Membuat rumus perulangan untuk menentukan banyak bilangan yang akan di bandingkan
		for (i;i<a;i++)
	6.Menginputkan nilai a.
	7.menginputkan nilai x.
	8.Membandingkan nilai x dengan max
		if ( x> max) // jika x lebih besar dari max
	    	max= x   // maka nilai max adalah x
````
\*berikut kode program lengkapnya :
````
#include <iostream>

int main()
{
	int i= 0;
	int max = 0;

	int a,x;
	std::cout << "masukan jumlah bilangan : ";

	std::cin >> a;

	for (i;i<a;i++)
	{
		std::cout << "masukan bilangan ke - " << i+1 << ": " ;
		std::cin >> x;
		if (x>max)
			max=x;
	}

	std::cout << "bilangan terbesarnya adalah : " << max;
	return 0;
}

````
\*berikut adalah hasilnya :

![img]https://raw.githubusercontent.com/RAIS14/praktikum3/master/hasil_latihan1.png

\*berikut flowchart nya:
![img]https://raw.githubusercontent.com/RAIS14/praktikum3/master/flowchart.lat1.jpg


\*latihan2 #mengurutkan bil.terkecil sampai bil.terbesar

````
Alur Algoritmanya
	1.Mendeklasrasikan int a,b,c sebagai variabel input
	2.Membandingkan setiap variabel untuk menentukan nilai yang terkceil sampai yang terbesar
	3.Dengan menggunkan rumus if dan percabangan
		if (a<b)
    		    {
       		       if (b<c)
                       cout<< a << "  " << b << "  " <<c;
		Jika a lebih kecil dari b dan jika b lebih kecil dari c maka yang akan ditampilkan
		a b c
````
\*berikut kode programnya :
````
#include <iostream>

using namespace std;
int main()
{
	int a,b,c;

	cout << "masukan nilai pertama : ";
	cin >> a ;
	cout << "masukan nilai kedua : ";
	cin >> b ;
	cout << "masukan nilai ketiga : ";
	cin >> c ;



	if (a<b){
		if (b<c)
		cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
		<< a << " "<< b << " " <<c ;
		else{
			if (a<c)
				cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
				<< a << " "<< c << " " <<b ;
			else
				cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
				<< c << " "<< a << " " <<b ;
		}
	}

	else
	{
		if (a<c)
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
			<< b << " "<< a << " " <<c ;
		else
		{
			if(b<c)
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
			<< b << " "<< c << " " <<a;
			else
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
			<< c << " "<< b << " " <<a ;
		}
	}


	return 0;
}

````
\*berikut hasilnya :
![img]https://raw.githubusercontent.com/RAIS14/praktikum3/master/hasil_latihan2.png

\*berikut adalah flowchartnya :
![img]https://raw.githubusercontent.com/RAIS14/praktikum3/master/flowchart.lat2.jpg

