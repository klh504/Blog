## Welcome to my GitHub page

I have linked [my repository](https://github.com/klh504/accessing-data-mysql) for you to view and will be discussing some of the content on this page.

I have worked to make this repository function and output information in JSON format. I will be making additional changes over the next few weeks to continually improve the functionality and aesthetics of the application.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### The Basic Information
- The application is written in Java
- The database is a mySQL database
- The application runs using Maven


### About the Application
- Springboot MVC was used to create this REST API which accesses data from a SQL database.
- The database is empty when the application is first created
- The controllers in the application contain functions to create, read, update, and delete items from the tables in the database. 
- Each controller corresponds to a different SQL table
- The data is sent by using CURL commands
- The data is output to the localhose URL in JSON format



### How the Application Works
- This application was built using a maven dependency. The application can be run by opening a console and entering the command: mvnw spring-boot:run
- The application can also be run by opening the files in a development environment and running the application
- CURL commands can be sent through a console
- The results of the CURL commands can be seen in the corresponding URL - either (http://localhost:8080/blogpost/allPosts) for blog information or (http://localhost:8080/demo/all) for login information.

