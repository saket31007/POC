The ReMeDi Automation Framework is a TestNG-based testing solution designed for the ReMeDi application. This framework facilitates efficient and effective automated testing of the application, ensuring high-quality releases with minimal manual intervention.

Features
Modular Test Design: Easily add and manage test cases in a structured manner.
Data-Driven Testing: Support for parameterized tests to handle various input data.
Reporting: Generates detailed HTML reports for test execution results.
Parallel Execution: Run tests concurrently to reduce execution time.
Integration: Seamless integration with CI/CD pipelines like Jenkins.
Prerequisites
Java JDK: Version 8 or above.
Maven: Version 3.6 or above.
TestNG: Included as a dependency in the project.
IDE: Any Java IDE (e.g., IntelliJ IDEA, Eclipse).

Running Tests
From the Command Line
To run all tests:

bash
Copy code
mvn test
From an IDE
Open the project in your preferred IDE.
Right-click on the test class or method and select "Run".
Running Specific Tests
To run a specific test class:

bash
Copy code
mvn -Dtest=YourTestClass test
TestNG Configuration
The TestNG XML file (testng.xml) is located in the root directory. You can modify this file to include or exclude specific test classes and suites as needed.

Reporting
After test execution, reports can be found in the target/surefire-reports directory. Open index.html in a web browser to view detailed results.

Continuous Integration
Integrate this framework into your CI/CD pipeline by configuring your build tool (e.g., Jenkins) to execute the mvn test command as part of the build process.

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Make your changes and commit them (git commit -m 'Add your feature').
Push to the branch (git push origin feature/YourFeature).
Create a pull request.
