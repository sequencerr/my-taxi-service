# Awesome Taxi Service

Used 3-layer project architecture. Packaging into war using maven

### Features

- Authorization: login page (user creation), possibility to logout from any page. To register a user (driver in our case) you should visit `Add driver` page
- Authentication: implemented limit to access valuable pages for unauthorized users. (Using web filters)
- Getting and Updating information about current drivers, cars and their manufacturer

### Used Technologies
| Name                     | ver.   |
|--------------------------|--------|
| Tomcat                   | 9.0.69 |
| JavaServer Pages (JSP)   | -      |
| Servlets                 | 4.0.1  |
| JDBC                     | -      |
| PostgreSQL Server (win)  | 15.1   |
| JSTL for jsp tags        | 1.2    |
| mvn                      | 3.8.6  |
| jdk                      | 17.0.4 |

### Contribution / Running on your machine

1. Clone this repo
2. Execute `src/main/resources/init.db` to get actual database model
3. Configure the `ConnectionUtil`
4. Add tomcat configuration to run & test application
5. Don't forget to use `mvn clean verify package` before pushing!

## Database UML diagram
![img.png](uml.png)
