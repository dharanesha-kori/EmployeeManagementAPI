<p>Please find the Read Me document for more details.</p>

<h1>
    Employee Management Web UI - Project Structure
</h1>

The Employee Management Web UI is an MVC application that provides a user interface to interact with the Employee Management API. It allows users to view and manage employee data using a dashboard-style interface. The application is built using C#, ASP.NET MVC framework, and Bootstrap for responsive and modern UI components.
 
<h3>Features</h3>
The Employee Management Web UI offers the following features:

<h3>Dashboard</h3>
Dashboard: The dashboard provides an overview of employee data, including a grid displaying employee records with filtering, sorting, and pagination options.

<h3>Manager Selection</h3>
Manager Selection: Users can select a manager from a dropdown list to filter the employee records based on the selected manager. The list dynamically updates to show employees associated with the selected manager.

<h3>Bootstrap Grid</h3>
Bootstrap Grid: The employee records are displayed using a responsive Bootstrap grid component, ensuring optimal display across different screen sizes and devices.

<h3>Filters</h3>
Filters: The grid allows users to apply filters to narrow down the displayed employee records based on specific criteria such as name, position, office, age, start date, and salary.

<h3>Sorting</h3>
Sorting: Users can sort the employee records based on various columns such as name, position, office, age, start date, and salary. Sorting can be done in ascending or descending order.

<h3>Pagination</h3>
To enhance usability and performance, the grid implements pagination, allowing users to navigate through multiple pages of employee records.


<h1>Web API Project Structure</h1>
The Employee Management API is a RESTful API designed to manage employee data. It provides endpoints to create, retrieve, update, and delete employee records. The API is built using C# and ASP.NET MVC framework.

The Employee Management API project is structured into multiple projects to follow a modular and organized architecture. The main projects in the solution are as follows:

<h3>EmployeeManagement.API</h3>
This project contains the main API controllers and configuration files. It handles the HTTP requests and responses, routing, and overall API functionality.

<h3>EmployeeManagement.API.Repository</h3>
This project is responsible for data access and persistence. It includes repository classes that interact with the database to perform CRUD operations on employee records. It utilizes a Unit of Work pattern and Entity Framework to manage database connections and transactions.

<h3>EmployeeManagement.API.Service</h3>
This project contains the business logic and services for handling employee-related operations. It provides functionalities like employee creation, retrieval, update, and deletion. The services communicate with the repository layer to access and manipulate data.

<h3>
    EmployeeManagement.API.Model
</h3>
EmployeeManagement.API.Model: This project defines the data models and entities used throughout the application. It includes classes that represent employee records, as well as any related entities or data structures.

<h3>EmployeeManagement.API.Test</h3>
EmployeeManagement.API.Test: This project contains unit tests for the API, repository, and service layers. It ensures the functionality and correctness of the implemented features.

