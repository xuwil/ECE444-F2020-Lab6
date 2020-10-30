# ECE444-F2020-Lab6
Author: Yudong (Will) Xu

This repo is a clone of https://github.com/mjhea0/flaskr-tdd.git





## What are the pros and cons of TDD?
Test driven development is an iterative development cycle that emphasizes writing tests before writing actual features/functions, it follows the cycle of: 

Write a test → ensure the test fails → write code → ensure the test passes → refactor code → write a new test.

Some of the biggest pros of using TDD:

TDD will make bugs easier to detect during development, since developers always need to ensure that all the tests pass. TDD means that code is written one module at a time, this means that the project will have good architecture since code will be modularized. TDD will help make the code easier to understand as the tests can serve as a documentation, what each part of the code is supposed to do is clear. TDD will allow easier refactoring and maintenance, by making sure that the tests still pass after refactoring, developers can know that the code isn’t behaving in an unexpected way.

Some of the biggest cons of using TDD:

TDD is very time consuming, because the tests themselves also need to be maintained and updated. Developers could set their goals to only make the tests pass, without thinking too far ahead, which could result in major refactoring further into the development process. It is difficult to write good tests, sometimes people focus only on the code coverage of the tests without caring about the quality of the tests themselves. From my personal experience, I found it difficult to come up with good tests up front when I still have no idea of what the functions will look like, which resulted in me changing the tests a lot as development progressed, resulting in a lot of extra work.

Sources:

https://devqa.io/pros-cons-test-driven-development/ 

https://leantesting.com/test-driven-development/ 

https://realpython.com/python-testing

