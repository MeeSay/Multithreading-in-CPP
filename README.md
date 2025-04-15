# Multithreading-in-CPP
Thread is the thread class that represents a single thread in C++. To start a thread we simply need to create a new thread object and pass the executing code to be called (i.e, a callable object) into the constructor of the object. Once the object is created a new thread is launched which will execute the code specified in callable. The five callables:
- A Function Pointer
- A Lambda Expression
- A Function Object
- Non-Static Member Function
- Static Member Function
