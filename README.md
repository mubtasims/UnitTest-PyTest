# UnitTest & PyTest

Testing in the software development cycle is a crucial step, not only for further development and production ready codes but also to implement a clean layout overall. An application, no matter how small or large it is, needs some form of testing in order to execute the commands properly and spits out the result that is expected. In this very particular repo, we will understand the very basics of testing, especially in Python.

Writing tests can be time consuming for many developers and some questions needs to be asked in order to write effective tests:

1.) What needs to be tested?
2.) What specific output is expected after the test?

This questions would lead the developer to create a mental strategy and a clear goal to write a functional test. Following right after that, the developer should think about how to :

1.) Creating the inputs for the test.
2.) Execute the code being tested, and observing the test result.
3.) Compare the the test result with the expected result.

Python is a versatile language that is used in multiple different industries starting from space technologies to machine learning, all the way down to YouTube. With such a versatile language to work with, testing Python can be seen as a very daunting task but with proper procedures and a structured plan, testing can be implemented without much complications. Software developers can create simple tests for applications in a few easy steps and then build on it from there.

The basics of Python testing can be covered through testing procedures known as Unit Testing and PyTest.

A unit test is a smaller test, one that checks that a single component of the program and see if that operates in the right way.It helps one to isolate what is broken in the application and fix it faster. It has been built into the Python standard library for a while and it contains both a testing framework and a test runner and it also has some important requirements for writing and executing tests.

Unittest requires that:

1.) The tests must be input into classes as methods.
2.) A collection of unique assertion methods must be used.

Then we have Pytest, which is also a testing procedure for Python codes. It is a framework that is also used in the industry, if anything more preferred by the Python community for testing purposes on databases and mainly APIs.

Pytest also supports execution of unittest test cases and one of the exciting advantage of pytest comes by writing pytest test cases. These test cases are a collection of functions in a Python file starting with the name test_. that can be created as a separate file and run in order to excute the test.
