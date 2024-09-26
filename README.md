# TodoList

This project is a **Java Spring Boot** application using **Java 21** and **Maven**. The goal of this project is to create a task manager in the same style as Trello, the project serves as a study project.


## Prerequisites
Make sure you have the following software installed:

### 1. Java 21 (JDK)

#### Install on Linux (Debian/Ubuntu):

```bash
sudo apt update
sudo apt install openjdk-21-jdk
```

#### Install on Windows:

- Download the JDK from the official website.
- Follow the installation instructions.

### 2. Maven 3.6.3 or higher

#### Install on Linux (Debian/Ubuntu):
```bash
sudo apt update
sudo apt install maven
```

#### Install on Windows:
- Download the Maven zip file from: [Download Maven](https://maven.apache.org/download.cgi).
- Extract the contents of the file to a directory of your choice.
- Add the Maven bin directory path to the environment variables.

### Verifying the Installations

- Check the Java version:
  ```bash
  java -version
    ```

It should return something like java 21.
- Check the Maven version:
```bash
    mvn -v
```
It should return something like Apache Maven 3.6.3 or higher.

## How to Run the Project
### 1. Clone the Repository

- Clone this repository to your local machine:

```bash
  git clone https://github.com/ViniciusDuranteBagio/TodoList.git
  cd TodoList
```

### 2. Run the Application

- You can run the application directly using Maven with the following command:

```bash
  mvn spring-boot:run
```
### 3. Build the Project

- If you want to generate a .jar file for distribution, run the following command to build the project:

```bash
  mvn clean install
```

The generated .jar file will be available in the target/ folder.



