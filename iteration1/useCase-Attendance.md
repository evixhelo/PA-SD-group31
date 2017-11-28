# Use case: Daily attendance report

# User Story
After all the children have arrived and payed the specified amount of money to the lunch-parent, the lunch parent starts the system and logs in. Then he/she is given a list of students in this group. For all students the lunch-parent marks a box for attendance if the student is present and marks a box for payment if the student has payed the required amount of money.

# Formal

## Name
Filling in the attendance sheet

## Scope
Attendence and payment registration system

## Level
User goal

## Primary actor
lunch-parent

## Stakeholders and Interests
- lunch-parent: wants to make sure all owned money is received
- students: wants to make sure there payment is registered

## Preconditions
- The lunch-parent is authenticated in the system
- the lunch-parent is authorized for this use case
- All students who can pay have payed

## Postconditions
- The presence of all students in this group are recorded
- The payment status of all students in this group are recorded

## Main succes scenario
1. lunch-parent opens the attendance sheet page for this group
2. lunch-parent chooses an attending student that is not yet chosen
3. lunch-parent marks student as present 
4. lunch-parent marks the payment of the student if the student payed
5. lunch-parent repeats step 2-4 until every student is chosen
6. lunch-parent submits the attendance sheet
7. the system informs the lunch-parent of the result

## Extensions
none

## Special requirements
none

## Technology and Data Variations List
none

## Frequency of Occurrence
Daily for every group

## Miscellaneous
none
