# USE CASE: 8 Delete an Employee's details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to delete an employee's details so that the company is compliant with data retention legislation.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role. Database contains current employee details.

### Success End Condition
Employee's details are deleted.

### Failed End Condition
Employee details not deleted.

### Primary Actor
HR Advisor.

### Trigger
A request for employee details is sent to HR.

## MAIN SUCCESS SCENARIO
1. Delete employee's details.
2. HR advisor captures name of the employee to find details.
3. HR advisor extracts details of the employee of a given role.
4. HR advisor deletes employee's details.

## EXTENSIONS
Role does not exist:
HR advisor informs finance that employee's details cannot be deleted.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 3.0