# SDLC Interview Questions

## What is verification
Verification ensures the product is designed to deliver all functionality to the customer; it typically involves reviews and meetings to evaluate documents, plans, code, requirements, and specifications; this can be done with checklists, issues list, and walkthroughs and inspection meetings.

## What is Validation
Validation ensures that functionality, as defined in requirements, is the intended behavior of the product; validation typically involves actual testing and takes place after verifications are completed. 

## What is the difference between build and release 
Build: It is an installable software that is given to the testing team by the development team. 
Release: It is an installable software that is handed over to the customer by the tester or developer. 

## What is Quality
Quality software is software that is reasonably bug-free, delivered on time and within budget, meets requirements and expectations and is maintainable

## What is good code 
A good code is code that works, is free of bugs and is readable and maintainable. 

## What is good design 
Design could mean to many things, but often refers to functional design or internal design. Good functional design is indicated by software functionality can be traced back to customer and end-user requirements. Good internal design is indicated by software code whose overall structure is clear, understandable, easily modifiable and maintainable; is robust with sufficient error handling and status logging capability; and works correctly when implemented. 

## Why do you recommend that we test during the design phase? 
Because testing during the design phase can prevent defects later on. We recommend verifying three things... 
1. Verify the design is good, efficient, compact, testable and maintainable. 
2. Verify the design meets the requirements and is complete (specifies all relationships between modules, how to pass data, what happens in exceptional circumstances, starting state of each module and how to guarantee the state of each module). 
3. Verify the design incorporates enough memory, I/O devices and quick enough runtime for the final product.

## What is software quality assurance 
Software Quality Assurance is oriented to *prevention*. It involves the entire software development process. Prevention is monitoring and improving the process, making sure any agreed-upon standards and procedures are followed and ensuring problems are found and dealt with. 

## What is quality assurance 
Quality Assurance ensures all parties concerned with the project adhere to the process and procedures, standards and templates and test readiness reviews. A lot will depend on team leads or managers, feedback to developers and communications among customers, managers and testers.

## What is the difference between the QA and software testing
The role of QA (Quality Assurance) is to monitor the quality of the "process" used to produce the software. While the software testing, is the process of ensuring the functionality of final product meets the user's requirement. 

## List out the roles of Software Quality Assurance engineer
A software quality assurance engineer tasks may include following things amongst others 
1.	Writing source code
2.	Software design
3.	Control of source code
4.	Reviewing code
5.	Change management
6.	Configuration management
7.	Integration of software
8.	Program testing
9.	Release management process

## What makes a good test engineer 
Has a "test to break" attitude. 
1. Takes the point of view of the customer,
2. Has a strong desire for quality, 
3. Has an attention to detail, He's also 
4. Tactful and diplomatic and 
5. Has good a communication skill, both oral and written. And he 
6. Has previous software development experience, too.

## List out various tools required to support testing during development of the application
To support testing during development of application following tools can be used: 
1.	Test Management Tools: JIRA, Quality Center etc.
2.	Defect Management Tools: Test Director, Bugzilla
3.	Project Management Tools: SharePoint
4.	Automation Tools: RFT, QTP, and WinRunner, Selenium

## What is walkthrough
A walkthrough is an informal meeting for evaluation or informational purposes. A walkthrough is also a process at an abstract level. It's the process of inspecting software code by following paths through the code (as determined by input conditions and choices made along the way). The purpose of code walkthroughs is to ensure the code fits the purpose. Walkthroughs also offer opportunities to assess an individual's or team's competency. 

## What is software life cycle 
Software life cycle begins when a software product is first conceived and ends when it is no longer in use. It includes phases like initial concept, requirements analysis, functional design, internal design, documentation planning, test planning, coding, document preparation, integration, testing, maintenance, updates, re-testing and phase-out.

