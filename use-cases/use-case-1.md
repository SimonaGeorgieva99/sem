# USE CASE: 1 Produce a Report on the Salary of all Employees
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to produce a report on the salary of all employees so that I can support financial reporting of the organisation.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role. Database contains current employees salary data.

### Success End Condition
A report is available for HR to provide to finance.

### Failed End Condition
No report is produced.

### Primary Actor
HR Advisor.

### Trigger
A request for finance information is sent to HR.

## MAIN SUCCESS SCENARIO
1. Finance request salary information for all employees.
2. HR advisor captures name of employee to get salary information for.
3. HR advisor extracts current salary information of all employees of the given role.
4. HR advisor provides report to finance.

## EXTENSIONS
Role does not exist:
HR advisor informs finance no employee exists.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 3.0