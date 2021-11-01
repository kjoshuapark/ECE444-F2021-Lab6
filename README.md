# ECE444-F2021-Lab6

Kieun Joshua Park

This repo is a walkthrough of the example found in https://github.com/mjhea0/flaskr-tdd.

## Pros and Cons of TDD

### Pros

A practice of TDD is that developers only write new code to fix issues that arise from knowing that a test has failed. A practice like this really encourages conciseness and so theoretically you will only have code that you truly need to fulfill the particular and necessary features. 
When aiming to develop with the basis to unit test everything, the code itself also becomes more decoupled. The result is that the application becomes easier to maintain.

### Cons

Writing and maintaining tests can be time consuming. Maintaining the test code in particular can be tough when the particular needs for an application change or when you need to test for new results. Writing unit tests can also be especially difficult because it is not easy to isolate functionality of a whole program. It may be necessary to initialize certain values just to have particular objects to use for testing and this problem is only made worse in very large programs.
