# C++ Reference
This reference is supposed to give an overview to the syntax and features of the C++ programming language.
## First program
Create a file called 'main.cc' including the following content
```C++
#include <iostream>

int main() {
	std::cout << "Hello, World!" << std::endl;
	return 0;
}
```
Using the g++ compiler, the file can be compiled by using
```
g++ main.cc -o main
```
The executable 'main' is created which can be executed via
```
./main
```
printing the message
```
Hello, World!
```
on the screen.
