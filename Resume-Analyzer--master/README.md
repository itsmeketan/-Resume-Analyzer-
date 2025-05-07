# Resume Analyzer
Resume Analyzer is a Java-based web application that utilizes the Apache OpenNLP library for keyword extraction and matching against the contents of a resume PDF file. The application takes a resume PDF and a job description as inputs, and then extracts the text from the PDF file and identifies the relevant keywords from the job description using OpenNLP. It then calculates the percentage of matched keywords in the resume and identifies any unmatched keywords.

The project is designed to assist job seekers in ensuring that their resumes are optimized for applicant tracking systems (ATS) used by many employers. By identifying the relevant keywords from the job description, the application helps job seekers to tailor their resumes to meet the requirements of the specific job.

## Getting Started
### Prerequisites

To build and run the application, you will need:

- Java 17
- Apache Maven

## Installation:

- Clone this repository to your local machine
- Navigate to the project directory
- Run mvn package to build the application
- Run java -jar target/resumeatschecker.jar to start the application

## For Front end 
Before building this app save the index5.html file to your local machine.
Also adjust the port for front end into the controller accordingly so that there is no problem wrt CORS.
