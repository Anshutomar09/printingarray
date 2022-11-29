# printingarray
#include <iostream>

using namespace std;

int main()
{
    int row,col;
    int arr[3][4];
    for(col=0;col<4;col++){
        for(row=0;row<3;row++){
            cin>>arr[col][row];
        }
    }
    for(col=0;col<4;col++){
        for(row=0;row<3;row++){
            cout<<arr[col][row];
        }
    }

    return 0;
}
