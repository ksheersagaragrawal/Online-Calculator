# Online Calculator

This project is an Online Calculator implemented using Spring Boot and Gradle.

## IntelliJ IDEA Setup

### Installation

1. **Download IntelliJ IDEA Ultimate**: [Download Link](https://www.jetbrains.com/products/compare/?product=idea&product=idea-ce)
   - IntelliJ IDEA Ultimate provides advanced features, including full support for Spring framework.

2. **Install Required Plugins**:
   - Open IntelliJ IDEA.
   - Go to `File` -> `Settings` -> `Plugins`.
   - Search and install the following plugins:
     - KeypromoterX
     - AIXcODER
     - Spring Boot Helper (optional but useful for Spring Boot projects)

## Cloning the Repository

To clone the repository to your local machine, use the following command in your terminal:

```bash
git clone https://github.com/your-username/Online-Calculator.git
cd Online-Calculator
```

## Important Links

- **Project Structure Check**: [Watch Video](https://www.youtube.com/watch?v=Xx4kggKHXFE)
- **Annotations Check**: [Watch Video](https://www.youtube.com/watch?v=j5FtKEOlQ8Y)

## Running the Application

### Cleaning and Building

To clean the project, run:

```bash
./gradlew clean
```

To build the project, run:

```
./gradlew build
```

To run the Spring Boot application, use:
```
./gradlew bootRun
```

Once the application is running, open your web browser or use an API client (like Postman or curl) to access the endpoints:
```
http://localhost:8080/add?a=10&b=20
```

If you find anything missing when working through it, feel free to open a pull request.

