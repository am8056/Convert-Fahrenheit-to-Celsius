# Convert-Fahrenheit-to-Celsius

#include<iostream>
using namespace std;
int main(){
    int start,end,size;
    cout<<"Enter the start point ";
    cin>>start;
    cout<<"\n Enter the end point ";
    cin>>end;
    cout<<"\n Enter the size ";
    cin>>size;
    int i=start;
while(i<=end){
    int c;
    c=(i-32)*5/9;
    cout<<s(3)<<i<<" "<<c;
    cout<<endl;
    i=i+10;
}
return 0;
}
