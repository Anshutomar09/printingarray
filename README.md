# printingarray
#include <iostream>

using namespace std;

int main()
{
    int row,col,i,j;
    int arr[3][4];
    //taking input of the array
    for(col=0;col<4;col++){
        for(row=0;row<3;row++){
            cin>>arr[row][col];
        }
    }
    //printing the array
    for(i=0;i<3;i++){
        for(j=0;j<4;j++){
            cout<<arr[i][j]<<" ";
        }
        cout<<endl;
    }

    return 0;
}
