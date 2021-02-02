# Admin Dashboard Planning

### 1. What tech stack will you use for your final project?
React, Node, Postgres

### 2. Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application?
It will hopefully be full-stack, but by nature will likely be back-end focused.

### 3. Will this be a website? A mobile app? Something else?
This will be a website

### 4. What goal will your project be designed to achieve?
To create a simple internal-tooling application for companies non-technical users to be able to do user management and link to support tickets

### 5. What kind of users will visit your app? In other words, what is the demographic of your users?
The primary focus of my app will be on the company employees logging in for user management. There will also be a customer-facing component to submit support tickets.

### 6. What data do you plan on using? How are you planning on collecting your data?
User-inputed data (for the users). About half the app will be using 3rd party data from Zendesk. 

### 7. In brief, outline your approach to creating your project:

#### a. What does your database schema look like?
My database will be very simple, possibly only containing user information

#### b. What kinds of issues might you run into with your API?
I will need to integrate a customer ticket solution into my own dashboard

#### c. Is there any sensitive information you need to secure?
Customer and admin user data (passwords, emails)

#### d. What functionality will your app include?
Login in, submitting tickets, user management, and linking to view tickets

#### e. What will the user flow look like?
For customers: logging in, submitting tickets
For admins: logging in, viewing customers info and tickets, managing customers

#### f. What features make your site more than a CRUD app? What are your stretch goals?
Implementing the Zendesk API to allow for creation of tickets through a custom solution. User management from an admin standpoint.
