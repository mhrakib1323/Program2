
#include <iostream>

int main() {
    int a=5,b=6;
    a+=1;
    b-=1;
    a%=2;
    b/=2;
    a++;
    b--;
    std ::cout<<a++;
    std ::cout<<++b ;
    std ::cout<<(a<=5 && 10>=b)<< std ::endl ;
    std ::cout<<"Addition : "<< a + b<<std::endl ;
    std ::cout<<"Subtraction: "<<a - b<<std ::endl;
    std ::cout<<"Multiplication: "<<a * b<<std ::endl ;
    std :: cout<<"Division: "<<a / b<<std ::endl ;
    std ::cout<<"Modulus: "<<a % b ;
    

    return 0;
    }
