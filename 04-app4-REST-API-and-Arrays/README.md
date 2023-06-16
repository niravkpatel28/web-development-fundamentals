## Application 4 : REST API using Array

Use the array created in
[Application 3](https://github.com/niravkpatel28/web-development-fundamentals/tree/main/03-app3-random-employee-generator)
as a starting point. This database contains an array, where each object is an
instance of class/type Employee.

Write functions that will perform the following operation on the above array.

1. Find an employee with specific id. (id is the unique primary key for search)
   Example `findEmployeeById(id: "1")` should return a single object from the
   array that has `"id = 1"`.

2. Find an employee information that matches the search object passed as an
   argument. Example `findEmployee({ name: "Employee Name" })` should return a
   single object from the array that has "name = Employee Name". Assume that the
   search object passed into the function contains only those keys that are
   present in the Employee object.
   `findEmployee({ name: "Employee Name", company:"Companyname" })` should
   return an employee object which matches these specification.

3. Update employee with a specific idThis function will take in arguments as id
   and an update object. Update object will contain a key value pairs that needs
   to be updated. eg. { name:  "updated  name" } Example
   `updateEmployeeById(id: "1",{update Object: updated values})` should update a
   single object from the array that has `"id=1"`. Assume that the
   `updateObject` will contain keys that are present in the Employee object.
   **Restrict** updating key properties like `id`.

4. Delete an object with a specific id. This function should take in an argument
   as id and delete the same from the array of Employees.

Once the application is completed, the learner is requested to submit the link
to code repository and the live hosted site, using the
[form](https://forms.gle/YcowC8wRTAnbeB8Z6), under the type of application
select

`Application 4 : REST API using Array`
