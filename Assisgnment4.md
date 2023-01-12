**Questions**

1. explain the architecture of nodejs
2. explain the feature of nodejs like non-blocking, synchronous, single threaded.
3. create a array and object in javascript and print it.
4. Nowadays how data is transferred between server and client?(explain about json)
5. write program to show how to append, pop and sort elements in array in javascript.
6. why should we use let in place of var in our javascript programs?
7. explain about all the primitive data types in javascript.


**Solutions**
1.  Node js architecture is based on “Single Threaded Event Loop” architecture to handle multiple concurrent incoming clients requests.
2. `Non blocking` input and output operations allows single process to serve multiple requests at the same time.
like wise, ``Synchronous`` executes a batch of code line by line and each time it waits for a function to finish to get started with another one. 
Node js basically operates on a``Single threaded`` even loop. 
3. 
``const arr = new Array();``<br>
``arr[4] = [2, 3 , 4, 5];``<br>
``console.log(arr);``
4.  Between server and client data is transferred using TCP/IP that provides mechanism for the transfer of data between two applications.
5. 
6. `let` is used in place of `var` bcs it can declared in a limited scope of a variable of function, but `var` is declared globally which is not that helpful in certain cases.
7. The Primitive Data types in JavaScript include Number, String, Boolean, Undefined, Null and Symbol.
<br>
The Non-Primitive data type has only the Object.