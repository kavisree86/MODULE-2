# Ex.No:4
# Ex.Name:Write a CPP Program to overload the first function to perform addition, second function to perform subtraction, third function to perform multiplication and the fourth function to perform division.
## Date:
## Aim:
To write a CPP Program to overload the first function to perform addition, second function to perform subtraction, third function to perform multiplication and the fourth function to perform division.

## Algorithm:

1.Start the program.

2.Define a class Math with four overloaded functions named calculate.

3.First function (int, int) → perform addition and print the sum.

4.Second function (double, double) → perform subtraction and print the difference.

5.Third function (long, long) → perform multiplication and print the product.

6.Fourth function (float, float) → perform division and print the quotient (check division by zero).

7.In main(), read four pairs of numbers, call each overloaded function, display results, then end the program.




## Program:
```

using namespace std;

class Math {
public:
    void sum1(int a, int b) {
        cout << "Sum of two Numbers=" << a + b << endl;
    }

    void sum2(int a, int b) {
        cout << "Difference of two Numbers=" << a - b << endl;
    }

    void sum3(int a, int b) {
        cout << "Product of two Numbers=" << a * b << endl;
    }

    void sum4(int a, int b) {
        cout << "Division of two Numbers=" << a / b;
    }
};

int main() {
    int a, b;
    cin >> a >> b;
    Math o;
    o.sum1(a, b);

    cin >> a >> b;
    o.sum2(a, b);

    cin >> a >> b;
    o.sum3(a, b);

    cin >> a >> b;
    o.sum4(a, b);

    return 0;
}
```

## Output:

<img width="1224" height="522" alt="image" src="https://github.com/user-attachments/assets/90fa0502-2cbb-4da9-a074-afa9555f0a49" />


## Result:
Hence the program is executed successfully.
