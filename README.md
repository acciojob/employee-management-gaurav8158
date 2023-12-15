# Employee Management

## Instructions

1. Create a class Employee with properties `name` and `salary`.
2. Add a method `giveRaise(amount)` that increases the salary by the amount parameter.
3. Create a `subclass Manager` that `extends Employee`, and has an additional property `department`.
4. Override the `giveRaise(amount)` method of the Manager class to also log the `department` and the `new salary` to the console.

## Example

```(js)
let employee = new Employee("John Doe", 50000);
employee.giveRaise(5000);
console.log(employee.salary); // 55000

let manager = new Manager("Jane Smith", 80000, "Sales");
manager.giveRaise(10000); // New salary for Jane Smith in Sales: 90000
```
