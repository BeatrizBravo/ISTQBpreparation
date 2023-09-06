
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

