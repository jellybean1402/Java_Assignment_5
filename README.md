# Java_Assignment_5

# PART 1

**Circle Class:**
- `radius`: Instance variable representing the radius of the circle.
- `Circle(double radius)`: Constructor initializing the circle with a given radius.
- `area()`: Calculates and returns the area of the circle using the formula π * radius * radius.
- `perimeter()`: Calculates and returns the perimeter (circumference) of the circle using the formula 2 * π * radius.



# PART 2

- **Employee Abstract Class:**
- `empName`, `empAddress`, ... : Private instance variables representing various employee details.
- `sc`: Scanner instance for user input.
- `Employee()`: Constructor for the `Employee` class.
- `getEmployeeDetails()`: Takes user input for employee details such as ID, name, designation, etc.
- `salaryCalculation()`: Abstract method, to be implemented by subclasses for salary calculation.

Certainly, here are all the getter and setter methods present in the `Employee` class:

**Getter Methods:**
- `getEmpName()`: Returns the employee's name.
- `getEmpAddress()`: Returns the employee's address.
- `getEmpDesignation()`: Returns the employee's designation.
- `getEmpDept()`: Returns the employee's department.
- `getDoj()`: Returns the employee's date of joining.
- `getBankName()`: Returns the employee's bank name.
- `getUAN()`: Returns the employee's UAN (Universal Account Number).
- `getPF_NO()`: Returns the employee's PF (Provident Fund) number.
- `getESINo()`: Returns the employee's ESI (Employee State Insurance) number.
- `getEmpId()`: Returns the employee's ID.
- `getBankAcctNo()`: Returns the employee's bank account number.
- `getTotalWorkingDays()`: Returns the total number of working days.
- `getPaidDays()`: Returns the number of paid days.
- `getLeavesTaken()`: Returns the number of leaves taken by the employee.
- `getLopDays()`: Returns the number of leave without pay days.
- `getGrosswage()`: Returns the gross wage of the employee.
- `getTotalEarning()`: Returns the total earnings of the employee.
- `getTotalDeductions()`: Returns the total deductions from the employee's earnings.
- `getBasicWage()`: Returns the basic wage of the employee.
- `getHra()`: Returns the HRA (House Rent Allowance) of the employee.
- `getConveyanceAllowances()`: Returns the conveyance allowances of the employee.
- `getMedicalAllowances()`: Returns the medical allowances of the employee.
- `getOtherAllowances()`: Returns the other allowances of the employee.
- `getEpf()`: Returns the EPF (Employee Provident Fund) of the employee.
- `getEsi()`: Returns the ESI (Employee State Insurance) of the employee.
- `getPt()`: Returns the PT (Professional Tax) of the employee.
- `getLoanRecovery()`: Returns the loan recovery amount from the employee.

**Setter Methods:**
- `setEmpName(String empName)`: Sets the employee's name.
- `setEmpAddress(String empAddress)`: Sets the employee's address.
- `setEmpDesignation(String empDesignation)`: Sets the employee's designation.
- `setEmpDept(String empDept)`: Sets the employee's department.
- `setDoj(String doj)`: Sets the employee's date of joining.
- `setBankName(String bankName)`: Sets the employee's bank name.
- `setUAN(long UAN)`: Sets the employee's UAN (Universal Account Number).
- `setPF_NO(long PF_NO)`: Sets the employee's PF (Provident Fund) number.
- `setESINo(long ESINo)`: Sets the employee's ESI (Employee State Insurance) number.
- `setEmpId(long empId)`: Sets the employee's ID.
- `setBankAcctNo(long bankAcctNo)`: Sets the employee's bank account number.
- `setTotalWorkingDays(int totalWorkingDays)`: Sets the total number of working days.
- `setPaidDays(int paidDays)`: Sets the number of paid days.
- `setLeavesTaken(int leavesTaken)`: Sets the number of leaves taken by the employee.
- `setLopDays(int lopDays)`: Sets the number of leave without pay days.
- `setGrosswage(double grosswage)`: Sets the gross wage of the employee.
- `setTotalEarning(double totalEarning)`: Sets the total earnings of the employee.
- `setTotalDeductions(double totalDeductions)`: Sets the total deductions from the employee's earnings.
- `setBasicWage(double basicWage)`: Sets the basic wage of the employee.
- `setHra(double hra)`: Sets the HRA (House Rent Allowance) of the employee.
- `setConveyanceAllowances(double conveyanceAllowances)`: Sets the conveyance allowances of the employee.
- `setMedicalAllowances(double medicalAllowances)`: Sets the medical allowances of the employee.
- `setOtherAllowances(double otherAllowances)`: Sets the other allowances of the employee.
- `setEpf(double epf)`: Sets the EPF (Employee Provident Fund) of the employee.
- `setEsi(double esi)`: Sets the ESI (Employee State Insurance) of the employee.
- `setPt(double pt)`: Sets the PT (Professional Tax) of the employee.
- `setLoanRecovery(double loanRecovery)`: Sets the loan recovery amount from the employee.

**Concrete Methods:**
- `getEmployeeDetails()`: Takes user input for employee details.
- `setTotalWorkingDays(int totalWorkingDays)`: Setter method for total working days.
- `setLopDays(int lopDays)`: Setter method for leave without pay days.

**Salary and Allowance Methods:**
- `getGrosswage()`, `setGrosswage(double grosswage)`, ... : Getter and setter methods for salary-related details.
- Methods for basic salary, HRA, conveyance allowances, medical allowances, other allowances, EPF, ESI, PT, loan recovery.

**Main Employee Class Usage:**
- `getEmployeeDetails()`: Creates an instance of the `Employee` class and prompts the user for input to set employee details.
- `salaryCalculation()`: Abstract method to be implemented by subclasses for salary calculation.

Note: The `Employee` class is abstract and serves as a base class for other employee-related classes. The provided details cover various aspects of employee information and financial components.





