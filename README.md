# Cucumber Java in Eclipse

## Description
This repository contains sample Cucumber tests using Java and configured to run in Eclipse.

## Installation

### Prerequisites
- [Eclipse IDE](https://www.eclipse.org/downloads/)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Cucumber for Java](https://cucumber.io/docs/installation/java/)

### Setup
1. Clone this repository: `git clone https://github.com/nathan-rivera/CucumberJava.git
2. Open Eclipse IDE.
3. Import the project into Eclipse:
   - File -> Open Projects from File System...
   - Navigate to the cloned directory and select it.

## Running Tests
1. Open the project in Eclipse.
2. Navigate to the test file or feature file you want to run.
3. Right-click on the file.
4. Choose `Run As` > `Cucumber Feature`.

## Writing Tests
1. Create feature files in the `src/test/resources/features` directory.
2. Write Gherkin scenarios in these feature files.
3. Implement step definitions in Java in the `src/test/java/stepdefinitions` directory.

## Configuration
- Configure your test environment, such as WebDriver setup, in the appropriate classes before running tests.
- Modify the `src/test/resources` folder for configuration files, if necessary.

## Troubleshooting
- If you encounter issues with Cucumber setup or test execution, refer to the [Cucumber documentation](https://cucumber.io/docs) or community forums for assistance.

## Resources
- [Cucumber Documentation](https://cucumber.io/docs)
- [Cucumber for Java Documentation](https://cucumber.io/docs/installation/java/)
- [Eclipse IDE Documentation](https://www.eclipse.org/documentation/)

## Contributors
- [Your Name](https://github.com/nathan-rivera)
- Feel free to contribute by forking and creating pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README file to fit your specific project structure, additional configurations, or any other details relevant to your Cucumber Java project in Eclipse.
