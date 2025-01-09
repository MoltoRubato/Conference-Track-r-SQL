# DBS_SQL

# Conference Track-r - INFO20003 A2 S1 2024

## Overview
Conference Track-r is a platform designed to track academic conferences, paper submissions, and researcher activities. It manages data about conferences, tracks, sessions, researchers, and papers, including submissions, reviews, presentations, and author-supervisor relationships.

## Key Features
- **Conferences**: Tracks event details such as location, dates, and session organization.
- **Tracks**: Each conference has multiple tracks with paper submission guidelines.
- **Sessions**: Each track contains sessions for paper presentations, with time allocated for each paper.
- **Researchers**: Manages researcher data, including their supervision relationships and attended conferences.
- **Papers**: Tracks paper submissions, their review outcomes, and assigned sessions for presentation.

## Database Model
The system uses an ER model to define relationships between conferences, tracks, researchers, papers, and sessions. The schema supports complex queries about researcher activities, paper submissions, and conference statistics.

## Setup
1. Download and set up the provided dataset `conference_2024.sql` from the Canvas assignment link.
2. Import the dataset into MySQL using MySQL Workbench or any compatible SQL tool.
3. Ensure the `ONLY_FULL_GROUP_BY` mode is enabled for query correctness.

## Assignment Task
Write SQL queries to solve 10 questions, each focusing on different aspects of the system, such as:
- Counting attended researchers for each conference.
- Identifying the researcher with the most "unique" conferences attended.
- Analyzing paper acceptance and rejection statistics.
- Finding relationships between researchers and their influences.

## Contributors
- Ryan Huang
- University of Melbourne INFO20003 Teaching Team

## License
This project is for academic purposes under the University of Melbourne's INFO20003 Database Systems course.
