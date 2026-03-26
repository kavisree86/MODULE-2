# Ex.No:1
# Ex.Name:Write A CPP Program to allocate memory dynamically for a double array. (Note: p_array = new type [size]; )
## Aim:

To write a C++ program that overloads a function to perform the sum of two integers and the sum of three integers.
## Algorithm:
Start the program.
Define a class Addition with two overloaded functions named sum:
One function takes two integer arguments and returns their sum.
Another function takes three integer arguments and returns their sum.
In the main() function, create an object of the class.
Call both overloaded functions to compute the sum of two and three integers.
Display the results.
End the program.




## Program:
```
#include<iostream>
using namespace std;
class fun{
    public:
    void add(int a,int b){
        cout<<"Sum of two Numbers="<<a+b<<endl;
    }
    void add(int a,int b,int c){
        cout<<"Sum of three Numbers="<<a+b+c;
    }
};
int main()
{
    int a,b,c;
    cin>>a>>b;
    fun f;
    f.add(a,b);
    cin>>a>>b>>c;
    f.add(a,b,c);
}
```


## Output:

<img width="553" height="255" alt="image" src="https://github.com/user-attachments/assets/eed06556-562c-45bb-98c2-db9640b8cbb5" />


## Result:
The program successfully demonstrates function overloading by computing the sum of two integers and the sum of three integers using the same function name.
