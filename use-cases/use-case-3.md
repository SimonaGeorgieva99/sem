# USE CASE: 3 Produce a Report on the Salary of Employees in given Department
## CHARACTERISTIC INFORMATION
### Goal in Context
As an department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the role. Database contains current employees salary data in the department.

### Success End Condition
A report is available for department manager to provide to finance.

### Failed End Condition
No report is produced.

### Primary Actor
Department manager.

### Trigger
A request for finance information is sent to the department manager.

## MAIN SUCCESS SCENARIO
1. Finance request salary information for all employees in a department.
2. Department manager captures name of employee in a given department to get salary information for.
3. Department manager extracts current salary information of all employees in the department.
4. Department manager provides report to finance.

## EXTENSIONS
Role does not exist:
Department manager informs finance no employee exists.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 3.0