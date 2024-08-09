# Exp_4
Aim -> To study and implement C++ Bitwise Operators.

Theory -> Bitwise Operators are the operators that are used to perform operations on the bit level on the integers. While performing this operation integers are considered as sequences of binary digits. Its symbols and functions are as follows:

1.Bitwise AND (&)

2.Bitwise OR (|)

3.Bitwise XOR (^)

4.Bitwise NOT (~)

5.Left Shift (<<)

6.Right Shift (>>)

CODE
```
#include<iostream> 
using namespace std; 
int main()  
{ 
int a, b, x, y;
cout<<"Enter a number: ";                           
cin>>a; 
cout<<"Enter another number: ";                  
cin>>b; 
cout<<"Binary AND: "<<(a&b)<<"\n";              
cout<<"Binary OR: "<<(a|b)<<"\n";                
cout<<"Binary XOR: "<<(a^b)<<"\n";               
cout<<"Left Shift: "<<(a<<b)<<"\n";             
cout<<"Right Shift: "<<(a>>b)<<"\n";            
cout<<"Complement of a: "<<(x=~a)<<"\n";         
cout<<"Complement of b is: "<<(y=~b)<<"\n";      
return 0;
}
```
OUTPUT:

<img width="406" alt="Screenshot 2024-08-09 at 12 28 55" src="https://github.com/user-attachments/assets/d676acc0-e818-47dd-ac9d-5e50ce302038">

Conclusion -> I learnt about bitwise operators.
