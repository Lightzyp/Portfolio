# Daniel Macharia: Selected Projects

An index of software, database and security work, mostly from coursework at East Tennessee State University. Each entry links directly to the code or lab documentation.

## Library Management System

A Blazor web application for managing books, users, loans and returns. Book and user records are saved to CSV, and the service layer prevents a book from being borrowed twice.

- **Stack:** C#, ASP.NET Core Blazor, .NET 8, CSV files, xUnit
- **Skills:** service-layer design, dependency injection, unit test authoring
- **Context:** coursework
- **Code:** [Lightzyp/Lab-6](https://github.com/Lightzyp/Lab-6)

## Doctor and Patient Appointments

An MVC application that links doctors and patients through appointments. `Appointment` is an explicit join entity with its own date and notes, and appointments can be created, edited and deleted from either the doctor or the patient side.

- **Stack:** C#, ASP.NET Core MVC, Entity Framework Core, SQLite
- **Skills:** relational modeling, migrations, seed data, repository pattern, view models
- **Context:** CSCI 3110 coursework
- **Code:** [lab-03-many-to-many-crud](https://github.com/Lightzyp/coursework/tree/main/csci-3110/lab-03-many-to-many-crud)

## ShinraNet API

The backend for a social media course project. REST endpoints create, read, update and delete users and posts, and adjust post likes. The supplied starter frontend is not included.

- **Stack:** Python, FastAPI, Pydantic, SQLite, SQL
- **Skills:** REST endpoint implementation, parameterized SQL queries, HTTP error handling
- **Context:** CSCI 2910 coursework
- **Code:** [project-01-shinranet](https://github.com/Lightzyp/coursework/tree/main/csci-2910/project-01-shinranet)

## Modular Course Catalog

A JavaScript exercise that validates course data and models enrollment, open seats and waitlists. An ASP.NET MVC page loads the modules, and results appear in the browser console.

- **Stack:** JavaScript ES modules, ASP.NET MVC host page
- **Skills:** regular expressions, array methods, closures, classes, inheritance, private fields
- **Context:** CSCI 3110 coursework
- **Code:** [lab-04-course-catalog](https://github.com/Lightzyp/coursework/tree/main/csci-3110/lab-04-course-catalog)

## Ubuntu Server Hardening Lab

Documentation of an educational lab that secures an Ubuntu Server 24.04 virtual machine. It covers a non-root administrator account, SSH key authentication, firewall rules, Fail2Ban and automatic security updates.

- **Stack:** Ubuntu Server, VMware Workstation, OpenSSH, UFW, Fail2Ban
- **Skills:** Linux administration, SSH configuration, firewall rules, technical documentation
- **Context:** educational lab
- **Documentation:** [Lightzyp/ubuntu-server-hardening](https://github.com/Lightzyp/ubuntu-server-hardening)

## More work

- [Security lab reports](https://github.com/Lightzyp/coursework/tree/main/csci-3500): vulnerability scanning and firewall rules on classroom virtual machines, plus policy analysis
- [Full coursework archive](https://github.com/Lightzyp/coursework): all course folders, indexed by subject
- [GitHub profile](https://github.com/Lightzyp)
