**Content:**
 <a id="x"></a>

 - [Introduction](#1)
 - [Testing and debugging](#2)
 - [Regression and retesting](#3)
 - [Testing Principle](#4)
 - [Entry Criteria and Exit Criteria](#5)
 - [Comparing test activities:](#6)
 - -[Test activities of analysis and design](#7)
 - -[Test activities of analysis, design and implementation](#8)
 - -[Test activities of implementation and execution](#9)



# Intro
 <a id="1"></a>
It is true that people are fallible and can make mistakes. 
```
Effect of an:

├── Error /mistake/Blunder
    ├── Defect / Bug/Fault/ Flaw
        ├── Failure /Malfunction/Breakdown


```
There are other reason why system fail and can affect the operation of hardware and firmware and lead to system failure. Then can lead to:
- loss of money
- loss of time
- loss of business reputation
- injury
- death

<br>

[Back to content](#x)

# Testing and debugging
<a id="2"></a>

|testing |debugging|
|:----|:----|
|Identifies failures| Investigates the cause of a fault (root cause)|
|Confirms whether a failure has been fixed| Fixes software if necessary|
| |Checks the defect has been fixed|
| |Steps through program code|
|-- |-- |
| by the tester |by the developer |

<br>

|TRUE|FALSE|
|:----|:----|
|Failures can be caused by environmental conditions such as radiation|A defect is produced as a result of system failure|
|Defects, bugs and faults are the same thing|Failures can cause bugs|
| |Faults always cause system failures|

<br>

[Back to content](#x)

# Regression and retesting
<a id="3"></a>

|REGRESSION|RETESTING|
|:----|:----|
|Regression testing is checking that there are no additional problems in previously tested software. |retesting is demonstrating that the reported defect has been fixed.|

[Back to content](#x)

# Testing Principles
 <a id="4"></a>

|Testing Principles|Description|
|:----|:----|
|Testing shows the presence of defects|Testing can show that defects are present, but it cannot prove that there are no defects. Even with thorough testing, it is possible that some defects may remain undetected.|
|Absence of Error Fallacy|Finding and fixing defects does not necessarily mean that the system is ready for release or will meet the needs of its users.Just because a system does not have any known defects does not mean that it is fit for its intended purpose.It is important to focus on fulfilling the requirements and meeting the needs of the users, rather than just finding and fixing defects.|
|Exhaustive testing is impossible|It is not possible to test all possible combinations of inputs and preconditions due to the large number of possibilities.Therefore, it is not possible to find all defects in a system through testing.|

[Back to content](#x)

# Entry Criteria and Exit Criteria
 <a id="5"></a>


|Entry Criteria|Exit Criteria|
|:----|:----|
|Pre-requisite condition for testing|Post-testing condition|
|Defines when to start testing|Indicates when to stop testing|
|Deals with basic scenarios of testing|Deals with conditions outside basic scopes|
|Points out what should be tested and when to start testing|Gives warning about what problems still exist in an application even after completing all tests|

[Back to content](#x)

# Comparing test activities:
 <a id="6"></a>

 ## Test activities of analysis and design
 <a id="7"></a>
 |Test activities|ANALYSIS|DESIGN|Implementation|
|:----|:----|:----|:----|
|Creating test suites| | |x|
|Developing test procedures,| | |x|
|Service virtualization| | |x|
|Verifying that everything needed has been set up correctly| | |x|
|Identifying necessary test data to support test cases| |x| |
|Building test harnesses and simulators| | |x|
|Designing the test environment| |x| |
|Verifying that everything needed has been set up correctly| | |x|
|Evaluating the test basis and test items to identify defects of various types|x| | |
|Capturing bi-directional traceability between the test basis, test conditions, and test cases| |x| |
|Capturing bi-directional traceability between each element of the test basis and the associated test conditions|x| | |


[Back to content](#x)

## Test activities of analysis, design and implementation
 <a id="8"></a>
 
[Back to content](#x)

## Test activities of implementation and execution
 <a id="9"></a>

 [Back to content](#x)