## What is the role of documentation in QA
Documentation plays a critical role in QA. QA practices should be documented, so that they are repeatable. Specifications, designs, business rules, inspection reports, configurations, code changes, test plans, test cases, bug reports, user manuals should all be documented. Ideally, there should be a system for easily finding and obtaining of documents and determining what document will have a particular piece of information. Use documentation change management, if possible. 

## What about requirements
Requirement specifications are important and one of the most reliable methods of insuring problems in a complex software project is to have poorly documented requirement specifications. Requirements are the details describing an application's externally perceived functionality and properties. Requirements should be clear, complete, reasonably detailed, cohesive, attainable, and testable. 

## What is a test plan
A software project test plan is a document that describes the objectives, scope, approach and focus of a software testing effort. The process of preparing a test plan is a useful way to think through the efforts needed to validate the acceptability of a software product. The completed document will help people outside the test group understand the why and how of product validation. It should be thorough enough to be useful, but not so thorough that none outside the test group will be able to read it.

## What is a test case 
A test case is a document that describes an input, action, or event and its expected result, in order to determine if a feature of an application is working correctly. A test case should contain particulars such as a... 

1. Test case identifier
2. Test case name
3. Objective 
4. Input data requirements/steps 
5. Expected results. 

Please note, the process of developing test cases can help find problems in the requirements or design of an application, since it requires you to completely think through the operation of the application. For this reason, it is useful to prepare test cases early in the development cycle, if possible. 

## What does the test strategy include 
The test strategy includes an introduction, resource, scope and schedule for test activities, test tools, test priorities, test planning and the types of tests that has to be performed. 

## What is Traceability matrix?
The requirements specified by the users in the business requirement document may not be exactly translated into a functional specification. There will be a trace on between functional specification and business requirements. It is done on a one-to-one basis. This helps finding the gap between the documents. These gaps are the closed by the author of the Functional specifications (FS) or deferred after discussions 

Testers should understand these gaps and use them after getting this signed off from the author of the FS. The final FS form may vary from the original

## Standards and templates - what is supposed to be in a document 
All documents should be written to a certain standard and template. Standards and templates maintain document uniformity. It also helps in learning where information is located, making it easier for a user to find what they want. 

## What are the different levels of testing
Each level of testing is either considered black or white box testing. 

## What is black box testing
Black box testing is functional testing, not based on any knowledge of internal software design or code. Black box testing is based on requirements and functionality. 

## What is white box testing
White box testing is based on knowledge of the internal logic of an application's code. Typically done by developers.

## What is unit testing
Unit testing is the first level of dynamic testing and is first the responsibility of developers and then that of the test engineers. Unit testing is performed after the expected test results are met or differences are explainable/acceptable. 
 
## What is functional testing
Functional testing is black-box type of testing geared to functional requirements of an application. Test engineers *should* perform functional testing. 

## What is Adhoc testing
It is a testing phase where the tester tries to break the system by randomly trying the system's functionality. It can include negative testing as well. 

## What is integration testing
Upon completion of unit testing, integration testing begins. Integration testing is black box testing. The purpose of integration testing is to ensure distinct components of the application still work in accordance with customer requirements. Test cases are developed with the express purpose of exercising the interfaces between the components. This activity is carried out by the test team. Integration testing is considered complete, when actual results and expected results are either in line or differences are explainable/acceptable based on client input.

## What is incremental integration testing 
Incremental integration testing is continuous testing of an application as new functionality is recommended. This may require that various aspects of an application's functionality are independent enough to work separately, before all parts of the program are completed, or that test drivers are developed as needed. This type of testing may be performed by programmers, software engineers, or test engineers.

## What is system testing
System testing is black box testing, performed by the Test Team, the purpose of system testing is to validate an application's accuracy and completeness in performing the functions as designed. System testing is deemed complete when actual results and expected results are either in line or differences are explainable or acceptable, based on client input. Upon completion of integration testing, system testing is started. 

## What is Gray Box testing
A style of testing that attempts to blend both “white box” and “black box” test strategies.

