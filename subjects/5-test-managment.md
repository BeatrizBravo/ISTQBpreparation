
**Content:**
<a id="x"></a>

- [Independent Testing](#1)
- [Benefits of Test Independence](#2)
- [Typical test manager tasks and tester tasks](#3)
- [Test Strategy and Test Approach](#4)
- [Entry Criteria and Exit Criteria ](#5)
- [Test executuion Schedule ](#6)
- [Product vs Project Risk  ](#7)
- [Questions  ](#100)


|Independent Testing| | | | |
|:----|:----|:----|:----|:----|
|Low Level of Independence| | | |High Level of Independence|
|No independent testers |Independent developers or testers **within** development team|Independent Tester|Independent Tester|• Independent Tester|
|• Developers testing their own code| |• Same organization|• Same organization|• Different Organization|
| | |• Same Manager|• Different Manager| |


<a id="2"></a>

|Benefits of Test Independence|Drawbacks of Test Independence|
|:----|:----|
|Testers can provide an OBJECTIVE and UNBIASED view of the software quality and risks|Testers may be ISOLATED from the development team, leading to a lack of collaboration, delays in providing feedback, or an adversarial relationship|
|Testers can apply different SKILLS, EXPERIENCE, and PERSPECTIVES than the developers, leading to more effective and efficient testing|Testers may have LIMITED access to project information, resources, or support from the development team, leading to difficulties in understanding the requirements, design, or implementation|
|Testers can avoid the ASSUMPTIONS, OVERSIGHTS, or BLIND SPOTS that the developers may have, leading to more thorough and diverse testing|Testers may have HIGHER costs or overheads associated with test independence, such as hiring external testers, managing contracts, or transferring knowledge|


<a id="3"></a>

| Typical test manager tasks and tester tasks                                                                                                                                                                 | |
|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----|
|                                                                                                                                                                                                             | |
| Test Manager Tasks                                                                                                                                                                                          |Tester Tasks|
| Define the TEST STRATEGY and TEST APPROACH for the project based on the organizational test strategy and the project context                                                                                |Contribute to the TEST PLAN by reviewing and writing test plans and submitting plan documents for final review to the test manager|
| Manage and coordinate the TEST TEAM and their activities, including assigning tasks, monitoring progress, providing feedback, resolving issues and conflicts, and ensuring adequate skills and competencies |Analyze, review and assess USER REQUIREMENTS, stories, specifications, and acceptance criteria|
| Manage the TEST RESOURCES, such as test environments, test data, test tools, etc., and ensure their availability, suitability, security, and maintenance                                                    |Design, prioritize, implement and execute TEST CASES and TEST PROCEDURES based on the test basis and test objectives|
| Manage the TEST STAKEHOLDERS, such as customers, users, developers, sponsors, etc., and ensure effective communication, collaboration, reporting, and expectation management                                |Record and evaluate TEST RESULTS and report any defects or deviations from expected behavior|
| Manage the TEST PROCESS, such as planning, monitoring, controlling, evaluating, reporting, and improving the test activities and deliverables                                                               |Perform REGRESSION TESTING and RETESTING as needed after defect fixes or changes|
| Manage the TEST RISKS and issues that may affect the test objectives, scope, schedule, quality, or resources                                                                                                |Support other test levels or types, such as integration testing, system testing, acceptance testing, performance testing, etc., as needed|

[Back to content](#x)

<a id="4"></a>

| Test Strategy                                                                                       |Test Approach|
|:----------------------------------------------------------------------------------------------------|:----|
| **generalized** description of the test process                                                     |**tailors** the test strategy for a particular project or release. Help to select test techniques, levels and types and define test entry/exit criteria|
| types:                                                                                              |about the context and factors:|
| Analytical (some factor. Example Risk or requirement)                                               |Risk|
| Model-base (model/requirement of the product functinal or non-funct.)                               |safety|
| Methodical (use predefined set of test/conditions Example taxonomy                                  |available resouces and skills|
| Process compliant (rules/standars)                                                                  |technology|
| Directed (advice/instructins stakeholdes, business domain, etc)                                     |nature of the system|
| Regression-averse (reuse existing testware)                                                         |test objetives|
| reactive (event occurring during teste execution -> response -->knowloge gained -> explorative testing |regulation, etc.|


[Back to content](#x)

<a id="5"></a>

|Entry Criteria| Exit Criteria                                                                                                                                                                                                                                                                                                 |
|:----|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|PREREQUISITES/precondition that must be met **before test activities** can begin, such as **availability** of test basis, test plan, test environment, test data, test tools, other necessary resources.| CONDITIONS that **must be met** before  test level or a set of test is declare completed, such as achievement of test objectives, planned tests have been executed, defined level of coverage (#unresolved defect is within agreed limit/estimated remaining defects is sufficiently low, quality, or budget) |
|Entry criteria help to ensure that testing is PLANNED, PREPARED, and READY to start, and that the test items are stable and testable| Exit criteria help to ensure that testing is COMPLETED, EVALUATED, and REPORTED, and that the test items meet the stakeholder expectations and requirements                                                                                                                                                   |
|Agile: Definition of ready| Agile: definition of done                                                                                                                                                                                                                                                                                     |
Intro to [entry/exit criteria](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/1-Fundamental.md#5)


[Back to content](#x)

<a id="6"></a>

## Test executuion Schedule
Diference [Test script/case](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/4-test-disign-techniques.md#4)

|Factors|
|:------|
|prioritization|
|dependencies|
|confirmataion tests|
|regression test|
|sequence for executing the tests|

If a higer priority test case is dependent on lower priority test case, the lower priority test case **must** be executed **first**

[Back to content](#x)

<a id="7"></a>
 
### Risk
a factor taht could result in future negative consquences, usually expressed as impact and likelihud.

#### Types:

#### Level of Risks:
Level of Risks = probability of the risk ocurring X impact if it did happen (manage by the manager)

| Product Risk   | Project Risk                                                                                                          |
|:---------------|:----------------------------------------------------------------------------------------------------------------------|
| A risk that affects the QUALITY or RELIABILITY of the software product. | A risk that affects the COST, SCHEDULE, or RESOURCES of the software project.                                         |                                        |
| Examples: FUNCTIONALITY, PERFORMANCE, SECURITY, USABILITY, or COMPATIBILITY issues. | Examples: BUDGET, SCOPE, STAFFING, TECHNOLOGY, or STAKEHOLDER issues.                                                 |
| The impact of product risk is mainly on the CUSTOMERS or END-USERS of the software product. | The impact of project risk is mainly on the DEVELOPERS or MANAGERS of the software project.                           |
| Product risk can be identified and analyzed by using techniques such as REQUIREMENTS REVIEW, RISK-BASED TESTING, or EXPLORATORY TESTING. | Project risk can be identified and analyzed by using techniques such as RISK MANAGEMENT PLAN, RISK REGISTER o MATRIX. |

[Back to content](#x)

<a id="100"></a>

# Questions

|Questions| Answers                        | N. Page in the book |
|:----|:-------------------------------|:--------------------|
|What are the two types of risk that have to be considered in testing?| Product Risk  and Project Risk | 162                 |
|Compare and contrast these 2 risk types.| [here](https://github.com/BeatrizBravo/ISTQBpreparation/blob/main/subjects/5-test-managment.md#risk)                       |                     |
|How early in the Life Cycle can risk impact the testing approach?|                                |                     |
|What does MISRA determine when the level of risk is understood?|                                |                     |
|[Back to content](#x)|                                |                     |
|Why is independent testing more effective at finding errors than simply allowing the developer and author to test their ow product?|                                | 164                 |
|Name 2 benefits of independence.|                                |                     |
|Which organisation provides de lowest level of independence, and which provides the highest?|                                |                     |
|[Back to content](#x)|                                |                     |
|Name and explain 5 approaches to the development of the test approach or test strategy.|                                | 168                 |
|Name one of the standards referred to that dictate the test approach.|                                |                     |
|Can discretion be used when defining a test approach testing?|                                |                     |
|[Back to content](#x)|                                |                     |
|What is the international standard for testing called?|                                | 174                 |
|Identify the 15 sections of the test plan.|                                |                     |
|What activities are contained within test planning?|                                |                     |
|Detail 4 typical exit criteria|                                |                     |
|[Back to content](#x)|                                |                     |
|Name 4 common test metrics|                                | 185                 |
|Name the 10 heading in the ISO 29119-3 Test summary report|                                |                     |
|Identify 3 ways a test manager can control testing if there are more tests than there is time to complete them.|                                |                     |
|[Back to content](#x)|                                |                     |
|Identify 3 details that are usually included in a defect report.|                                | 186                 |
|What is the name of the standard that includes an outline of a tst defect report?|                                |                     |
|What is a test defect?|                                |                     |
|[Back to content](#x)|                                |                     |
|Define configuration management.|                                | 187                 |
|What can be stored under configuration management?|                                |                     |
|Why is it important to have effective configuration management?|                                |                     |
|[Back to content](#x)|                                |                     |
