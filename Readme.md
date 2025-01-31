
**Test Automation Framework**

This is a Java-based Test Automation Framework designed for UI testing. 
The framework follows data-driven testing principles and integrates with LambdaTest for cloud execution. 
It supports headless execution for faster test runs and generates detailed Extent Reports along with Log4j logs.


## 🚀 About Me
Hi, My name is Sivasubramanian and i have 5+ years of experience in manual and automation testing using technology like Selenium webdriver.

My major expertise is in Java programming Language.


## Authors

- [@Siva14995](https://github.com/Siva14995)
- EmailAddress:k.r.sivasubramanian95@gmail.com




## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Siva14995)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sivasubramanian-k-r-12259825b/)



**Prerequisites**

Ensure you have the following installed:

- **Java 11** or later

- **Maven** (latest version recommended)
- Download link: https://maven.apache.org/download.cgi

- **TestNG** plugin (if using an IDE like IntelliJ or Eclipse)





**Features**
- **Data Driven Testing**: Using OpenCSV, Apache POI and Gson for reading test data from CSV and Excel file and JSON.
- **Cross-Browser Testing**: Supports running tests on different browsers.
- **Headless Mode** :Faster execution by running tests in headless mode.
- **Cloud Testing**: Integrated with LambdaTest to run tests on the cloud.
- **Logging**: Uses log4j for detailed logs.
- **Reporting**: Generates detailed reports using Extent Reports.

**Technologies & Libraries Used**
- Java 11 - Programming language
- TestNG - Test framework
- OpenCSV, Gson, Apache POI - Data-driven testing
- Faker - Fake data generation
- LambdaTest - Cloud-based test execution
- Maven Surefire Plugin - Running tests from the CLI
- Extent Reports - HTML test reports
- Log4j - Logging


## Setup Instructions

**Clone the repository:**

```bash
git clone https://github.com/Siva14995/Test-Automation-Framework.git
cd Test-Automation-Framework
```

**Reports & Logs**

**Test Execution Report**
- Generated using Extent Reports.
- Output: automationreport.html in the project root.
- Open the report in a browser for a detailed test summary.
**Logs**
- Logs are generated using Log4j.
- Output: logs/ directory.
- Check log files for debugging test failures.

**Integrated the project Github Actions**:
This automation framework is integrated with github actions.
The tests will be executed at 11:30PM IST every single day.

The reports will be archieved in gh-pages branch
You can view the html reports at: https://siva14995.github.io/Test-Automation-Framework/Automationreport.html
    
** Running Tests on LambdaTest**

```bash
  mvn test -Dbrowser=chrome -DisLambdatest=true -DisHeadless=false -X
```

** Running Tests on Chrome browser on Local Machine in Headless Mode**


```bash
  mvn test -Dbrowser=chrome -DisLambdatest=false -DisHeadless=true -X
```

