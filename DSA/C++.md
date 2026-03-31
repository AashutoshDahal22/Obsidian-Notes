#DSA 

![[Pasted image 20260330070219.png]]
#### File extension
- In C++ the primary or the main file of the program is saved as ```main.cpp``` or the name of the program such as ``program.cpp`` .
- ``cpp`` is the file extension used by **C++** , other extensions such as `.cc` or ``.cxx`` can also be used.

#### Compilation
- To compile the C++ code we need a C++ compiler which sequentially goes through the each source code(``cpp``) file in the program and deos two important task
- **First** the compiler checks the C++ code to make sure that the source code is syntaxically correct and until it is correct it stops the compilation process
- **Second** is that the compiler translates the C++ code into machine level code into an *intermediate* file called an **object file**.
- The object file also contains other data that is required or useful in subsequent steps (including data needed by the linker in step 5, and for debugging in step 7).
- Object files are typically named `name.o` or `name.obj` where the name is the file that the `cpp` was produced from.

	![[Pasted image 20260330070845.png]]

#### Linker
- LInker is the program that runs after the compiler which bascially connects all the object fiels and checks if there is any *DI(Dependency Issues)* 
- Depending upon the way the project is set, the **linker** can generate *executable* or *library* files.

	![[Pasted image 20260330071240.png]]

#### Libraries
- C++ comes with an extensive library called the **C++ standard library** or Standard Library for short which has many functions and keywords which we can use through out the program.
- We can also link our C++ project into **third party libraries** which can provide even richer set of functions we can apply but depending upon the library and the implementation the performance and security can vary.

#### Building
- Because there are multiple steps involved, the term **building** is often used to refer to the full process of converting source code files into an executable that can be run. A specific executable produced as the result of building is sometimes called a **build**.

