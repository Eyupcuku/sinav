#include <iostream>
#include <string>
using namespace std;

class ceptel {
public:
    string mrk;
    string mdl;
    double fyt;
};

void yazdir (const ceptel & tlfn) {
    cout << "Marka: " << tlfn.mrk << ", Model: " << tlfn.mdl << ", Fiyat: " <<tlfn.fyt<<endl;
}

int main() {
    ceptel tf1;
    tlf1.mrk = "Apple";
    tlf1.mdl = "Iphone 16 Pro";
    tlf1.fyt = 7999.99;

    ceptel tlf2;
    tlf2.marka = "Apple";
    tlf2.model = "Iphone 16 Pro Max";
    tlf2.fiyat = 9999.99;

    cout << "1. Urunun Bilgileri: ";
    yazdir(tlf1);

    cout << "2. Urunun Bilgileri: ";
    yazdir(tlf2);

    return 0;
}
