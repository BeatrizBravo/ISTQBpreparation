**Content:**
 <a id="x"></a>
 - [Introduction](#1)
 - [Type of review](#2)
 - [Typical defects in static testing](#3)

 <a id="1"></a>
 
# Intro

**Static** test is carried out **without** executing any code.
<br>


>By:
>> -  reading and 
>>- commenting on 
> 
>Any work product such:
>>* a requirement specification
>>* a piece of code 
>>* a test plan
>>* a test case


|Static|Dynamic|
|:----|:----|
|- finds causes of failure (Defect)|- finds the failures themselves (failure)|
|- finds them early|- finds them late|
|- defect cheap to fix|- defect expensive to fix|
|-----Te techniques  are complementary----- |
| | |



<br>

|static analysis and dynamic testing have the same objective =>|identifying defects|
|:----|:----|

<br>

[Back to content](#x)
 <a id="2"></a>

# Type of review

|Type of review|Description|Advantages|Disadvantages|
|:----|:----|:----|:----|
|Informal Review|Review conducted without any formal structure or methods.|Quick and easy to conduct, suitable for small documents.|May miss important issues, may lack consistency and thoroughness.|
|Walkthrough|A formal, slow-paced review that focuses on educating reviewers and discovering defects.|Helps identify defects early, can improve understanding of the document, fosters teamwork.|Can be time-consuming, may be too informal for some contexts.|
|Technical Review|A formal, structured review that uses specific techniques and criteria to identify defects.|Unearths comprehensive list of defects, improves quality of the document.|Can be time-consuming and costly to plan and execute.|
|Inspection|A highly formal, rigorous review process that analyzes the document with the goal of finding as many defects as possible.|Finds many defects, helps ensure high quality.|Can be time-consuming, requires extensive preparation and training.|
|Peer Review|A review conducted by peers who share similar qualifications and experience, using a set of guidelines.|Can identify defects early, fosters collaboration and knowledge sharing, helps ensure high quality.|Limited to the expertise of the participants, may overlook some issues.|
<br>

[Back to content](#x)
 <a id="3></a>

# Typical defects in static testing
|Typical defects| |
|:----|:----|
|Requirement defects |inconsistencies<br> ambiguities<br> contradictions<br> omissions<br> inaccuracies<br> redundancies|
|Design defects|inefficient algorithms or database structures<br> high coupling (the lack of interdependent between modules) <br> low cohesion (associated with undesirable traits such as being difficult to maintain, test, reuse or even understand.|
|Coding defects | variables with undefined values<br> variables that are declared but never used<br> unreachable code <br>duplicate code|
|Deviations from standards |lack of adherence to coding standards|
|Incorrect interface specifications |different units of measurement used by the **calling** system than by the **called** system|
|Security vulnerabilities |susceptibility to buffer overflows|
|Gaps or inaccuracies in test basis traceability or coverage |missing tests for an criterion|


