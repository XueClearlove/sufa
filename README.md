最简单的排序-桶排序
#include"iostream"using namespace std;int main(){ int a[11],i,j,t; for(i=0;i<11;i++)  a[i]=0; for(i=1;i<=5;i++) {  cin>>t;  a[t]++; } for(i=0;i<=10;i++) {  for(j=1;j<=a[i];j++)  {   cout<<i;  } } return 0;}
