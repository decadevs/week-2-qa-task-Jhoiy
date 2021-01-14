# WEEK TWO TASK ANSWERS
1.	Test coverage is a metric used to determine/check how thorough our testing is. It looks at our test cases and determines if they actually cover every area of our application codes/software.
They are of different types namely:
* Function Coverage —  This type checks to see the fraction of functions that have been used. 
* Statement Coverage — It looks at the fraction of code statements  that have been tested. It checks whether each line of code has been executed
* Branch Coverage(also called Path Coverage) — It checks whether or not  both true and false branch paths have been exercised. 
Test coverage is very important in software testing because:
* It checks to ensure that every possible test case/ test scenario has been exhausted so as to prevent future bugs and if not, it enables us create more test cases.
* It handles any error that might arise.
* It locates gaps in the software requirements.

2.	Testing technique refers to the procedures taken to ensure that we have a 100% test case coverage while types of testing refer to the different ways testing is done.

3.	Types of testing
* Functional testing
* Non-Functional testing

***Functional testing*** – It is a type of software testing that checks to see whether or not the system software aligns with the functional requirements/specifications. 
	Types of functional testing:
* Unit Testing
* Integration Testing
* System Testing
* Interface Testing
* Regression Testing
* User Acceptance Testing

*Unit testing* –This type of testing is done of single modules to check whether or not it has been developed properly. The type of test coverage used is function coverage.
*Integration testing* – Here, individual modules are combined together and are tested as a group to see the interaction between them
There are different approaches to carrying out integration testing, namely:
* Big bang - It is an approach to integration testing where all or most of the units are combined together and tested at one goal. This happens when the testing team receives the entire software in a bundle.
* Top Down - This is an approach to integration testing where top-level units are tested first and lower-level-units are tested step by step downward.
* Bottom Up - This is an approach to integration testing where bottom level units are tested first and upper-level-units are tested step by step after that.
* Sandwich or Hybrid - This is an approach to integration testing which is a combination of top-down and bottom-up approaches.

*System testing* – This type of testing focuses on the behavior of the system as a whole. It checks how a user will use the system. We check whether the system meets the goal.

*Interface testing* - It verifies that communication between systems is done correctly. There are three phases of interface testing in an interface life cycle, namely: Validation, Maintenance and Configuration.

*Regression testing* – This type of testing is done to check if any change in the software caused adverse side effects. It is of a repetitive form, i.e. it is carried out from time to time, although, automations are done to iterate the process.

*User Acceptance testing* – This type of testing does not focus on finding/locating bugs/defects but how acceptable the users find the software. i.e it answers the question, will the end user accept the software? And would they be able to use it?

***Non-functional testing*** – It is a type of Software testing that checks non-functional aspects (performance, usability, reliability, etc) of a software application. It is designed to test the readiness of a system as per nonfunctional parameters which are never addressed by functional testing.
Types of Non-functional testing
1. Documentation Testing
2. Installation Testing
3. Performance Testing 
* Load Testing
* Stress Testing
* Endurance Testing
* Spike Testing
4. Reliability Testing
5. Security Testing.

*Documentation testing*- It helps to estimate testing effort required and test coverage. It includes- test plan, test cases and requirements section.
*Installation Testing*- It is a type of quality assurance work in the software industry that converges on what customers will need to do to install and setup the new software successfully. The testing process may involve full, partial or upgrades install or uninstall processes.
*Performance testing*
* Load testing — It is conducted to evaluate the behavior of a system at increasing workload.
* stress testing — It is conducted to evaluate the behavior of a system at or beyond the limits of its anticipated workload.
* Endurance testing —   It is conducted to evaluate the behavior of a system when a significant workload is given continuously.
*Reliability testing*- It assures that the product is fault free and is reliable for its intended purpose. It is about exercising an application so that failures are discovered before the system is deployed.

*Security Testing*
There are two main areas to be considered in security testing namely:
* Network security — This involves looking for vulnerabilities in the network infrastructure.
* Client security — It ensures that the client cannot be manipulated and the server code and its technologies are robust enough to fend off any intrusion.
 
4.	Solution link https://drive.google.com/drive/folders/18asa9QLAInemMkjX2SHgO83KWiLCr8r7?usp=sharing
5.	Testing technique is a method which is usually applied to a system/component to evaluate it with the intent of knowing whether or not the given requirements are satisfied.
Types of testing techniques
* Error guessing
* Equivalence partitioning
* Boundary value analysis
* Decision table techniques
* State transition technique

*Error guessing*: In error guessing, the test engine will try to guess the error by entering negative values. No rules are followed, it depends on analytical thinking of individual test engineers. It is usually based on intuition and experience of the test engineers involved. 
Examples: 
A program is meant to receive an array of numbers as its input, error guessing in this case can be, what if it doesn’t receive numbers as its values or what if it receives nothing at all?
* It is expected that in a sign-up page for a banking app, the user is to enter his full name which is meant to consist of alphabets only. Error guessing looks at a possibility where figures(numbers) or even extra non-alphabetical characters are entered instead or combined with alphabets.

