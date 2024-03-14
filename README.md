# Secret Santa Website

## Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Objectives](Objectives)
4. [Identifying the Need](#identifying-the-need)
5. [Secret Santa Website Process](#secret-santa-website-process)
6. [Testing with Selenium in Eclipse](#testing-with-selenium-in-eclipse)
7. [PlantUML of Secret Santa Website](#plantuml-of-secret-santa-website)
8. [Comprehensive Overview of Secret Santa Application](Comprehensive-Overview-of-Secret-Santa-Application)
9. [Conclusion](#conclusion)

## Abstract

Last year, our organization faced challenges during our Christmas celebration, particularly with organizing our Secret Santa gift exchange. It became difficult to keep track of who was giving gifts to whom, leading to confusion and frustration among participants. To address this issue, a group of individuals within our organization collaborated to create a dedicated website specifically designed to manage our Secret Santa event. The main goal was to simplify participation and ensure fairness for all employees involved.

The website features several key functionalities aimed at enhancing the Secret Santa experience. It provides an easy signup process, facilitates the management of the employee list, and generates unique codes for each person's Secret Santa assignment. This ensures clarity and transparency, making it effortless for everyone to identify their gift recipients.

Overall, the website was developed with the intention of making our office Christmas celebration more enjoyable and organized. It focuses on fostering inclusivity and excitement for the holiday season by providing a user-friendly platform for coordinating the Secret Santa exchange.




## Introduction

The Secret Santa Website facilitates several essential processes to ensure the smooth and effective management of Secret Santa events within our organization. It begins with admin registration, where new administrators can easily create accounts by providing necessary details like their name, email, and password. Once this information is provided, the system validates it for accuracy, and upon successful validation, a new admin account is created, directing the admin to the login page for access.

Once logged in, administrators can navigate to the home page, where they are presented with various options to manage the Secret Santa event. One crucial feature is the QR code generation tool, allowing admins to generate unique QR codes for each participant, simplifying the process of assigning Secret Santas. These generated QR codes can be saved and distributed to employees, providing a seamless way for everyone to access their Secret Santa assignments.

The website also offers employee management functionalities, enabling admins to view, add, or delete employee details as needed. This feature ensures that participant information remains up-to-date and accurate throughout the event. Additionally, admins can easily access Secret Santa records to oversee and manage the gift exchange process effectively.

Moreover, the Secret Santa Website automates email notifications, sending them out on December 26th to inform participants of their assigned Secret Santas. These emails contain all the necessary details, ensuring clarity and transparency in the gift exchange process. Overall, the website streamlines the organization and execution of Secret Santa events, making it a valuable tool for creating memorable holiday experiences within our organization.

# Objectives
### Objectives

1. **Enhance User Experience:** Improve the website's usability and interface to ensure a seamless and enjoyable experience for users participating in the Secret Santa event.

2. **Streamline Event Management:** Develop administrative tools to simplify the process of organizing and managing the Secret Santa event, including features for employee data management and event tracking.

3. **Increase Participation:** Implement features and incentives to encourage higher participation rates among employees, fostering a greater sense of community and holiday spirit within the organization.

4. **Ensure Data Security:** Strengthen security measures to protect user data and ensure compliance with privacy regulations, maintaining trust and confidence among participants.

5. **Expand Feature Set:** Introduce new functionalities and integrations to enrich the Secret Santa experience, catering to diverse user preferences and needs.

6. **Improve Communication:** Enhance communication channels between participants and administrators, facilitating clearer instructions, reminders, and notifications throughout the event.

7. **Promote Accessibility:** Optimize the website for accessibility to ensure that all users, including those with disabilities, can fully participate in the Secret Santa event without barriers.

8. **Drive Engagement:** Incorporate gamification elements and community-building activities to enhance engagement and excitement surrounding the Secret Santa event.

9. **Facilitate Internationalization:** Support multiple languages and cultural customs to accommodate participants from diverse backgrounds and regions, promoting inclusivity and cultural sensitivity.

10. **Measure Success:** Establish key performance indicators (KPIs) to track the effectiveness of the Secret Santa Website in achieving its objectives and iteratively improve based on feedback and analytics.



## Identifying the Need
We noticed some issues during our previous office Christmas celebrations, especially concerning the organization of our Secret Santa gift exchange. Managing it manually led to confusion and made it challenging to ensure fairness for everyone involved. People often became confused about who they were supposed to give gifts to, which dampened the fun of the event.
Our mentors and Rashmi Chaudhary, Ma'am, identified these problems and realized the need for a better way to manage our Secret Santa event. They assigned the task to find a solution to the January intern. Everyone pitched in with their ideas, and among them, Aman's idea was chosen. The task of implementing the solution was then assigned to Aman, Aditi, and Irfan.


## Secret Santa Website Process

The Secret Santa Website facilitates various processes to ensure smooth operation and effective management of Secret Santa events within our organization. Here's a breakdown of each process:

### Admin Registration
1. **New admin visit the registration page:** New admins access the registration page to create an account.
2. **Provide necessary details:** Admins provide required information such as name, email, and password.
3. **Validate information:** The system validates the provided information.
4. **Create new admin account:** Upon successful validation, a new admin account is created.
5. **Admin directed to login page:** The admin is then redirected to the login page.

  ![Screenshot 2024-03-14 162927](https://github.com/Aditi22222/SecretSanta/assets/162342704/af67a8f5-f85c-4316-a43d-6e762184bbde)

### Admin Login
1. **Admin enters login credentials:** Admins enter their registered email and password.
2. **Validate login credentials:** The system validates the entered credentials.
3. **Redirect to home page upon successful login:** Upon successful validation, admins are redirected to the home page.
   
   ![Screenshot 2024-03-13 103449](https://github.com/Aditi22222/SecretSanta/assets/162342704/9706c40c-8341-49e3-be1d-b336a5795b40)

### Home Page
1. **Choose from various options:** Admins can choose from various options available on the home page.

  ![Screenshot 2024-03-14 162452](https://github.com/Aditi22222/SecretSanta/assets/162342704/62a658ee-6876-4d1b-9de6-f6317a9bc58d)


### QR Code Generation
1. **Admins access QR code generation:** Admins access the feature to generate QR codes.
2. **Generate QR code to become a Secret Santa:** QR codes are generated for each participant to become a Secret Santa.
3. **Save QR codes in a document file:** Generated QR codes are saved in a document file.
4. **Distribute QR codes to employees:** Admins distribute QR codes to employees.
5. **QR code button for each employee:** Each employee has a QR code button associated with their name.

  ![Screenshot 2024-03-14 161930](https://github.com/Aditi22222/SecretSanta/assets/162342704/8159bf15-563c-40ad-a85b-c14f3d50b061)

### Employee Management
1. **View/Add/Delete Employee List:** Admins can view, add, or delete employee details.
2. **Manage employee details:** Admins can manage employee details as needed.

   ![Screenshot 2024-03-14 161950](https://github.com/Aditi22222/SecretSanta/assets/162342704/914f1f03-7155-4c77-81d3-615f3cc81f97)

### Viewing Secret Santa Records
1. **View Secret Santa records:** Admins can view Secret Santa assignments.

   ![Screenshot 2024-03-14 162008](https://github.com/Aditi22222/SecretSanta/assets/162342704/19e5a9bf-5138-4c85-b5e1-c159ffb04a0b)

### Email Management
1. **System sends email notifications on December 26th:** Email notifications containing assigned Secret Santa details are sent.
2. **Contain assigned Secret Santa details:** Email notifications contain assigned Secret Santa details.
3. **Disclose assigned Secret Santa details via email:** Assigned Secret Santa details are disclosed via email.

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript
- React.js for building user interfaces
- Axios for making HTTP requests
- Express.js for backend API integration
- React Router DOM for client-side routing
- Web Vitals for web performance monitoring
- QRCode.react for generating QR codes
- react-hot-toast for toast notifications
- init for project initialization

### Backend
- Node.js for server-side operations
- Express.js for building RESTful APIs
- MongoDB for database management
- Mongoose for MongoDB object modeling
- Nodemailer for sending emails
- bcrypt for password hashing
- Cors for enabling CORS in Express.js
- Nodemon for automatic server restarts during development
- React Router for routing on the server side

### Frontend

- **HTML (Hypertext Markup Language):**
  - HTML is the standard markup language used for creating the structure and content of web pages.
  - It defines the layout and elements displayed on the user interface of the Secret Santa Website.

- **CSS (Cascading Style Sheets):**
  - CSS is used to style HTML elements, defining their appearance, layout, and visual presentation.
  - It enhances the aesthetics and user experience by controlling colors, fonts, and spacing.

- **JavaScript:**
  - JavaScript enables dynamic interactions and functionalities on web pages.
  - It handles user events and implements dynamic features to enhance interactivity.

- **React.js:**
  - React.js is a JavaScript library for building user interfaces.
  - It allows for creating reusable UI components and managing application state efficiently.

- **Axios:**
  - Axios is a promise-based HTTP client for making asynchronous HTTP requests in JavaScript applications.
  - It is used for making HTTP requests to the backend server and fetching data.

- **Express.js:**
  - Express.js is a minimalist web application framework for Node.js.
  - It is utilized for server-side rendering and routing in the frontend of the Secret Santa Website.

- **React Router DOM:**
  - React Router DOM provides routing capabilities to React applications.
  - It enables navigation between different pages without full page reloads.

- **Web Vitals:**
  - Web Vitals is used for monitoring key performance metrics such as page load time and interactivity.
  - It ensures optimal performance and user satisfaction.

- **QRCode.react:**
  - QRCode.react is a React component library for generating QR codes dynamically.
  - It facilitates the assignment of Secret Santas and enhances the user experience.

- **react-hot-toast:**
  - react-hot-toast is a library for displaying toast notifications in React applications.
  - It provides a simple way to show informative messages to users.

- **init:**
  - init is a command-line utility for initializing new projects and configuring dependencies.
  - It sets up the project structure and installs necessary dependencies.

### Backend

- **Node.js:**
  - Node.js is a runtime environment for executing JavaScript code outside of a web browser.
  - It is used for server-side operations in the Secret Santa Website.

- **Express.js:**
  - Express.js is a web application framework for Node.js.
  - It is utilized for building RESTful APIs, handling HTTP requests, and routing.

- **MongoDB:**
  - MongoDB is a NoSQL database management system.
  - It is used for storing and managing data in the Secret Santa Website.

- **Mongoose:**
  - Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js.
  - It provides a schema-based solution for modeling application data.

- **Nodemailer:**
  - Nodemailer is a module for sending emails from Node.js applications.
  - It is used for sending email notifications to users.

- **bcrypt:**
  - bcrypt is a library for hashing passwords securely in Node.js applications.
  - It ensures the security of user authentication credentials.

- **Cors:**
  - Cors is a middleware for enabling Cross-Origin Resource Sharing (CORS) in Express.js applications.
  - It facilitates communication between frontend and backend components.

- **Nodemon:**
  - Nodemon is a utility for automatically restarting Node.js applications when file changes are detected.
  - It enhances the development workflow by reducing manual intervention.

- **React Router:**
  - React Router is a library for routing in React applications.
  - It is used for server-side routing in the backend of the Secret Santa Website.


# Testing with Selenium in Eclipse

# Introduction to Selenium

Selenium stands as a cornerstone in the realm of automated web testing and browser automation. It's a suite of tools and libraries designed to simplify and streamline the process of testing web applications across different browsers and platforms. Since its inception, Selenium has evolved into a robust and versatile framework, empowering developers and testers to automate various web-related tasks efficiently.

At its core, Selenium enables users to interact with web elements, simulate user actions, and validate expected behaviors, all programmatically. Whether it's filling out forms, clicking buttons, navigating through pages, or verifying content, Selenium provides the necessary tools to replicate user interactions with precision and reliability.

One of Selenium's key strengths lies in its cross-browser compatibility, allowing tests to be executed seamlessly across popular browsers like Chrome, Firefox, Safari, and Internet Explorer. This ensures consistent behavior across different browser environments, crucial for ensuring the compatibility and reliability of web applications in today's diverse web landscape.

Moreover, Selenium supports multiple programming languages, including Java, Python, C#, Ruby, JavaScript, and more, making it accessible to a wide range of developers with varying skill sets and preferences. This flexibility enables teams to leverage their existing programming expertise and seamlessly integrate automated testing into their development workflows.

Beyond its primary use case in automated testing, Selenium finds applications in web scraping, data extraction, and browser automation for various tasks such as performance monitoring, content validation, and repetitive administrative tasks.

In essence, Selenium empowers developers and testers to accelerate the testing process, enhance the quality and reliability of web applications, and ultimately deliver better user experiences. Its rich feature set, combined with a vibrant community and extensive documentation, makes Selenium a go-to choice for automating web-related tasks in today's fast-paced software development landscape.

# Basic Setup For Selenium(JDK, Maven Project, Eclipse 
To set up a basic Selenium project using JDK, Maven, and Eclipse, follow these steps:

### Step 1: Install JDK (Java Development Kit)

1. Download and install the latest version of JDK from the official Oracle website.
2. Set up the JAVA_HOME environment variable to point to the JDK installation directory.
   
   ![Screenshot 2024-03-07 102822](https://github.com/Aditi22222/Selenium/assets/162342704/190b5212-a3eb-4b0f-bec3-c53d29395cc2)


### Step 2: Install Eclipse IDE

1. Download and install the Eclipse IDE for Java Developers from the Eclipse Foundation website.
2. Launch Eclipse and set up any necessary preferences.

    ![Screenshot 2024-03-07 103403](https://github.com/Aditi22222/Selenium/assets/162342704/ca0c9b41-4892-41ef-b6a1-2857b08f8c6a)

### Step 3: Create a Maven Project

1. Open Eclipse IDE.
2. Go to "File" -> "New" -> "Other...".
3. In the wizard, select "Maven" -> "Maven Project" and click "Next".
4. Choose "Create a simple project (skip archetype selection)" and click "Next".
5. Enter the Group Id, Artifact Id, and Version for your project. Click "Finish" to create the Maven project.

    ![Screenshot 2024-03-07 103801](https://github.com/Aditi22222/Selenium/assets/162342704/0e6e7e35-de12-42c7-84b1-5faf3c325c66)

    ![Screenshot 2024-03-07 103844](https://github.com/Aditi22222/Selenium/assets/162342704/46ab9d6c-395c-46ae-b6fa-3b02eb705d90)
   

### Step 4: Add Selenium Dependencies

1. **Save the File:** After adding the dependencies, save the `pom.xml` file.

2. **Update Maven Project:** Right-click on your Maven project in the project explorer, navigate to "Maven" -> "Update Project...". This will update the project with the newly added dependencies.

3. **Wait for Dependencies to Download:** Maven will automatically download the required libraries and manage them for you. Wait for Maven to finish downloading the dependencies.

4. **Verify Dependencies:** Once the dependencies are downloaded successfully, you can verify that they are added to your project by expanding the "Maven Dependencies" folder in the project explorer.


![Screenshot 2024-03-07 111936](https://github.com/Aditi22222/Selenium/assets/162342704/4b2111f2-4cff-4db6-85f8-66498d1ca426)

### Step 5: Write Your Selenium Tests

1. Create a new Java class within your Maven project.
2. Write your Selenium test code using the Selenium WebDriver API.
3. Make sure to include necessary import statements for Selenium classes.

![Screenshot 2024-03-07 114828](https://github.com/Aditi22222/Selenium/assets/162342704/68e0fece-95e4-49fe-9964-c0e9ea4daf0b)

![Screenshot 2024-03-07 115548](https://github.com/Aditi22222/Selenium/assets/162342704/a190ecd3-16df-4d52-a4d1-ab36b55f9f18)

### Analyzing Test Results:

After executing the test scripts, the results were analyzed to ensure that the Secret Santa Website functioned as expected. Test cases were designed to cover various functionalities of the website, including user authentication, QR code generation, and email notifications.

By utilizing Selenium WebDriver in Eclipse, comprehensive testing of the Secret Santa Website was conducted to verify its functionality, reliability, and user experience.

## PlantUML of Secret Santa Website
### PlantUML of Secret Santa Website

The PlantUML diagram below illustrates the architecture and flow of the Secret Santa Website:

```plantuml
@startuml

skinparam package {
    BackgroundColor LightPink
    BorderColor Black
}

package "Admin Registration" {
    [New admin visit the registration page]
    [Provide necessary details]
    [Validate information]
    [Create new admin account]
    [Admin directed to login page]
}

package "Admin Login" {
    [Admin enters login credentials]
    [Validate login credentials]
    [Redirect to home page upon successful login]
}

package "Home Page" {
    [Choose from various options]
}

package "QR Code Generation" {
    [Admins access QR code generation]
    [Generate QR code to become a Secret Santa]
    [Save QR codes in a document file]
    [Distribute QR codes to employees]
    [QR code button for each employee]
}

package "Employee Management" {
    [View/Add/Delete Employee List]
    [Manage employee details]
}

package "Viewing Secret Santa Records" {
    [View Secret Santa records]
    [Manage Secret Santa assignments]
}

package "Email Management" {
    [System sends email notifications on December 26th]
    [Contain assigned Secret Santa details]
    [Disclose assigned Secret Santa details via email]
}

package "Frontend" {
    [HTML]
    [CSS]
    [JavaScript]
    [React.js] as react
    [Axios]
    [Express.js]
    [React Router DOM]
    [Web Vitals]
    [QRCode.react]
    [react-hot-toast]
    [init]
}

package "Backend" {
    [Node.js] as node
    [Express.js]
    [MongoDB] as mongo
    [Mongoose]
    [Nodemailer]
    [bcrypt]
    [Cors]
    [Nodemon]
    [React Router]
}

[New admin visit the registration page] --> [Provide necessary details]
[Provide necessary details] --> [Validate information]
[Validate information] --> [Create new admin account]
[Create new admin account] --> [Admin directed to login page]

[Admin directed to login page] --> [Admin enters login credentials]
[Admin enters login credentials] --> [Validate login credentials]
[Validate login credentials] --> [Redirect to home page upon successful login]

[Redirect to home page upon successful login] --> [Choose from various options]
[Choose from various options] --> [Admins access QR code generation]
[Choose from various options] --> [View/Add/Delete Employee List]
[Choose from various options] --> [View Secret Santa records]

[Admins access QR code generation] --> [QR Code Generation]
[QR Code Generation] --> [Generate QR code to become a Secret Santa]
[Generate QR code to become a Secret Santa] --> [Save QR codes in a document file]
[Save QR codes in a document file] --> [Distribute QR codes to employees]
[Distribute QR codes to employees] --> [QR code button for each employee]

[QR code button for each employee] --> [Employee scans QR code]
[Employee scans QR code] --> [Open form to fill details]

[View/Add/Delete Employee List] --> [Employee Management]
[Employee Management] --> [Manage employee details]

[View Secret Santa records] --> [Viewing Secret Santa Records]
[Viewing Secret Santa Records] --> [Manage Secret Santa assignments]

[System sends email notifications on December 26th] --> [Email Management]
[Email Management] --> [Contain assigned Secret Santa details]
[Contain assigned Secret Santa details] --> [Disclose assigned Secret Santa details via email]

node --> mongo : Database Operations
react --> node : API Requests
node --> react : Data Responses

@enduml




![Screenshot 2024-03-14 170825](https://github.com/Aditi22222/SecretSanta/assets/162342704/9c4e9c4b-c8c2-4646-9a17-be54779b5530)


 # Comprehensive Overview of Secret Santa Application
 # Backend: Node.js/Express with MongoDB

## User Authentication:
- Express.js handles HTTP requests.
- MongoDB is connected using Mongoose.
- Two schemas, Emp and User, are defined with Mongoose.
- Routes for user authentication (/register, /login) are implemented.
- Passwords are hashed with bcrypt before saving.
- Login route checks email existence and compares hashed passwords.

## Employee Management:
- Endpoints for adding, fetching, updating, and deleting employees (/emplist, /emplist/:id, /empl/:id).
- Employee data includes first name, last name, and email.

## Secret Santa Assignment:
- Endpoint /santasubmit assigns Secret Santas to employees.
- It sends emails to each employee with their Secret Santa's details.

# Frontend: React.js

## Components:
- **Register:** User registration form with form validation using Axios for HTTP requests and React Hot Toast for notifications.
- **Santaform:** Form for submitting Secret Santa entries with form validation and Axios for HTTP requests.
- **ShowQr:** Displays QR code generated based on URL parameters.
- **UpdateEmp:** Incomplete component for updating employee information.
- **App:** Main component with React Router for navigation.

## Routing:
- React Router handles client-side routing with different routes mapped to corresponding components.

## Root Rendering:
- ReactDOM.createRoot creates a root instance for rendering in strict mode.

## Event Handlers and Form Validation:
- Handlers like handlechange, handlechangeemail, and handlechangepass update state.
- Form validation checks required fields and data criteria.

## API Requests:
- Axios makes HTTP requests to localhost:9002 for user registration and Santa event entries.

## Styling:
- Basic CSS styling applied to components.

## Additional Features:
- Nodemailer used for sending emails.
- QR code generation (/empqr) and viewing Secret Santa records (/records).

## Conclusion

In conclusion, our Secret Santa Website is a great way to organize and manage our gift exchange at work. It's easy to use and makes the whole process smooth. With features like simple signup, easy gift assignments, and clear email notifications, everyone can enjoy the holiday fun without any hassle.

Plus, it helps us all feel included and brings us closer as a team. By using our website, we can make our office celebrations even more special and memorable. We're always working to make it better, so our holiday traditions can continue to bring joy year after year.

