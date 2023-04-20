## <pre>             IT 314 - Software Engineering </pre> 
### Lab 8 : Unit Testing with JUnit
### Student Name : Darpan radadiya
### Student ID: 202001159

#### 1. Create a new Eclipse project, and within the project create a package.
![image](https://user-images.githubusercontent.com/99037272/233044268-51e5a80a-d3fc-469b-9dda-a25ce547f037.png)


#### 2. Create a class for a Boa. Here’s the code you can use (you may copy/paste):

![image](https://user-images.githubusercontent.com/99037272/233044075-a75ec6df-bfa7-4004-a63f-bb3f1ca1cebf.png)


#### 3. Follow the instructions in the JUnit tutorial in the section “Creating a JUnit Test Case in  Eclipse”. You’ll be creating a test case for the class Boa. When you’re asked to select 

 test method stubs, select both isHealthy() and fitsInCage(int).

![image](https://user-images.githubusercontent.com/99037272/233044770-f630a074-049b-4b76-9dcc-75c3f204fbf8.png)


#### 4. Now it’s time to write some unit tests. Notice that the BoaTest class that JUnit created for you contains stubs for several methods. The first stub (for the method setUp()) is annotated with @Before. The @Before annotation denotes that the method setUp() will be run prior to the execution of each test method. setUp() is typically used to initialize data needed by each test. Modify the setUp() method so that it creates a couple of Boa objects.

![image](https://user-images.githubusercontent.com/99037272/233045022-f5f18723-973b-4f76-b3d2-6d9a3ebde675.png)


#### 5. Create Junit test case

for isHealthy() method 

![image](https://user-images.githubusercontent.com/99037272/233046003-920d509f-3e5d-48e2-86e6-6aa597c1ddd8.png)

for fitsInCage() method 

![image](https://user-images.githubusercontent.com/99037272/233046143-a092800b-8cbc-4dee-9c83-906970451925.png)


#### 6. Run Test Case

![image](https://user-images.githubusercontent.com/99037272/233046375-53015433-b418-4995-8c27-cf4fca66024c.png)


#### 7.Add a new method to the Boa class, lengthInInches(). And Add a new test case to the BoaTest class that tests the lengthInInches() method.

code

![image](https://user-images.githubusercontent.com/99037272/233047130-25c9fad3-6e9a-47ff-99b8-16d0b4763c82.png)

TestCase

![image](https://user-images.githubusercontent.com/99037272/233047234-3838cc91-cfa4-4656-95b9-60b4b7ee2e65.png)

Output

![image](https://user-images.githubusercontent.com/99037272/233048218-2914fa06-ea9c-4b1c-b02c-b9c45498fcc6.png)
