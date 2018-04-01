# EmbeddedProject8

This is a supplmentary project to the sysprogs VisualGDB support message for Feedback for VisualGDB 5.4 Preview 1 with support for Advanced ESP-ID

https://sysprogs.com/w/forums/topic/feedback-for-visualgdb-5-4-preview-1-with-support-for-advanced-esp-idf/

showing that includes are not working properly:

I've created a couple of include directories and files. My sample sample includes are located in my Documents directory (C:\Users\gojimmypi\Documents\TestLibrary) like this:
![alt text](https://github.com/gojimmypi/EmbeddedProject8/blob/master/images/Lib1Lib2files.PNG)

This sample include library can be downloaded here:

https://github.com/gojimmypi/TestLibrary 

Here's a basic C++ Console Applipcation with include directories working intuitively and properly:
![alt text](https://github.com/gojimmypi/EmbeddedProject8/blob/master/images/ConsoleApp.PNG)

Here's the result in VisualGDB:
![alt text](https://github.com/gojimmypi/EmbeddedProject8/blob/master/images/Lib1Lib2.PNG)

Note how the libraries are not found by the compiler.

Here's another view of the code:
![alt text](EmbeddedProject8/images/VisualGDB-LibNotFound.PNG)