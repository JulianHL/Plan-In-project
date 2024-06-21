# Plan-In

## 1.Project Title
Daily Routine Planner

## 2.Project Scope
The Daily Routine Planner is a desktop application thought to help users manage their daily tasks and activities productively. The application will take advantage of the capabilities of a modern programming language and integrate various supportive tools and services to provide a comprehensive user experience.

### Scope of the Project Includes:
•	Core Features:
•	Task creation and management (add, edit, delete, and view tasks).

•	Calendar integration for scheduling and reminders.

•	Categorization of tasks (work, personal, urgent, etc.).

•	Supportive Tools and Services:
•	Database Management System (DBMS): Integration with a DBMS (Microsoft SQL Server) for storing user data, tasks, and settings.

•	API Support: Capability to interact with external services to provide contextual information within the planner (notification, transactions, etc.).

•	Front-End Visualization: A user-friendly graphical interface with charts and progress bars to visualize task completion and time management.

•	Version Control Integration: Use of Git for source code management, ensuring version control and collaborative development.


## 3.Project Users, Actors, Vendors, Actuators
### Project Users:
#### Primary Users: 
•   Individuals who need to organize their daily activities, including students, professionals, and homemakers.

#### Secondary Users: 
•   Project managers or team leaders who want to track team members' daily tasks.

#### Actors:
•	End Users: People using the application to manage their routines.

•	Administrators: Individuals managing the application settings and user accounts.

#### Vendors:
•	Database Vendors: Providers of the DBMS used in the project (Microsoft SQL Server).

•	API Service Providers: Providers of external APIs used for additional functionalities, notifications, transactions, etc.

#### Actuators:
•	Notification Actuator: Sends reminders about upcoming meetings and activities via notifications.

•	Payment Actuator: Initiates automatic withdrawals from the bank account and pays bills when approved. This could involve interacting with banking APIs or payment gateways to execute transactions.

•	Calendar Actuator: Manages the scheduling and organization of daily meetings and activities. It might add, modify, or delete events in the user's calendar application (such as Google Calendar or Outlook).

•	Approval Actuator: Handles the approval process for bill payments. It may notify the user when bills are due and await approval before initiating payments.

•	Logging Actuator: Records transaction logs or activity logs for auditing purposes or user reference. This actuator would log interactions with the system, such as when reminders are sent, bills are paid, or meetings are scheduled.

•	Error Handling Actuator: Manages error scenarios gracefully by providing feedback to users or taking corrective actions. 

•	Integration Actuators: Interfaces with external systems or APIs to gather information about bills, bank account balances, or other relevant data needed for the application's functionality.

## 4.Project Properties
### a.	Technology Stack:
•	IDE (Integrated Development Environment): 
Visual Studio Community Edition: 2022

•	Framework for Desktop Application:

•	WPF (Windows Presentation Foundation): .NET Framework 8.0

•	Google and Microsoft APIs:
Log in:
Google Sign-In: Google.Apis.Auth: 1.55.0.2414 
Microsoft Sign-In (Azure AD): Microsoft.Identity.Client: 4.43.0 
Calendars:
Google.Apis.Calendar.v3: 1.55.0.2414 (latest version)
Microsoft.Graph: 5.0.0 (latest version)

•	Database Management: 

•	Microsoft SQL Server

•	Entity Framework Core: 6.0.0

•	Sending Reminders: SMTP (System.Net.Mail): using .NET Framework 8.0

•	Interaction with Banks and Automatic Payments APIs: using .NET Framework 8.0

•	Security: Part of .NET Framework 8.0

### b.	Functional Requirements:

•	User Authentication: Secure login and registration system.

•	Task Management: CRUD operations for tasks.

•	Notification System: Reminders for upcoming tasks.

•	Reporting: Generation of daily, weekly, and monthly task reports.

### c.	Non-Functional Requirements:

•	Usability: The application should have an intuitive interface that is easy to navigate.

•	Performance: The application should be responsive and handle multiple tasks efficiently.

•	Security: User data must be securely stored and transmitted.

•	Scalability: The application should handle an increasing number of users and tasks without significant performance degradation.

### d.	Development Methodology:

•	Agile Methodology: Iterative development with Regular feedback from the instructor to ensure the application meets the needs effectively.

We will distribute the work in sprints to be able to manage small deliverables that united will be the result of our project, we will start with the front end, then continue with the back-end implementations, and lastly, we will do the different testing processes.

#### Sprint Plan
##### First – Second Week:
•	Create GitHub repository and define project characteristics and development methodology.

•	Discuss project approach and start planning.

•	Set up basic project structure, including initial frontend and backend scaffolding.

•	Documentation: Document project scope, initial requirements, and development methodology.

•	Meet to get feedback on the first sprint.

##### Third – Fourth Week:
•	Improve issues from the first sprint.

•	Design basic user interface with wireframes using Figma.

•	Define entities and tables for the database.

•	Develop the authentication page UI using WPF and initial backend logic using MVC architecture.

•	Configure the database.

•	Implement continuous integration.

•	Documentation: Document UI designs, database schema, and authentication logic.

•	Meet to get feedback on the second sprint.

##### Fifth – Sixth Week:
•	Correct issues from the second sprint.

•	Develop home page UI for daily meetings and tasks, integrate with database.

•	Implement backend logic for task management and integration with Google/Microsoft calendars.

•	Conduct unit testing for new features.

•	Documentation: Update documentation with home page UI designs, task management logic, and API integration details.

•	Meet to get feedback on the third sprint.

##### Seventh – Eighth Week:
•	Address feedback from the third sprint.

•	Build billing page UI and components for bills and payment methods.

•	Implement backend logic for transactions and payment processing.

•	Conduct integration testing.

•	Perform final revisions and comprehensive testing.

•	Documentation: Complete final documentation, including billing page details, transaction logic, and testing results.

•	Deploy final version and gather final feedback.


•	MVC Architecture promotes organized and modular code, which is especially beneficial for both development and maintenance.

### e.	Tools and Environment:

•	Development Environment: Visual Studio 2022.

•	Version Control System: GitHub or GitLab for repository management.

•	Testing Framework: NUnit for unit and integration testing.

## Conclusion
The purpose of the Daily Routine Planner is to allow users to organize their daily tasks and improve their productivity. By integrating core features of tasks
management with supportive tools and services like a database, APIs, and visualization, the application will offer a robust solution for routine planning and management.