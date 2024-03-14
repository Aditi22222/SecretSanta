# Secret Santa Website

## Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Identifying the Need](#identifying-the-need)
4. [Secret Santa Website Process](#secret-santa-website-process)
5. [Testing with Selenium in Eclipse](#testing-with-selenium-in-eclipse)
6. [PlantUML of Secret Santa Website](#plantuml-of-secret-santa-website)
7. [Conclusion](#conclusion)

## Abstract

Last year, our organization faced challenges during our Christmas celebration, particularly with organizing our Secret Santa gift exchange. It became difficult to keep track of who was giving gifts to whom, leading to confusion and frustration among participants. To address this issue, a group of individuals within our organization collaborated to create a dedicated website specifically designed to manage our Secret Santa event. The main goal was to simplify participation and ensure fairness for all employees involved.

The website features several key functionalities aimed at enhancing the Secret Santa experience. It provides an easy signup process, facilitates the management of the employee list, and generates unique codes for each person's Secret Santa assignment. This ensures clarity and transparency, making it effortless for everyone to identify their gift recipients.

Overall, the website was developed with the intention of making our office Christmas celebration more enjoyable and organized. It focuses on fostering inclusivity and excitement for the holiday season by providing a user-friendly platform for coordinating the Secret Santa exchange.


## Introduction

Welcome to the Secret Santa Website, a platform designed to simplify and enhance the experience of organizing Secret Santa gift exchanges within our organization. The holiday season is a time for celebration, joy, and camaraderie, and the tradition of Secret Santa adds an extra layer of excitement to workplace festivities. However, coordinating Secret Santa events manually can be challenging and prone to errors, leading to confusion and frustration among participants.

Recognizing the need for a more efficient and user-friendly solution, we developed the Secret Santa Website to streamline the process of organizing and managing Secret Santa exchanges. Our goal is to provide a seamless experience for both administrators and participants, making it easy to sign up, manage gift assignments, and foster a sense of community spirit during the holiday season.

In this introduction, we'll explore the key features of the Secret Santa Website and how they contribute to making our office Christmas celebration more enjoyable and organized. Whether you're a small team or a large organization, our website is designed to meet your Secret Santa event management needs and enhance the festive atmosphere in your workplace. Let's discover how our platform can transform your holiday celebrations for the better.


## Identifying the Need

We noticed some problems during our past office Christmas celebrations, especially with organizing our Secret Santa gift exchange. Doing it manually caused confusion and made it hard to keep things fair for everyone. People often got mixed up about who they were supposed to give gifts to, which wasn't much fun.

[Rashmi Chaudhary](#), our team lead, saw these problems and realized we needed a better way to manage our Secret Santa event. She tasked the January intern with finding a solution to this issue, and everyone came up with their own ideas. Among them, Aman's idea was chosen, and this task was assigned to Aman, Aditi, and Irfan.

## Secret Santa Website Process

The Secret Santa Website facilitates various processes to ensure smooth operation and effective management of Secret Santa events within our organization. Here's a breakdown of each process:

### Admin Registration
1. **New admin visit the registration page:** New admins access the registration page to create an account.
2. **Provide necessary details:** Admins provide required information such as name, email, and password.
3. **Validate information:** The system validates the provided information.
4. **Create new admin account:** Upon successful validation, a new admin account is created.
5. **Admin directed to login page:** The admin is then redirected to the login page.

   ![Admin Registration](https://github.com/OurOrganization/SecretSanta/assets/162342704/af67a8f5-f85c-4316-a43d-6e762184bbde)

### Admin Login
1. **Admin enters login credentials:** Admins enter their registered email and password.
2. **Validate login credentials:** The system validates the entered credentials.
3. **Redirect to home page upon successful login:** Upon successful validation, admins are redirected to the home page.
   
   ![Admin Login](https://github.com/OurOrganization/SecretSanta/assets/162342704/9706c40c-8341-49e3-be1d-b336a5795b40)

### Home Page
1. **Choose from various options:** Admins can choose from various options available on the home page.

    ![Home Page](https://github.com/OurOrganization/SecretSanta/assets/162342704/62a658ee-6876-4d1b-9de6-f6317a9bc58d)

### QR Code Generation
1. **Admins access QR code generation:** Admins access the feature to generate QR codes.
2. **Generate QR code to become a Secret Santa:** QR codes are generated for each participant to become a Secret Santa.
3. **Save QR codes in a document file:** Generated QR codes are saved in a document file.
4. **Distribute QR codes to employees:** Admins distribute QR codes to employees.
5. **QR code button for each employee:** Each employee has a QR code button associated with their name.

   ![QR Code Generation](https://github.com/OurOrganization/SecretSanta/assets/162342704/8159bf15-563c-40ad-a85b-c14f3d50b061)

### Employee Management
1. **View/Add/Delete Employee List:** Admins can view, add, or delete employee details.
2. **Manage employee details:** Admins can manage employee details as needed.

    ![Employee Management](https://github.com/OurOrganization/SecretSanta/assets/162342704/914f1f03-7155-4c77-81d3-615f3cc81f97)

### Viewing Secret Santa Records
1. **View Secret Santa records:** Admins can view Secret Santa assignments.

   ![Secret Santa Records](https://github.com/OurOrganization/SecretSanta/assets/162342704/19e5a9bf-5138-4c85-b5e1-c159ffb04a0b)

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

# Testing with Selenium in Eclipse

To ensure the functionality and reliability of the Secret Santa Website, testing was conducted using Selenium WebDriver in the Eclipse IDE. Selenium WebDriver is a powerful tool for automating web browser interactions, making it suitable for testing web applications like the Secret Santa Website.

### Setting Up Selenium WebDriver Project in Eclipse:

1. **Install Eclipse**: Eclipse IDE for Java developers was used for this project.

2. **Create a New Java Project**: A new Java project was created in Eclipse to house the testing scripts.

3. **Download Selenium WebDriver JAR Files**: Selenium WebDriver Java language bindings (JAR files) were downloaded from the Selenium official website.

4. **Set Up the Project Build Path**: The Selenium WebDriver JAR files were added to the project's build path in Eclipse.

### Writing Test Scripts Using Selenium WebDriver:

1. **Create Test Classes**: Java classes were created in the Eclipse project to contain the test scripts. These classes were responsible for simulating user interactions with the Secret Santa Website.

2. **Import Selenium WebDriver Classes**: Necessary Selenium WebDriver classes were imported into the test classes to interact with web elements on the Secret Santa Website.

3. **Write Test Methods**: Test methods were written to perform specific actions on the Secret Santa Website, such as logging in, generating QR codes, and verifying user interactions.

4. **Execute Test Scripts**: Test scripts were executed from Eclipse by running the Java classes containing the test methods.

### Analyzing Test Results:

After executing the test scripts, the results were analyzed to ensure that the Secret Santa Website functioned as expected. Test cases were designed to cover various functionalities of the website, including user authentication, QR code generation, and email notifications.

By utilizing Selenium WebDriver in Eclipse, comprehensive testing of the Secret Santa Website was conducted to verify its functionality, reliability, and user experience.

## PlantUML of Secret Santa Website

![PlantUML](https://github.com/OurOrganization/SecretSanta/assets/162342704/9c4e9c4b-c8c2-4646-9a17-be54779b5530)

## Conclusion

In conclusion, the Secret Santa Website offers a comprehensive and user-friendly solution for organizing and managing Secret Santa gift exchanges within our organization. By leveraging modern technology and best practices in event management, our platform aims to streamline the entire process, from participant registration to gift distribution, while enhancing the overall experience for everyone involved.

With features such as easy signup, efficient gift assignment management, and transparent communication via email notifications, the Secret Santa Website ensures a seamless and enjoyable holiday celebration for all participants. Administrators can effortlessly oversee the event and ensure fairness, while participants can focus on the joy of giving and receiving gifts without the stress of organizational logistics.

Furthermore, the Secret Santa Website promotes inclusivity and fosters a sense of community spirit among colleagues, strengthening bonds and enhancing workplace morale during the festive season. By providing a centralized platform for coordinating Secret Santa exchanges, our website helps create memorable and meaningful experiences that bring people together and spread holiday cheer.

As we continue to enhance and improve the Secret Santa Website based on user feedback and evolving needs, we remain committed to making our office Christmas celebration a success year after year

