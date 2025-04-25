# 1A OVERVIEW & STRUCTURE

## PROGRAM STATEMENT:
Write a C++ program to display "Welcome to Technical Training" in first line and "at Saveetha Engineering College" in next line in the output device?

## ALGORITHM:
1. Start the program. 
2. Include necessary header files for input/output operations. 
3. Define the main function. 
4. Print "Welcome to Technical Training" with a newline. 
5. Print "at Saveetha Engineering College". 
6. End the program.

## PROGRAM:
```
#include <iostream>
using namespace std;
int main()
{
    cout<<"Welcome to Technical Training\nat Saveetha Engineering College";
    return 0;
}
```
 ## OUTPUT:
 ![image](https://github.com/user-attachments/assets/64f5030f-65de-4a72-9769-047e64228ea9)

 ## RESULT:
Thus, the C++ program to display "Welcome to Technical Training" in first line and "at Saveetha Engineering College" in next line into the output device is implemented successfully.



# 1B CLASS SCOPE AND ACCESSING CLASS MEMBERS & REFERENCE VARIABLES

## PROGRAM STATEMENT: 
Write a C++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class) 

## ALGORITHM:
1. Start the program and define a class Cylinder with private radius and height.
2. Create a method to take input for radius and height from the user.
3. Define a method inside the class to calculate volume using the formula πr²h.
4. In main(), create an object of the class and call the input and volume methods.
5. Display the volume and end the program.

## PROGRAM:
```
#include <iostream>
using namespace std;
class cyclinder
{
    public:
    float a,b;
    void dis()
    {
        cin>>a>>b;
        cout<<"The Volume of the Cyclinder is:"<<(3.14)*(a*a)*(b);
    }
};
int main()
{
    cyclinder c;
    c.dis();
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/168d0e17-d64d-4fa3-9543-eeee97ff6a4a)

## RESULT:
Thus,the C++ program to Calculate the volume of a cylinder using class methods(declare members as private & methods define inside the class) has been successfully created.


# 1C C++ CONSTRUCTORS AND DESTRUCTORS 

## PROGRAM STATEMENT
Write a C++ program to display "C++ constructors" using default constructors.

## ALGORITHM:
1. Start the program. 
2. Define a class Cont with a default constructor that prints "C++ constructors". 
3. In the main function, create an object c of class Cont, which calls the default constructor and displays the message. 
4. End the program.

## PROGRAM:
```
#include<iostream>
using namespace std;
class con
{
    public:
    con()
    {
        cout<<"C++ constructors";
    }
};
int main()
{
    con g;
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/e1cfe747-04ee-4c47-86f9-5a0e0b0caf15)

## RESULT:
Thus, the C++ program to display "C++ constructors" using a default constructor is 
created successfully.


# 1D C++ MEMBER FUNCTION

## PROGRAM STATEMENT:
Write a C++ program to calculate the sum of AP series using friend function.

## ALGORITHM:
1. Start and define a class AP with private members a, d, n.
2. Create a method to input a, d, and n.
3. Use a friend function to calculate the AP sum using the formula.
4. In main(), create an object and call the input and friend function.
5. Display the sum and end the program.

## PROGRAM:
```
#include<iostream>
using namespace std;
class zenko{
    public:
    int x,y,z;
    void data(){
        cin>>x>>y>>z;
    }
    friend int z(zenko m);
};
int z(zenko m){
    int u=(m.x+(m.y-1)*m.z);
    return u;
}
int main(){
    zenko s;
    s.data();
    cout<<"the sum is "<<z(s);
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/dd3a7990-6e77-450d-af9a-70c3a974c1d8)

## RESULT:
Thus,the C++ program to calculate the sum of AP series using friend function has been created successfully.






