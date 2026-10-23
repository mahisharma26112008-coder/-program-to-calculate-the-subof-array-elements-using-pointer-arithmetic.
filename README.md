# -program-to-calculate-the-subof-array-elements-using-pointer-arithmetic.

#include<iostream>
  using namespace std;  
    int main(){
     int arr[5]={10,20,30,40,50};
     int *p=arr;
    int result=*p;
      cout<<*p;

        for(int i=1;i<5;i++){
            result=result-*(p+i);
        }

        cout<<"sub of elements : "<<result;
        
         return 0;

    }
        

        

        
