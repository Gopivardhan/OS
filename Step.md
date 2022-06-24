<h1 align ='center'>Steps to execute a c or c++ file in ubuntu</h1>
<div>
Terminal
<ol>
 <li> Open terminal. </li>
 
  <li> Type command to install gcc or g++ complier:
    ```
    
      $ sudo apt-get install build-essentia
    
    This will install the necessary C/C++ development libraries for your Ubuntu to create
      C/C++ programs.  
      To check gcc version type this command:
      $ gcc –version or gcc –v </li>
 
  <li> Now go to that folder where you will create C/C++ programs. I am creating my
      programs in Documents directory. Type these commands:  
    ```
      $ cd Documents/
      $ sudo mkdir programs
      $ cd programs/  
    ```
  </li>
 
  <li> Open a file using any editor.  
      $ sudo gedit first.c (for C programs)
      $ sudo gedit hello.cpp (for C++ prgrams) </li>
 <li> Save the file and exit. </li>
 
  <li> Compile the program using any of the following command:
      Compiling C++ program.
      $ sudo g++ hello.cpp (or)
      $ sudo g++ -o hello hello.cpp </li>
      [Note: Make sure you are in the same directory where you have created your program
      before compiling it.]
  
 <li> To run this program type this command:
      For running C++ program
      $ ./a.out (If you compiled using first command)
      Or
      $ ./hello (If you compiled using second command)
      It will show output on the terminal.</li>
  </ol>
</div>
