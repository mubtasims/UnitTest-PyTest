# UnitTest-PyTest

Testing in the software development cycle is a crucial step, not only for further development and production ready codes but also to implement a clean layout overall. An application, no matter how small or large it is, needs some form of testing in order to execute the commands properly and spits out the result that is expected. In this very particular repo, we will understand the very basics of testing, especially in Python.

Python is a versatile language that is used in multiple different industries starting from space technologies to machine learning, all the way down to YouTube. With such a versatile language to work with, testing Python can be seen as a very daunting task but with proper procedures and a structured plan, testing can be implemented without much complications. Software developers can create simple tests for applications in a few easy steps and then build on it from there.

The basics of Python testing can be covered through testing procedures known as Unit Testing and PyTest.

A unit test is a smaller test, one that checks that a single component of the program and see if that operates in the right way.It helps one to isolate what is broken in the application and fix it faster. It has been built into the Python standard library for a while and it contains both a testing framework and a test runner and it also has some important requirements for writing and executing tests.

unittest requires that:

You put your tests into classes as methods
You use a series of special assertion methods in the unittest.TestCase class instead of the built-in assert statement



pytest supports execution of unittest test cases. The real advantage of pytest comes by writing pytest test cases. pytest test cases are a series of functions in a Python file starting with the name test_.

Before you dive into writing tests, you’ll want to first make a couple of decisions:

What do you want to test?
Are you writing a unit test or an integration test?
Then the structure of a test should loosely follow this workflow:

Create your inputs
Execute the code being tested, capturing the output
Compare the output with an expected result





We create a set of fucntions that will be usig as an application and will be writing test cases against those functions. Create files and write functions 