## What is end-to-end testing 
Similar to system testing, the *macro* end of the test scale is testing a complete application in a situation that mimics real world use, such as interacting with a database, using network communication, or interacting with other hardware, application, or system. 

## What is regression testing 
Regression testing is like retesting after fixing or modification. Expected results from are compared to results of the software under test

## What is sanity testing 
Sanity testing is performed whenever cursory testing is sufficient to prove the application is functioning according to specifications. This level of testing is a subset of regression testing. It normally includes a set of core tests of basic GUI functionality to demonstrate connectivity to the database, application servers, printers, etc.

## What is performance testing? 
Performance testing verifies loads, volumes, and response times, as defined by requirements. 

## What is load testing? 
Load testing is testing an application under heavy loads, such as the testing of a web site under a range of loads to determine at what point the system response time will degrade or fail. 

## What is stress testing? 
Stress testing is testing that investigates the behavior of software (and hardware) under extraordinary operating conditions. For example, when a web server is stress tested, testing aims to find out how many users can be on-line, at the same time, without crashing the server

## What is acceptance testing? 
Acceptance testing is black box testing that gives the client/customer/project manager the opportunity to verify the system functionality and usability prior to the system being released to production. The acceptance test is the responsibility of the client/customer or project manager; however, it is conducted with the full support of the project team. The test team also works with the client/customer/project manager to develop the acceptance criteria. 

## What is alpha testing? 
Alpha testing is testing of an application when the development is nearing completion and when the application is not steady. Minor design changes can still be made as a result of alpha testing.

## What is beta testing? 
Beta testing is testing an application when development and testing are essentially completed, and final bugs and problems need to be found before the final release. Beta testing is typically performed by end-users or others, not programmers, software engineers, or test engineers.

## What is data driven testing 
Data driven testing is an automation testing framework, which tests the different input values on the AUT. These values are read directly from the data files. The data files may include csv files, excel files, data pools and many more

## What is configuration management? 
Configuration management (CM) covers the tools and processes used to control, coordinate and track code, requirements, documentation, problems, change requests, designs, tools, compilers, libraries, patches, changes made to them and who makes the changes

## What can be done if requirements are changing continuously? 
Work with management early on to understand how requirements might change, so that alternate test plans and strategies can be worked out in advance. It is helpful if the application's initial design allows for some adaptability, so that later changes do not require redoing the application from scratch entails.

## What if the application has functionality that wasn't in the requirements? 
It may take serious effort to determine if an application has significant unexpected or hidden functionality, which it would indicate deeper problems in the software development process. If the functionality isn't necessary to the purpose of the application, it should be removed, as it may have unknown impacts or dependencies that were not taken into account by the designer or the customer. 

## Why are there so many software bugs? 
Generally speaking, there are bugs in software because of unclear requirements, software complexity, programming errors, changes in requirements, errors made in bug tracking, time pressure, poorly documented code and/or bugs in tools used in software development.

## Give me five common problems that occur during software development. 
Poorly written requirements, unrealistic schedules, inadequate testing, adding new features after development is underway and poor communication. 
1. Requirements are poorly written when requirements are unclear, incomplete, too general, or not testable; therefore, there will be problems. 
2. The schedule is unrealistic if too much work is crammed in too little time. 
3. Software testing is inadequate if none knows whether or not the software is any good until customers complain or the system crashes. 
4. It's extremely common that new features are added after development is underway. 
5. Miscommunication either means the developers don't know what is needed, or customers have unrealistic expectations and therefore problems are guaranteed.

## What should be done after a bug is found? 
When a bug is found, it needs to be communicated and assigned to developers that can fix it. After the problem is resolved, fixes should be re-tested.

## What if the software is so buggy it can't be tested at all? 
In this situation the best bet is to have test engineers go through the process of reporting whatever bugs or problems initially show up, with the focus being on critical bugs. Since this type of problem can severely affect schedules and indicates deeper problems in the software development process, such as insufficient unit testing, insufficient integration testing, poor design, improper build or release procedures, managers should be notified and provided with some documentation as evidence of the problem. 

