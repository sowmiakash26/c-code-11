#include<stdio.h>
int main(){
   int arr[5]={1,2,3,5};
   int n=5;
   int sum=n*(n+1)/2;
   int arrsum=0;
   for(int i=0;i<n-1;i++){
     arrsum+=arr[i];
   }
   int val=sum-arrsum;
   printf("The missing number is %d",val);
   return 0;
}
