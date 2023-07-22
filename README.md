# EmpManagementPortal_Angular.NET
A simple full stack web app built using Angular, .NET Core Web API and SQL Server

Sure, I'd be happy to help you create a README.md for the "EmpManagementPortal_Angular.NET" Git repository. Below is a template you can use as a starting point:

# Employee Management Portal (Angular & .NET)

![Project Logo](link_to_logo.png) <!-- You can add a logo here if you have one -->

## Overview

Employee Management Portal is a web application built using Angular and .NET technologies. It aims to provide an easy-to-use platform for managing employee data within an organization. The portal facilitates various functionalities such as adding new employees, updating employee information, and generating reports. The project is designed to be extensible, maintainable, and scalable to accommodate the needs of small to large businesses.

## Features

- **Employee Listing**: View a comprehensive list of all employees in the organization with relevant details.

- **Employee Details**: Access individual employee profiles to view and edit their personal information.

- **Add New Employee**: Add new employees to the system with necessary information.

- **Update Employee Information**: Modify employee details such as contact information, job title, etc.

- **Search and Filters**: Easily search for specific employees using filters or search queries.

- **Reports**: Generate reports based on various criteria such as employee performance, department, etc.

## Technologies Used

- Angular
- .NET Core Web API (C#)

## Prerequisites

Before running the project, ensure you have the following prerequisites installed:

- [Node.js](https://nodejs.org) with npm (Node Package Manager)
- [Angular CLI](https://angular.io/cli)
- [.NET SDK](https://dotnet.microsoft.com/download) (ensure you have the appropriate version)

## Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository:

```bash
git clone https://github.com/SaiyedRushan/EmpManagementPortal_Angular.NET.git
cd EmpManagementPortal_Angular.NET
```

2. Frontend Setup (Angular):

```bash
cd frontend/empmanagement
npm install
ng serve
```

3. Backend Setup (.NET):

```bash
cd WebAPI/WebAPI
dotnet restore
dotnet run
```

4. Open your web browser and go to `http://localhost:4200/` to access the application.
