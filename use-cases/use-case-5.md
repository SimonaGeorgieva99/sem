# USE CASE: 5 Add new Employee's details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to add a new employee's details so that I can ensure the new employee is paid.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role. Database contains current employee details.

### Success End Condition
New employee is added.

### Failed End Condition
Employee details not added.

### Primary Actor
HR Advisor.

### Trigger
A request for employee information is sent to HR.

## MAIN SUCCESS SCENARIO
1. Add employee details.
2. HR advisor captures name of the employee to find information for.
3. HR advisor extracts details of the employee of a given role.
4. HR advisor adds employee's details.

## EXTENSIONS
Role does not exist:
HR advisor informs finance that employee cannot be added.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 3.0