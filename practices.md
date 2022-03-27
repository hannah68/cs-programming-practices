# Programming Practices

For each of the empty headings below, fill in the detail.

## Software Quality

Software quality is not the measure of _what_ the program does, rather, it is the measure of _how well_ it does it. Indeed, it's important to consider _how well_ at every stage.

### Maintainability

Maintainability means how easily a system can be modified. It's one characteristic of software quality.(The ability to modify a software system or component to correct faults, improve performance, or adapt to a changing environment.)
1.comment
2.Header: write author, date, version number
3.indentation
4.whitespace

### Dependability

dependability is a measure of a system's availability, reliability, maintainability, and in some cases, other characteristics such as durability, safety and security. In real-time computing, dependability is the ability to provide services that can be trusted within a time-period.

### Efficiency

efficiency is the ratio of useful work to resources (processor and storage) expended. In other words, the ratio of the output to the input of a given system.(Efficient programming is programming in a manner that, when the program is executed, uses a low amount of overall resources pertaining to computer hardware.)
Time efficiency is how fast an algorithm runs in relation to input size, and space efficiency is how much memory that the algorithm consumes.
Efficiency, in software development, is simply the amount of software developed or requirement meant divided by the amount of resources used like time, effort, etc.

### Usability

usability describes how useable software is in relation to its intended purpose.( Usability is a quality attribute that assesses how easy user interfaces are to use. The word "usability" also refers to methods for improving ease-of-use during the design process.)
Usability refers to the quality of a user's experience when interacting with products or systems, including websites, software, devices, or applications. Usability is about effectiveness, efficiency and the overall satisfaction of the user.

## Planning

Planning is the thing you should do both _before_ you start building your application, and while you're doing it. In general, some thought _beforehand_ will lead to much better outcomes both _during_ and _after_.
Program planning involves multiple steps including the identification of a problem, selection of desired outcomes, assessment of available resources, implementation, and evaluation of the program

### Software Development Lifecycles

The Software Development Life Cycle (SDLC) is a structured process that enables the production of high-quality, low-cost software, in the shortest possible production time. The goal of the SDLC is to produce superior software that meets and exceeds all customer expectations and demands. The SDLC defines and outlines a detailed plan with stages, or phases, that each encompass their own process and deliverables.
seven phases of SDLC include planning, analysis, design, development, testing, implementation, and maintenance.

<img src='/assets/sdlc_stages.jpg'/>

Stage 1: Planning and Requirement Analysis
Requirement analysis is the most important and fundamental stage in SDLC. It is performed by the senior members of the team with inputs from the customer, the sales department, market surveys and domain experts in the industry.

Stage 2: Defining Requirements
Once the requirement analysis is done the next step is to clearly define and document the product requirements and get them approved from the customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements to be designed and developed during the project life cycle.

Stage 3: Designing the Product Architecture
SRS is the reference for product architects to come out with the best architecture for the product to be developed. Based on the requirements specified in SRS, usually more than one design approach for the product architecture is proposed and documented in a DDS - Design Document Specification.

Stage 4: Building or Developing the Product
In this stage of SDLC the actual development starts and the product is built. The programming code is generated as per DDS during this stage. If the design is performed in a detailed and organized manner, code generation can be accomplished without much hassle.

Stage 5: Testing the Product
This stage is usually a subset of all the stages as in the modern SDLC models, the testing activities are mostly involved in all the stages of SDLC. However, this stage refers to the testing only stage of the product where product defects are reported, tracked, fixed and retested, until the product reaches the quality standards defined in the SRS.

Stage 6: Deployment in the Market and Maintenance
Once the product is tested and ready to be deployed it is released formally in the appropriate market. 

SDLC Models:
- Waterfall Model 
It is also referred to as a linear-sequential life cycle model. It is very simple to understand and use. In a waterfall model, each phase must be completed before the next phase can begin and there is no overlapping in the phases.

- Iterative Model
Iterative process starts with a simple implementation of a subset of the software requirements and iteratively enhances the evolving versions until the full system is implemented. At each iteration, design modifications are made and new functional capabilities are added. The basic idea behind this method is to develop a system through repeated cycles (iterative) and in smaller portions at a time (incremental).

- Spiral Model
This Spiral model is a combination of iterative development process model and sequential linear development model i.e. the waterfall model with a very high emphasis on risk analysis. It allows incremental releases of the product or incremental refinement through each iteration around the spiral.

- V-Model 
The V-Model is an extension of the waterfall model and is based on the association of a testing phase for each corresponding development stage. This means that for every single phase in the development cycle, there is a directly associated testing phase. This is a highly-disciplined model and the next phase starts only after completion of the previous phase.

- Big Bang Model
The Big Bang model is an SDLC model where we do not follow any specific process. The development just starts with the required money and efforts as the input, and the output is the software developed which may or may not be as per customer requirement. This Big Bang Model does not follow a process/procedure and there is a very little planning required. Even the customer is not sure about what exactly he wants and the requirements are implemented on the fly without much analysis.

- Agile Model
Agile SDLC model is a combination of iterative and incremental process models with focus on process adaptability and customer satisfaction by rapid delivery of working software product.
Agile model believes that every project needs to be handled differently and the existing methods need to be tailored to best suit the project requirements. In Agile, the tasks are divided to time boxes (small time frames) to deliver specific features for a release.
Iterative approach is taken and working software build is delivered after each iteration. Each build is incremental in terms of features; the final build holds all the features required by the customer.

