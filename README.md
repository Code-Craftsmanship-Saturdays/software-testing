# Code Craftsmanship Saturdays Fourth Session

To view lecture notes for this course, please consult the [github-pages](https://code-craftsmanship-saturdays.github.io/software-testing).

This meetup event gives an introduction to unit testing, integration testing,
and end-to-end-testing. We will also go over Mocks, Stubs, and Spies.

# Setup instructions
### 1. Install node.js via [Node.js](https://nodejs.org/en/download/)
### 2. Install couchdb via [CouchDB](http://couchdb.apache.org/)
### 3. Run `npm install` on root level of folder.
### 4. Run `npm run` to see all the scripts available

# Assignments

Each assignment folder has several exercise files. 
Read the instructions.md file in order to complete the exercises.
Some assignments may or may not have a program.js file that you will test.
Each assignment will have a file called program.test.js.
program.test.js will be where most of the logic exists for each test.

## Unit Testing

A unit test is an automated piece of code that invokes a unit of work in the system and then checks a single assumption about the behavior of that unit of work.
A unit of work is a single logical functional use case in the system that can be invoked by some public interface (in most cases).
A unit of work can span a single method, a whole class or multiple classes working together to achieve one single logical purpose that can be verified.

`Go to  unit-test folder`
open `program.test.js`
Read `instructions.md` in the folder
Run the command `npm run unit:test` at root of folder in order to see if tests pass.
Run the command `npm run unit:test:solution` at root of folder to see the solution output if you want.

## Integration Testing

Integration Testing is a level of software testing where individual units are combined and tested as a group.
Integration tests ensure that various units work together correctly.

`Go to integration-tests folder`
Read `instructions.md` in the folder
Run the command `npm run integration:test` at root of folder in order to see if tests pass.
Run the command `npm run integration:test:solution` to see the solution output.

## Behavior Driven Development

....

## Test Driven Development


## Mocks

....

## Spies

....


## Stubs

.....

## Functional Tests (End-to-End Tests)

....