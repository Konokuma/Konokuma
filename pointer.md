#include <iostream>
using namespace std;

struct DongVat{
   
string ten, den_tu;
int tuoi;
};
int main(){
    DongVat x;
    x.ten = "ho";
    x.den_tu = "rung";
    x.tuoi = 10;
    DongVat *ptr = &x;
    cout <<"ten con vat:"<<" "<< (*ptr).ten << endl;
    DongVat *quy_hiem = ptr;
    cout <<"tuoi tho dong vat quy hiem:"<<" "<< (*quy_hiem).tuoi << endl;
 return 0;
}
