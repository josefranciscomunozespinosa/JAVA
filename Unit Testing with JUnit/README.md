# Unit Testing with JUnit

### Exercise 1

Run all tests for the [CalculatorTDDTest.java](src/calculator/tdd/CalculatorTDDTest.java)

- Why don't they work?
- Implement the CalculatorTDD methods so that the test can pass.
- Run the unit test for the CalculatorTDDTest class again and verify that the tests pass.

### Exercise 2

#### Part 1: Writing Unit Tests

1. Open the Drive package and explore the classes and what they do.

2. Open the *DriversManagerTest* class and implement unit test for the following scenarios:
* Verify a Passenger is added correctly
* Verify a Driver is added correctly

3. Implement the following unit test in the *DriversManagerTest* class:

     ```java
        @Test
        public void startTripTest(){
    
        }
    
        @Test
        public void endTripTest(){
    
        }
     ```
#### Part 2: Test Driven Development
1. Implement the following unit test so it fails:
     ```java
        @Test
        public void nextAvailableDriverTest(){
    
        }
     ```
#### Part 3: Writing Tests for Edge Cases
1. Think of 2 edge cases that have not been tested. Write a unit test for each case. 

#### Challenge Yourself
1. As you can see this algorithm is not very fair. It does not consider distance so the drivers
will always get paid the same fee. Modify the code so it considers distance too.
 
