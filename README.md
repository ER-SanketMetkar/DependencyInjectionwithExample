# DependencyInjectionwithExample
In this created dependency injection using constructor injection.
why we do this - To achive loose coupling between EmployeeBL and EmployeeDAL class.
why loose couple becasue if we made any big changes in EmployeeDAL then we don't need to make any change in EmployeeBL.
-----------Description of Programm--------------------
in this I created a console application using .net framework.
then in that i create three classes explained as below.
1. Employee class this model class in that defined a details about the employee.
2. EmployeeDAL class in that i created one interface and declared a method into it i.e "List<Employee> SelectAllEmployees();"
3. then inherited the interface into EmployeeDAL class and did implementation of method into it.
4. EmployeeBL deaclared a ref variable of IEmployeeDAL and then created conscructor of EmployeeBL
5. and in Program class in main method created a object of EmployeeBL class and  injected a object of EmploeeDAL class into it as parameter to constructor of EmployeeBL
6. then it call the method SelectAllEmployees and result the list of employee.
