![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

# "Online Movie Archive System"

## Project Description:
It is a project to create an “Online Movie Archive System” database for a community of movie lovers. This system should enable the storage and management of information about movies and enable users to view information about movies.

## Requirements:
The system should have the following features:

**1.Movie Information:** 
For each movie, the following information should be stored:

**2.Directors:** 
Each movie is directed by a director. The following information about directors should be stored:

**3.Users:** 
Registered users should be able to view movie information and leave comments. The following user information should be stored:

**4.Movie Comments:** 
Registered users should be able to comment on movies. Each comment should include the following information:

## Directors Table

| Column Name   | Description     |
|---------------|-----------------|
| director_id   | Director ID     |
| movie_id      | Movie ID        |
| director_name | Director Name   |
| birth_year    | Birth Year      |

## Movies Table

| Column Name   | Description     |
|---------------|-----------------|
| movie_id      | Movie ID        |
| movie_title   | Movie Title     |
| release_year  | Movie Release Date   |
| director_id   | Director ID     |
| genre         | Movie Genre     |
| imdb_rating   | Movie Rating    |

## Users Table

| Column Name   | Description     |
|---------------|-----------------|
| user_id       | User ID         |
| username      | Username        |
| email         | User Mail       |
| password      | User Password   |

## Comments Table

| Column Name   | Description     |
|---------------|-----------------|
| comment_id    | Comment ID      |
| movie_id      | Movie ID        |
| user_id       | User ID         |
| comment_date  |  Movie Comment Date    |
| comment_content  | Movie comments      |

## Dependencies
- MySQL Server

## Usage
 - MySQL
 - Open the MySQL Workbench or DBeaver and connect to your MySQL server.
 - Navigate to the MySQL directory in the repository.
 - Run the SQL scripts to create and manipulate databases.


##  Contributors

 [Onur Girgin](https://github.com/Mednasa) | QA Automation Engineer


 ##  License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
