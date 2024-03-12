# soal-2
#include <iostream>
#include <cmath>

using namespace std;

int main() {
    float sisiAlas, tinggiLimas, Volume, LuasPermukaanLimas, LuasSegitigaTegak, KelilingAlas, A;

    cout << "Masukkan panjang sisi alas limas = "; cin >> sisiAlas;
    cout << "Masukkan tinggi limas = "; cin >> tinggiLimas;


    Volume = (sisiAlas * sisiAlas * tinggiLimas) / 3;
    cout << "Volume limas = " << Volume << endl;



    LuasSegitigaTegak= (sisiAlas / 2) * sqrt(tinggiLimas * tinggiLimas + (sisiAlas / 2) * (sisiAlas / 2));
    LuasPermukaanLimas = sisiAlas * sisiAlas + 4 * LuasSegitigaTegak;
    cout << "Luas permukaan limas = " << LuasPermukaanLimas << endl;

    return 0;
}
