#include <iostream>

int main(){
double xn,xk,dx;
double a,b,c;
cout << "Enter xn,xk,dx,a, b, c: ";
cin >>xn>>xk>>dx>>a>>b>>c;
if (-(int(a)|int(b))&-(int(a)|int(c)) !=0){
for (double x=xn; x<=xk;x+=){
double f;
if (x<0 && b!=0) f=(a*x*x*x+b*x*x);
else if(x>0 && b=0) f=(x-a)/(x-c);
else f=(x+5)/(c*(x-10));
cout<<"x="<<x<<"\tf="<<f<<endl;
}
}
else{
for (double x=xn; x<=xk;x+=){
int f;
if (x<0 && b!=0) f=(a*x*x*x+b*x*x);
else if(x>0 && b=0) f=(x-a)/(x-c);
else f=(x+5)/(c*(x-10));
cout<<"x="<<x<<"\tf="<<f<<endl;
}
}

