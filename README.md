# Road Map Belajar C++
#### Memahami  Printing(output) dan Masukan(input)
**Keluaran** & **Masukan** E.g :
```cpp
std::cout << "Hallo World.!"; // untuk output
std:cin >> nama_variabel; // untuk input
```

Contoh Sederhana :
```cpp
#include <iostream>

int main(){
	int nilai;
	std::cout << "Masukan Nilai : ";
	std::cin >> nilai;
	std::cout << "Nilai yang anda masukan adalah : ";
	std::cout << nilai << std::endl;
}
```

#### Memahami Variable, Inisialisasi dan Deklarasi
variabel pad C++ ditandai dengan tipe datanya contoh kita ingin membuat varibel yang dimana ingin menyimpan bilangan bulat kita bisa gunakan tipe data integer, contoh : 

```cpp
// int ini adalah integer dan nilai merupakan nama variabelnya
int nilai;
```