## How do you know when to stop testing? 
This can be difficult to determine. Many modern software applications are so complex and run in such an interdependent environment, that complete testing can never be done. Common factors in deciding when to stop are... 
1. Deadlines, e.g. release deadlines, testing deadlines; 
2. Test cases completed with certain percentage passed; 
3. Test budget has been depleted; 
4. Coverage of code, functionality, or requirements reaches a specified point; 
5. Bug rate falls below a certain level; or 
6. Beta or alpha testing period ends.

## What is Agile testing and what is the importance of Agile testing 
Agile testing is software testing, is testing using Agile Methodology. The importance of this testing is that, unlike normal testing process, this testing does not wait for the development team to complete the coding first and then doing testing. The coding and testing both go simultaneously. It requires continuous customer interaction. 

## Mention the different types of software testing? 
•	Unit testing
•	Integration testing and regression testing
•	System testing
•	Smoke testing
•	Functional testing
•	White box and Black box testing
•	Performance testing
•	Alpha and Beta testing
•	Load testing and stress testing
•	Shakeout testing

## List out various tools required to support testing during development of the application?
•	Test Management Tools: JIRA, Quality Center etc.
•	Defect Management Tools: Test Director, Bugzilla
•	Project Management Tools: SharePoint
•	Automation Tools: RFT, QTP, and WinRunner, Selenium

## What is Business Design Document? 
It is the document that describes the application functionalities of the user in detail. This document has the further details of the Business Requirement Document. This is a very crucial step in Software Development Life Cycle (SDLC). Sometimes the Business Requirement Document and Business Design Document can be lumped together to make only one Business Requirement Document.

## What is a Review? 
A review is an evaluation of a said product or project status to ascertain any discrepancies from the actual planned results and to recommend improvements to the said product. The common examples of reviews are informal review or peer review, technical review, inspection, walkthrough, management review. This is one of the manual testing interview questions.

## What is walk-through meeting? 
Once the Business Analysts complete the requirement document, they call a meeting to explain how the functionalities work, what the process is in the designed application and other details. The Business Analysts explain the high level functionalities of the application (software) that is going to the built. The participant members in the meeting may provide feed back and various point of views are expressed. This is walk-through meeting.

## Explain priority, severity in software testing? 
Priority is the level of business importance, which is assigned to a defect found. On the other hand, severity is the degree of impact, the defect can have on the development or operation of the component or the system.

## Is quality assurance and testing the same?
Quality assurance and testing is not the same. Testing is considered to be a
subset of QA. QA is should be incorporated throughout the software development
life cycle while testing is the phase that occurs after the coding phase.

## What is the difference between QA and testing?
The goals of QA are very different from the goals of testing. The purpose of QA
is to prevent errors is the application while the purpose of testing is to find
errors.

## What is the difference between Quality Control and Quality Assurance?
Quality control (QC) and quality assurance (QA) are closely linked but are very
different concepts. While QC evaluates a developed product, the purpose of QA is
to ensure that the development process is at a level that makes certain that the
system or application will meet the requirements.

## What is the difference between regression testing and retesting?
Regression testing is performing tests to ensure that modifications to a module
or system do not have a negative effect on previous releases. Retesting is
merely running the same testing again.

## Can you test a program and find 100% of the errors?
It is impossible to fine all errors in an application mostly because there is no
way to calculate how many errors exist. There are many factors involved in such
a calculation such as the complexity of the program, the experience of the
programmer, and so on.

## What is the difference between debugging and testing?
The main difference between debugging and testing is that debugging is typically
conducted by a developer who also fixes errors during the debugging phase.
Testing on the other hand, finds errors rather than fixes them. When a tester
finds a bug, they usually report it so that a developer can fix it.

## Authors

* **Hassen Hannachi** - *Initial work* - [HassenHannachi](https://github.com/HannachiHassen)

## License

This project is not under any License - Open source 
