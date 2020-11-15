# Interview Prep

S - Situation

T - Task

A - Action

R - Result

## Agile and Scrum Potential Questions

### What is Agile?
Agile is a project management process that can be broken up into several stages (Iterations). It also includes the constant collaboration with the stakeholders and continuous improvement and iteration at each stage.
### What is Scrum?
Scrum is a framework where a development team can collaborate with each other on complex products while addressing complex adaptive problems. This is so that they can productively and creatively deliver products at the highest possible value.
### What is the difference between the two?
Although similar in definition, Scrum and Agile are not the same because Agile is a methodology in project management whereas Scrum is not even though it can be used within Agile.
### What are the 3 amigos?
The three amigos refer to the aim of monitoring an increment of work before, during and after development.

* Business - What is the problem at hand?
* Development - How might we solve this problem?
* Testing - What could possibly happen?
### What is a persona?
A persona is similar to an Actor from a use case. It is considered to be an instance of a user where it refers to a specific kind of actor. e.g. A customer would be considered an actor where as a certain type of customer would represent a persona.
### What are Scrum Roles, Artifacts and Events?
**There are 3 Roles within Scrum:**
 * Product Owner
    - The person responsible for the management of the product backlog.
    - Responsible for maximizing the value of the product.
 * Scrum Master
    - The person responsible for making sure that everyone within the team and outside the team understand the theories and practices of Scrum.
    - Answers to the Product Owner finding techniques to help manage the product backlog making sure the Owner knows how to arrange it in order to maximize value.
    - They also have the role of helping out the development team making sure they are self organised and doing other things to create high-value products.
 * Development Team
    - A team of professionals who do the work of delivering a potentially released increment of 'Done'.
 
 **Scrum Artifacts**
 * Product Backlog
    - It is an ordered list of everything that is needed in the product. A single source of requirements for any changes within the product. Product Owner is responsible for this.
 * Sprint Backlog
    - A set of product requirements to be completed for that specific sprint.
 * Increment
    - The sum of all product backlog items completed during a sprint and the value of the increments of all previous sprints.
    - A new increment must be done meaning that it aligns with the teams Definition of Done (DOD).
 
 Scrum Artifacts represent work or value to provide transparency and opportunities for adaptation and inspection.
 
**Scrum Events**
* Sprint
    - A time box of one month or less during which a "Done", useable, and potentially releasable product increment is created.
* Sprint Planning
    - Where the work that is to be performed in the Sprint is planned. This plan is created by the collaborative work of the entire Scrum Team.
    - Maximum 8 hours
* Daily Scrum
    - A 15 minute time boxed event for the development team to synchronize activities and create a plan for the next 24 hours. Like a daily stand up
* Sprint Review
    - Held at the end of a Sprint to inspect the Increment and adapt the Product Backlog if needed.
* Sprint Retrospective
    - An opportunity for the Scrum Team to inspect itself and create a plan for improvements to be enacted during the next Sprint

This events are used in Scrum to create regularity and to minimize the need for meetings not defined in Scrum.

### What is the difference between V-Model, Agile and Waterfall?
Agile differs from the other two methodologies because it allows the development of a product at basic functionality leaving room for iterations later on that will improve it. V-Model and Waterfall are more static and you cannot go onto the next stage in development until the previous stage is fully completed. Waterfall differs from the other two because it doesnt allow the product to be tested after each stage and increment. It saves all the testing until the end of the development period. Waterfall is also used when all the product requirements are delivered at the beginning of the process meaning that there is no need for constant contact with the product owner.

**Waterfall:**

S - Product Owner specifies all the product requirements and wants little involvement.

T - Deliver the product without the need for regular updates.

A - Waterfall is applied to deliver a finished product

R - Product delivered on time and pleasing the Owner with the end result

**V-Method**

S - Product defined with clear requirements and a strict deadline

T - Product an accurate product on time

A - V-Model applied to complete process with tests and inspections at the end of each stage

R - Product delivered on time with the right amount of tests carried out

**Agile**

S - Product Requirements given with the possibility to be updated later on.

T - Deliver the products while frequently collaborating with the Product Owner

A - Agile method applied

R - Basic functionality achieved. Product Owner then defines the improvements that are to be made.

## SQL Potential Questions
### What is a foreign key?
A foreign key  is seen as the link between two tables of a database. A foreign key in one table is a primary key in another. A primary key is a unique point of reference in a database table.

### What is DML and DDL?
These are 2 of 4 subgroups that divide commands in SQL

* DML - Data Manipulation Language
    - SELECT
    - INSERT
    - UPDATE
    - DELETE
    - MERGE
    - CALL
* DDL - Data Definition Language
    - CREATE
    - ALTER
    - DROP
    - TRUNCATE
    - COMMENT

## Python interview questions
### What is OOP and the 4 pillars?
OOP stands for Object Oriented Programming which uses objects and classes and is well suited for programs that are large and complex.

The 4 pillars are:
* Abstraction (The use of Generalisation and only showing whats relevant)
* Inheritance (Where child classes inherit the code and attributes of its parent)
* Polymorphism (Where the parameters in a method can take on many forms)
* Encapsulation (When you encase the data/functionality in an object)

**When have I implemented OOP**

S - A waiter in a restaurant wanted a program that allows them to put through 3 orders from the menu

T - Using the user stories, I had to create a program that fulfills all the requirements from the stories.

A - Using a parent class for the menu and a child class for Waiter's order process, I created a program using the 4 pillars with the aim of achieving the goal set.

R - Program was written successfully

### What is TDD and how do we used it?
Test Driven Development refers to a style of programming in which three activities are closely merged together. This is Coding, Testing, and design (refactoring code)

**How did I use it**

S - Simple Calculator Task

T - The aim was to create a test for a simple calculator program.

A - The test was written and when ran, it failed as there was no code yet written. Once the calculator was created using Classes and methods, I had to refactor the code to make it pass the test.

R - Program passed the test successfully.
