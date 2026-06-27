# CS 320 Software Test Automation and QA Portfolio

## Project Overview

This repository contains my work from CS 320 Software Test Automation and QA. The projects focused on creating service classes and unit tests for different software components, including contact, task, and appointment services. Each project required me to follow specific software requirements, apply validation rules, and write tests to confirm that the program behaved correctly.

The main goal of this portfolio is to show how I approached software testing, user requirements, and software design. These projects helped me practice writing functional code, creating meaningful tests, and thinking about how software should behave when users enter valid or invalid information.

## Reflection

### How can I ensure that my code, program, or software is functional and secure?

I can ensure that my code is functional and secure by carefully reviewing the requirements before writing the program, then creating tests that confirm each requirement is met. In these projects, I used unit testing to check that the contact, task, and appointment services handled valid inputs correctly and rejected invalid inputs. For example, I tested required fields, length limits, unique IDs, and dates to make sure the program followed the rules provided in the project guidelines.

To make software more secure, I also need to think about how the program handles unexpected or incorrect input. A program should not accept data that breaks the requirements, and it should fail safely when something is wrong. Writing tests for edge cases, such as null values, empty strings, fields that are too long, or invalid dates, helps reduce the chance of defects reaching the user. Testing does not guarantee that software is perfect, but it helps improve reliability and gives more confidence that the program works as expected.

### How do I interpret user needs and incorporate them into a program?

I interpret user needs by reading the requirements carefully and turning them into specific program behaviors. In these projects, each requirement described what the user should or should not be allowed to do. For example, the program needed to prevent invalid contact information, tasks with missing details, or appointments scheduled in the past. I translated those needs into validation rules inside the code and then created tests to confirm that the rules worked.

As a QA-focused developer, I also try to think beyond the basic requirements and consider how a real user might interact with the program. Users may enter incomplete information, make mistakes, or try values that were not expected. By thinking about those situations, I can design better tests and help ensure the program supports the user while still protecting the system from bad data.

### How do I approach designing software?

My approach to designing software starts with understanding the requirements and breaking the problem into smaller parts. For these projects, I separated the program into model classes and service classes. The model classes stored the data, while the service classes handled actions such as adding, updating, and deleting records. This made the program easier to understand, test, and maintain.

I also approach software design by thinking about testability. If the code is organized clearly, it becomes easier to write unit tests and easier to identify where a defect might be located. I try to keep methods focused on one responsibility, use validation to protect the data, and write tests that prove each important behavior. This process helps create software that is not only functional but also easier to update in the future.

## What I Learned

Through these projects, I learned that testing is an important part of the software development process, not something that should only happen at the end. Writing tests helped me better understand the requirements and identify possible issues early. I also learned that clear requirements, organized code, and strong validation are important for creating reliable software.

This course helped me strengthen my understanding of how software quality is built through both development and testing. In future projects, I will continue using unit tests, requirement analysis, and edge case testing to improve the quality and reliability of my code.
