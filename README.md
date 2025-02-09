<!DOCTYPE html>
<html>
<head>
</head>
<body>
  <h1>Selenium Cucumber Automation Testing Exercise</h1>

  <p>This project contains software automation testing exercises inspired by the test cases <a href="https://www.nba.com/warriors/"></a>.</p>

  <h2>Project Details</h2>

  <ul>
    <li>Language: Java</li>
    <li>Frameworks and Libraries:
      <ul>
        <li>Selenium: A powerful web automation tool</li>
        <li>Cucumber: A behavior-driven development (BDD) framework</li>
        <li>Gherkin Language: A business-readable domain-specific language for specifying test cases</li>
        <li>TestNG: A testing framework for Java</li>
      </ul>
    </li>
  </ul>

  <h2>Usage</h2>

  <p>To use this project, follow the steps below:</p>

  <ol>
    <li>Clone the repository:
    <pre><code>git clone https://github.com/jtidake/CucumberMiniProject.git</code></pre>
    </li>
    <li>Open the project in your preferred Java IDE.
    </li>
    <li>install the necessary dependencies:
        <pre><code>mvn install</code></pre>
    </li>
   <li>Run the tests using the test runner class:
       <pre><code>mvn test</code></pre>
   </li>
<li>Framewrok Architecture
       <pre><code>cucumberMiniProject/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com.myProject.businessLogic/  # Business Logic (e.g., data operations, report generation)
│   │   │   │   ├── JacketDetailsWriter.java
│   │   │   │   └── ReportUtils.java
│   │   │   ├── com.myProject.pages/          # Page Objects (represents web pages)
│   │   │   │   ├── BasePage.java
│   │   │   │   ├── ProductPage.java
│   │   │   │   └── VideoFeedPage.java
│   │   │   ├── com.myProject.utilities/      # Utility classes (browser configuration, drivers, etc.)
│   │   │   │   ├── BrowserUtils.java
│   │   │   │   ├── ConfigurationReader.java
│   │   │   │   └── Driver.java
│   │   ├── resources/                        # Resources (Log4j configuration, etc.)
│   │   │   └── log4j2.xml
│   │   
│   ├── test/
│   │   ├── java/
│   │   │   ├── com.myProject.runners/        # Cucumber test runners
│   │   │   │   └── Runner.java
│   │   │   ├── com.myProject.stepDefinitions/  # Step Definitions (map Gherkin steps to code)
│   │   │   │   ├── Hooks.java
│   │   │   │   ├── ShopPage_StepDefs.java
│   │   │   │   └── VideoFeedSteps.java
│   │   ├── resources/                        # Cucumber feature files
│   │   │   ├── features/                     # Feature files (Gherkin syntax)
│   │   │   │   ├── shop.feature
│   │   │   │   └── videoFeed.feature
│   │   │                       
├── .gitignore                                # Git ignore file for ignoring unnecessary files (e.g., target, logs, etc.)
├── pom.xml                                   # Maven build file
└── README.md                                 # Project README file

</code></pre>
   </li>
  </ol>

  <h2>Report</h2>
  <p>A detailed report of the test results can be found in the project. The report includes information such as test case status, execution time, and any failures or errors encountered during the tests.</p>

</body>
</html>
