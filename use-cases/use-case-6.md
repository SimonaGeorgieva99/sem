# USE CASE: 6 View Employee's details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to view an employee's details so that the employee's promotion request can be supported.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role. Database contains current employee details.

### Success End Condition
Employee's details are viewed.

### Failed End Condition
Employee details not viewed.

### Primary Actor
HR Advisor.

### Trigger
A request for employee details is sent to HR.

## MAIN SUCCESS SCENARIO
1. View employee's details.
2. HR advisor captures name of the employee to find details.
3. HR advisor extracts details of the employee of a given role.
4. HR advisor views employee's details.

## EXTENSIONS
Role does not exist:
HR advisor informs finance that employee's details cannot be viewed.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 3.0