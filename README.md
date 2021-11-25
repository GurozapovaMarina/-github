# -github
#include <iostream>
#include <math.h>
using namespace std;
int main() 
{
    float a,b,c,d,e,f,p;
    cin>>a>>b>>c;
    p=(a+b+c)/2;
    d=2*sqrt(p*(p-a)*(p-b)*(p-c))/a;
    e=2*sqrt(p*(p-a)*(p-b)*(p-c))/b;
    f=2*sqrt(p*(p-a)*(p-b)*(p-b))/c;
    cout << d <<" "<< e << " " <<f;
    return 0;
} ghkfkfkvvdd
