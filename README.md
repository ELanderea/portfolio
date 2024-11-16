# My Software Development Portfolio

Welcome to my portfolio repository! Here, you can explore a curated selection of my projects across various areas of software development.

## Featured Projects

### 1. [Bechdel Film App](https://github.com/ELanderea/BechdelFilmApp)

**Overview:**
A feature-rich application designed to provide film information and recommendations, integrating data from The Movie Database (TMDB) and the Bechdel Test API. The app assesses films based on the Bechdel Test, highlighting gender representation in cinema and enabling users to discover movies that meet specific criteria.

**Key Highlights:**
- **Bechdel Test Analysis**: Check if a film passes the Bechdel Test, scoring from 0 to 3.
- **Crew Gender Details**: Identify the gender of film directors and composers.
- **Dynamic Recommendations**:
  - **By Year**: Retrieve movies released in a specific year or decade.
  - **By Genre**: Find films within a chosen genre.
  - **By Actress**: Discover movies featuring a specific actress.
  - **Random Picks**: Receive random movie suggestions that pass the Bechdel Test.
- **Interactive CLI**: The user interface in main.py provides a seamless way to interact with the API and explore film data.

**Core Functionalities:**
- **Modular Architecture**: Separate modules for database connections, API handling, and data processing ensure maintainability.
- **Caching & Performance**: Uses caching for efficient repeated data retrieval.
- **Error Handling**: Integrated to manage potential API call failures gracefully.

**API Endpoints**:
- Integrated TMDB and Bechdel Test API to provide comprehensive film data.

**User Flow**:
- **Explore Film Data**: Check if a film passes the Bechdel Test and view director/composer gender details.
- **Get Recommendations**: By year, genre, actress, or randomly.
- 
- **Potential Enhancements**:
  - Add TV series support.
  - Expand with runtime and director-specific filters.
  - Introduce a GUI for enhanced user experience.

**Technologies Used**: Python, Flask, TMDB API, Bechdel Test API.

### 2. [Music School Booking System](https://github.com/ELanderea/BookingSystem)

**Overview:**
An API-driven booking system designed for music schools, facilitating seamless scheduling between students and teachers. This project simulates the pre-term process where students with unique IDs view available teachers, check their schedules, and book their first lessons.

**Key Highlights:**
- **Database Structure**: A robust, normalized schema (musicschool.sql) with students, teachers, and bookings tables for optimized data management.
- **Modular Codebase**: Core operations encapsulated in db_utils.py for maintainability and ease of scalability.
- **RESTful API**: Developed with Flask in app.py, enabling CRUD operations for student-teacher interactions.
- **Client Interface**: main.py simulates user actions such as viewing teacher lists, checking availability, and making bookings.

**Core Functionalities:**
- **Database Operations**: Functions for connecting to the database, retrieving teacher data, checking schedules, and creating bookings.
- **Error Handling**: Integrated for reliability.
- **API Endpoints**:
  - /teachers/<instrument>: Get teachers for a specific instrument.
  - /availability/<teacher_id>: Check a teacher's availability.
  - /booking/<student_id> (PUT): Book a lesson.

- **User Simulation**: Demonstrates practical use cases and API interactions.
  
**Potential Enhancements**:
- Implement booking history for students.
- Add options to cancel or modify bookings.
- Generate teacher payslips based on completed lessons.

**Technologies Used**: Python, Flask, MySQL.


## Connect with Me
If you would like to connect then please get in touch via my LinkedIn profile below, or email me directly. 
- **LinkedIn**: [My LinkedIn Profile](https://www.linkedin.com/in/emerlanders)
- **Email**: [Email](mailto:emerlanders@gmail.com)

