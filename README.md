# days-of-week-using-array
this  program will display the days of week using array and display the off days
#include <iostream>
using namespace std;

int main() {
    string week[]={"monday\n","tuesday\n","wednesday\n","thursday\n","friday\n","saturday\n","sunday\n"};
    for(int i=0;i<sizeof(week)/sizeof(week[0]);i++){
        cout<<week[i];
    }
    cout<<"off days:"<<week[5]<<week[6];
     

    return 0;
}
