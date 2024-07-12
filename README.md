# Team-project-n1

purpose of our tool is:

Adoption Matching System: An AI system that analyzes the personality traits, behavior patterns, and preferences of animals in the shelter, along with potential adopters' profiles, to suggest ideal matches. This could increase the chances of successful adoptions.

Lost and Found Pet Recognition: Implementing image recognition AI to match lost pets with those in the shelter could reunite more animals with their owners.


TODO:
To implement a system where a person fills out a questionnaire to find a potential animal match from the shelter's database, a software engineer would need to follow these steps:

Design the Questionnaire: Create a form with questions that will help filter animals based on the adopter's preferences and circumstances. Typical questions might include:

Preferred species (dog, cat, etc.)
Preferred breed(s)
Age range
Gender preference
Any specific health requirements or restrictions
Activity level (high, moderate, low)
Environment (apartment, house with a yard, etc.)
Experience with pets
Backend Database: Use a relational database management system (RDBMS) like MySQL, PostgreSQL, or SQLite to store animal data. Ensure the database schema supports querying based on the questionnaire inputs.

Frontend Form: Create a user interface (UI) for the questionnaire using HTML, CSS, and JavaScript (or frameworks like React, Angular, Vue.js).

API Development: Develop an API to handle form submissions and query the database. This can be done using a backend framework like Express.js (Node.js), Django (Python), or Spring Boot (Java).

Query Logic: Write SQL queries or use an ORM (Object-Relational Mapping) to filter animals based on the inputs from the questionnaire.

Result Presentation: Display the list of potential matches to the user in a user-friendly manner.
