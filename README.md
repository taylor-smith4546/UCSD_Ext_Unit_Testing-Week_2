# UCSD Extension: Unit Testing: Supporting Modern Software Development Methods

## Videos: 

[Lecture 2: Unit Testing Guidelines and Techniques](URL link here)

## Assignment/Classwork:

Quiz #2 (Blackboard)

Exercise 1:  

JUnit Run (Not Graded)

This exercise will help you get up and running with JUnit.
1. Create a new empty project using the build tool of your choice (Maven, Gradle). Add required
JUnit dependencies. Create a simple test class with a single test method containing some assertions.
2. Compile and run the test using your build tool.
3. Compile and run the test using your IDE.
4. Browse the test results.

Exercise 2:

Learn About AssertJ (Not Graded)
 
The simplest way to learn about assertions provided by AssertJ is the following. Open your IDE and
create a new test class. Then create a test method like this:

## Example:

```java
@Test
void learnAssertJ() {
 double var = 2.5;
 assertThat(var).
}
```
If you set the cursor after the hanging dot and ask your IDE for autocompletion then it will provide
you with the list of available methods. All you have to do now is to change the type of variable var to
String, BigDecimal or List<Object> and see what assertions are available.

Exercise 3:

We have a very simple calculator class. All it does is add two numbers together. 
When testing this code, we would like to make sure that the calculation is correct.

o Construct an instance of the Calculator class
o Call the add() method with some parameters and store the result
o Check the results by calling the assertEquals() method, comparing the expected and actual value
o Write an additional test which calls the AssertNotEquals method


 
Exercise 4: 

Master Your IDE (Not Graded)

Make sure you spend some time learning about the support your IDE can give you in terms of
effective unit testing. In particular, there are two features you should get accustomed with.

## Topics Covered: 

o	What is a Unit Test?

o	Interactions in unit tests

o	Writing unit tests