Following are the Agile Manifesto principles −

- Individuals and interactions − In Agile development, self-organization and motivation are important, as are interactions like co-location and pair programming.

- Working software − Demo working software is considered the best means of communication with the customers to understand their requirements, instead of just depending on documentation.

- Customer collaboration − As the requirements cannot be gathered completely in the beginning of the project due to various factors, continuous customer interaction is very important to get proper product requirements.

- Responding to change − Agile Development is focused on quick responses to change and continuous developmen

** Agile Vs Traditional SDLC Models--
Agile is based on the adaptive software development methods, whereas the traditional SDLC models like the waterfall model is based on a predictive approach. Predictive teams in the traditional SDLC models usually work with detailed planning and have a complete forecast of the exact tasks and features to be delivered in the next few months or during the product life cycle.

Predictive methods entirely depend on the requirement analysis and planning done in the beginning of cycle. Any changes to be incorporated go through a strict change control management and prioritization.

Agile uses an adaptive approach where there is no detailed planning and there is clarity on future tasks only in respect of what features need to be developed. There is feature driven development and the team adapts to the changing product requirements dynamically. The product is tested very frequently, through the release iterations, minimizing the risk of any major failures in future.

Customer Interaction is the backbone of this Agile methodology, and open communication with minimum documentation are the typical features of Agile development environment. The agile teams work in close collaboration with each other and are most often located in the same geographical location.

### Requirements Engineering
 Software requirements engineering refers to the first phase, before any of the actual designing, coding, testing, or maintenance takes place. The goal is to create an important early document and process in the software design. Often referred to as software requirements specification, or SRS, it determines what software is produced. It is basically the gathering of information of a customer's or potential customer/target audience's requirements for a system, before any actual design takes place.

### Software Architecture

Software architecture exposes the structure of a system while hiding the implementation details. Architecture also focuses on how the elements and components within a system interact with one other.(Software architecture in software engineering helps to expose the structure of a system while hiding some implementation details. Architecture focuses on relationships and how the elements and components interact with each other)

### Software Design
Software design is a process to transform user requirements into some suitable form, which helps the programmer in software coding and implementation.

For assessing user requirements, an SRS (Software Requirement Specification) document is created whereas for coding and implementation, there is a need of more specific and detailed requirements in software terms. The output of this process can directly be used into implementation in programming languages.

Software design is the first step in SDLC (Software Design Life Cycle), which moves the concentration from problem domain to solution domain. It tries to specify how to fulfill the requirements mentioned in SRS.


## Coding Standards

This section asks you to consider establishing consistent programming standards before you begin programming; hence, this is a bit like _planning_, too. In summary:

1. Know what the code must do
2. Maintain uniform naming (and layout) conventions throughout
3. Comment where necessary
4. Keep your code simple
5. Design your code! When building your apps, consider things like scalability and reuse

### Commenting and Documentation

Commenting involves placing Human Readable Descriptions inside of computer programs detailing what the Code is doing. Proper use of commenting can make code maintenance much easier, as well as helping make finding bugs faster. Further, commenting is very important when writing functions that other people will use.
Documentation is intended to help a user of your software understand how to achieve their goals

### Folder and File Organisation -- here



### Naming Conventions

Camel Case: userAccount
Pascal Case: UserAccount
Snake Case: account_balance
Kebab Case: main-section
Screaming Case: TAXRATE, TAX_RATE


### KISS

Keep it simple, stupid (KISS) is a design principle which states that designs and/or systems should be as simple as possible. Wherever possible, complexity should be avoided in a system—as simplicity guarantees the greatest levels of user acceptance and interaction.

### DRY

'don't repeat yourself,' is a principle of software development that aims at reducing the repetition of patterns and code duplication in favor of abstractions and avoiding redundancy.
Benefits of using the DRY principle include code readability and ease of maintenance

### Open/Closed

The Open-Closed Principle (OCP) states that software entities (classes, modules, methods, etc.) should be open for extension, but closed for modification. In practice, this means creating software entities whose behavior can be changed without the need to edit and recompile the code itself(It tells you to write your code so that you will be able to add new functionality without changing the existing code. That prevents situations in which a change to one of your classes also requires you to adapt all depending classes.)

### Scalability

Scalability is the measure of a system's ability to increase or decrease in performance and cost in response to changes in application and system processing demands.(Scalability is the ability of a program to scale. For example, if you can do something on a small database (say less than 1000 records), a program that is highly scalable would work well on a small set as well as working well on a large set (say millions, or billions of records))

### Reusability

Reusability is the quality of a code being used in different platforms for multiple functions. The reusability of code is based on the programming philosophy, which emphasizes a programmer is not repeating himself.

## Development

This section is all about the good habits we establish _while_ writing code - it's important to have some processes in place.

### Testing

Testing is the process of executing a program with the aim of finding errors. To make our software perform well it should be error-free. If testing is done successfully it will remove all the errors from the software.(Software testing is the process of evaluating and verifying that a software product or application does what it is supposed to do. The benefits of testing include preventing bugs, reducing development costs and improving performance.)

### Do One Thing (Single Responsibility)

The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part

### Debugging

Debugging, in computer programming and engineering, is a multistep process that involves identifying a problem, isolating the source of the problem, and then either correcting the problem or determining a way to work around it. The final step of debugging is to test the correction or workaround and make sure it works.

### Refactoring

the process of restructuring computer code without changing or adding to its external behavior and functionality.