*Equivalence partitioning*: It is also called equivalence class partitioning; it is a testing technique that divides the input data of a software unit into partitions of equivalent data from which test cases can be derived. It is usually partitioning between valid and invalid values. 
 Examples
* if the requirement says that your input can accept 1 - 500 digits, you can divide it into classes, like -100 - 0, 1 - 100, 101 - 200, 201 - 300, 301 - 400, 401 - 500, 501 - 600. Once you take any digit from any of the classes and it gets accepted, it means that particular class has passed, other classes are then considered. It is not necessary to pick from all class, the main focus is to pick from a valid and invalid class.

* Another example goes this way; An input field for account number requires only number values with length of 10. Partitions can be made into namely: A test case in which a customer enters number values but of length less than 10, say of length 9, a test case where a customer enters numbers of length 10, also, a test case where a customer enters a  wrong expected value with length of 10, and a test case where a customer enters a  wrong expected value with length less than or more than 10.
*Boundary value analysis*: It is testing the boundaries between partitions. If you have a range of values say A-B, you’d have to run your test on A, A+1, A-1, B, B+1, B-1.
Example:
* If the requirement says that your input can accept 1 - 500 digits, you can divide it into classes, like -100 - 0, 1 - 100, 101 - 200, 201 - 300, 301 - 400, 401 - 500, 501 - 600. You then take the boundary digits from each of the classes, add one and subtract one from each and check if it gets satisfies the condition given.

*Decision table technique*:  It is a combination of techniques, conditions. 
We check for multiple conditions combinations and we rule criteria. Here the conditions are taken as an input and actions are taken as an output. The decision-based technique will be freely based on conditions, combinations and rule criteria.
	In Decision table technique, No. of test cases = No.  of rules = 2 ^ No. of conditions.
Example: 
* A student is allowed into the school if he/she has paid his/her school fees, is a member of the school and attends all his/her classes. So we have: 
Conditions = 
* Student paid fees,
* Student is a member of the school,
* Student attends all his/her classes.
No. of rules = 2^3 = 8, we have 8 rules of which we use our truth table to combine them together.


*State transition technique*: We test for the different state of a machine, the different screen of a machine or different transition state of any machine.
Having a diagram is very important so as not to miss out on some test cases.



Example:
* A case where we want to test an ATM system function to see what happens if the user enters the invalid password three times and if the account will be locked.


6.	Testing techniques that can be used are:

* *Error guessing*- Here we can assume that the user enters an email with the wrong format. 
* *Equivalence partitioning* – Here, we arrange the number of characters into classes. We are told that the email characters cannot be less that 15 characters and also not greater than 200 characters. 
So, we can have classes: 0-14, 15-200, 201-500, picking  from first class results to a false statement and so all of class 1 are falsy. Same goes for class 3 but class 2 returns truthy. Therefore all of class 2 holds and so any number of characters used in class 2 is valid.
* *Boundary value analysis* – We are told that password should contain at least 8 characters and at most 20 characters. So, we first create a partition say 8 - 20 and test between the boundaries which are (8 – 1) = 7, 8, (8 + 1) = 9 & (20 – 1) = 19, 20, and (20 + 1) = 21. Hence, 7: Invalid, 8: Valid, 9: Valid, 19: Valid, 20: Valid, 21: Invalid.
* *Decision Table Technique* – Here, we design a decision table with the three conditions given namely: Password must contain at least one character, Password must contain at least one number and Password must contain at least one capital letter.
So we have 3 conditions and 2 ^ 3 rules = 8 rules = 8 no of possible test cases.

https://drive.google.com/drive/folders/1KQkoDGnaDPZqiePhxmVGu6QwxzOR0RsU?usp=sharing

* //
* Here, we use state transitioning technique. Once a user puts in his/her email and password, if valid he/she is logged in, if not a second trial is given and if valid, he/she is logged in. If not valid, a third trial is given and if the login details is valid access is given, else the user is denied access.
* Here, we use error guessing. In this case we guess that the user is not registered.
* TypeError.

7. https://drive.google.com/drive/folders/1F3dykJbwF062i-gP18CE83ZgBrBlmU2I?usp=sharing

8. https://drive.google.com/drive/folders/1UEyuNozRBW4bF8N25J6FW366kE0YEdZd?usp=sharing

9. https://drive.google.com/drive/folders/1ZLqIgd35jBeiL-AOfUNER4TxU8iSGiyj?usp=sharing

10. I would apply state transition technique.
https://drive.google.com/drive/folders/1JDLEYlNrg2JwH3WO8Fuo3-nol12nOgsU?usp=sharing







