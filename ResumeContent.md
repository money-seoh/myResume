# Shubham

E-mail: thakurshubham546@hotmail.com &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; [LinkedIn](https://www.linkedin.com/in/shubham160893/) &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; [GitHub](https://GitHub.com/money-seoh) &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; Contact Number: +91-9459045707

## CAREER SUMMARY

Results-driven QA Automation professional with more than a decade of experience architecting scalable test frameworks and CI/CD pipelines for mission-critical enterprise domains. Technical expert in end-to-end automation utilizing Java, Selenium, RestAssured, and Cucumber BDD. An AI-forward innovator leveraging GitHub Copilot, Claude Code, and MCP servers to accelerate test generation, streamline code reviews, and drive delivery efficiency.

## TECHNICAL SKILLS

| Category                      | Skill Name                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------ |
| **Languages:**                | Java _(Proficient)_, TypeScript _(Proficient)_, C# _(Beginner)_, Elixir _(Beginner)_ |
| **Framework & Libraries:**    | Selenium, RestAssured, Apache HttpClient, Playwright, Phoenix (MVC)                  |
| **AI Tools**                  | GitHub Copilot, Antigravity, Claude Code                                             |
| **Tools:**                    | Maven, Gradle, Jenkins, Postman                                                      |
| **Version Control System**    | GitHub, GitLab, Bitbucket, Git                                                       |
| **Database:**                 | PostgreSQL, T-SQL, MySQL                                                             |
| **Project Management Tools:** | Jira, Redmine, Bugzilla, TestLink                                                    |

## CERTIFICATION CREDENTIALS

- [GitHub Foundation Certified (GH-900)](https://learn.microsoft.com/api/credentials/share/en-us/money-seoh/72E4DFBA8F38B07C?sharingId=A538976E4D9D4373)
- [GitHub Actions Certified (GH-200)](https://learn.microsoft.com/api/credentials/share/en-us/money-seoh/E92DB1F7C4A91CAE?sharingId=A538976E4D9D4373)
- [GitHub Copilot Certified (GH-300)](https://learn.microsoft.com/api/credentials/share/en-us/money-seoh/EAEB030C9B917126?sharingId=A538976E4D9D4373)
- [Postman API Fundamentals Student Expert certification](https://badges.parchment.com/public/assertions/oGj5_n5RQt6N4fmcQUI2oQ)
- [Google Cloud Certified Generative AI Leader (GCP-GAIL)](https://www.credly.com/badges/02d1ef55-e38b-4a82-a3c3-7b3d51786dea/public_url)
- [Microsoft Certified Azure Data Fundamentals (DP-900)](https://learn.microsoft.com/api/credentials/share/en-us/money-seoh/14591ED5300826C9?sharingId=A538976E4D9D4373)
- [Microsoft Certified Azure Fundamentals (AZ-900)](https://www.credly.com/badges/ecddac81-1891-4127-afab-7b0054e87a9f)

## EXPERIENCE

- **Tata Consultancy Services** - IT Analyst _(February 2022 - Present)_
- **Bebo Technologies Pvt. Ltd.** - Module Lead (Test Automation) _(October 2019 - February 2022)_
- **Watermark Insights India Pvt. Ltd.** - SDET _(September 2015 - October 2019)_

## PROJECTS

### Tata Consultancy Services

---

**<u>1. Capital Market - Investment Accounting _(January 2025 - Present)_</u>**

**Project Description:**

The project involves validating a mission-critical investment accounting platform that manages the complete front-to-back office trade lifecycle. Core operations focus on ensuring accurate daily portfolio valuation, automated processing of complex corporate actions such as dividend distributions. The system demands rigorous data integrity validation across diverse global asset classes—including equities, fixed income, derivatives, and money market funds—to guarantee regulatory compliance and seamless transaction reconciliation for high-volume capital market operations.

The project operates on an Agile methodology driven by two-week iterative sprints, encompassing standard ceremonies such as Sprint Planning, Demos, and Retrospectives. Jira serves as the primary tool for managing Epics, User Stories, and defect tracking, and is seamlessly integrated with the Xray app to oversee both functional and automated test suites. Confluence is leveraged to maintain vital project documentation, including application configurations and sprint burndown charts.

**App & Framework:**

An event-driven automation framework using Java and Cucumber (BDD) to validate a desktop-based application. Bypassing the untestable UI, the framework directly interacts with the application's backend by injecting and consuming Apache Kafka topics and events for critical workflows like portfolio creation and securities processing.

The architecture adapts Page Object Model (POM) principles to maintain Kafka message payloads, database connectors, utility classes, and validates Oracle SQL database records by utilizing Excel files for expected result assertions.

Integrated the automated test suite into a modern CI/CD pipeline, utilizing Jenkins for test execution and GitHub for source code management.

**AI-Led Automation Initiatives:**

Engineered multiple custom GitHub Copilot agents for automation framework. Here are details of few:

- Agent to generate and export cucumber test scripts into CSV format for Jira Xray upload.
- Agent to scaffold new test scripts automatically.
- Agent to validate and enforce cucumber format based coding guidelines in test script.
- Agent to validate and generate apache kafka messages by leveraging custom developed skills such as Portfolio.SKILL, FixedIncome.SKILL.
- Agent to perform code review based on custom instructions and internal organisation standards.

**_Impact_**:
Boosted overall automation efficiency by up to 40% by eliminating manual boilerplate, automating Jira Xray synchronization, instantly generating complex Kafka payloads, and enforcing strict code governance through automated Copilot code reviews.

**Responsibilities:**

- Led and mentored QA automation teams through end-to-end project lifecycles.
- Optimized engineering productivity by embedding GitHub Copilot into daily test development workflows.
- Collaborated with POs and BAs to define clear acceptance criteria and map test scenarios directly to UAT objectives.
- Oversee defect tracking and reporting processes to enhance communication, transparency, and timely issue resolution.
- Maintained codebase integrity through rigorous code reviews and PR management in Git/GitHub.
- Reported critical test metrics, automation coverage, and defect trends to cross-functional stakeholders to guide release decisions.
- Streamlined the onboarding of new engineers by conducting technical and domain-specific knowledge transfer sessions.

**<u>2. Capital Market - Alternative Investment _(February 2022 - December 2024)_</u>**

**Project Description:**

The project centers on a middle-office Alternative Investment platform designed to manage and track complex, non-traditional asset classes, including private equity, hedge funds, real estate, commodities, and venture capital. The system utilizes a dual-component architecture: a core web application for portfolio and asset record management, alongside an SSRS (SQL Server Reporting Services) application for downstream financial reporting and data extraction.

The project operates on an Agile methodology driven by two-week iterative sprints, encompassing standard ceremonies such as Sprint Planning, Demos, and Retrospectives. Jira serves as the primary tool for managing Epics, User Stories, and defect tracking, and is seamlessly integrated with the Xray app to oversee both functional and automated test suites. Confluence is leveraged to maintain vital project documentation, including application configurations and sprint burndown charts.

**App & Framework:**

An end-to-end Cucumber (BDD) automation framework was engineered from scratch using Java to validate workflows seamlessly across a Web UI, backend database tables, and an SSRS reporting portal.

The framework integrates Selenium WebDriver for robust browser automation and strictly adheres to the Page Object Model (POM) design pattern to maintain scalable page classes, utilities, and libraries. Apache Maven manages all project dependencies.

For assertion & validation , we leveraged Excel files to conduct complex, data-driven comparisons and backend database assertions. The entire suite is seamlessly integrated into a modern CI pipeline, utilizing Jenkins for automated test script execution enabling rapid feedback, and GitHub for source code management.

**Responsibilities:**

- Provided leadership and mentorship to test automation team members throughout all project phases.
- Created a robust automation test suite with Cucumber, Selenium, and Java to enhance testing efficiency.
- Conducted detailed code reviews and managed pull requests in GitHub, ensuring code quality and project standard compliance.
- Reported defects in Jira found during regression run.
- Presented key test results, coverage metrics, and defect trends to stakeholders in weekly meetings, facilitating informed decision-making.
- Collaborated with Product Owners, BA, and developers to define test scripts as per acceptance criteria.
- Facilitated knowledge transfer workshops to ensure smooth onboarding of new team members with comprehensive domain and project training.

---

### Bebo Technologies Pvt. Ltd.

---

**<u> Library Management System _(October 2019 - February 2022)_</u>**

**Project Description:**

The project is centered around developing and testing a comprehensive Library Management System designed to streamline operations such as book cataloging, user registration, book check-in/check-out, fine calculation, and inventory management. The application enables librarians and users to efficiently manage digital and physical book records, ensuring real-time updates across circulation, reservations, and membership activities.

**App & Framework:**

The project contains multiple modules maintained for web browser automation using Selenium WebDriver and API test automation using Apache HttpClient libraries in Java. As projects contain multiple modules, all the dependencies and automated execution are maintained using Gradle build scripts (multiproject build scripts).

The test script execution is automated using Jenkins spanned over multiple node agents (on daily basis as CI builds), and Selenium hub library is being used to execute the scripts across these agents on Firefox and Chrome browsers.

**Responsibilities:**

- Lead and mentor team members, providing guidance and support in resolving technical challenges.
- Collaborate with offshore teams to ensure seamless communication and project alignment.
- Oversee defect tracking and reporting processes to enhance communication, transparency, and timely issue resolution.
- Develop and maintain automated test scripts, contributing to regression testing efforts to identify and address software defects efficiently.
- Involved in prioritizing test scripts for automated testing.

---

### Watermark Insights India Pvt. Ltd.

---

**<u> Planning & Education Assessment System _(September 2015 - October 2019 )_</u>**

**Project Description:**

Provides solutions to stakeholders throughout the year to maintain their organizational goals and tracking updates on them and generating reports based on result.

**App & Framework:**

The project is MVC framework based on Elixir language which is a functional language. In the project, we help development team writing integration test scripts with ExUnit library. These test cases will be run during compile time and then on every commit using YAML-based CI/CD build scripts managed on GitLab.

UI automation was being done for only smoke test script using Selenium and TestNG libraries in Core Java. Maven was being used to resolve dependencies and project structure was based on Page Object Model (POM). The test script execution is being managed using Jenkins, and run-on daily basis with help of Jenkins.

**Responsibilities:**

- Improved test coverage by automating UI smoke tests using Selenium and TestNG in Java
- Writing integration test cases using ExUnit
- Involved in tracking design issues
- Effective defect tracking and reporting improving communications and reduce delays
- Logged defects using various tools like Jira, Redmine and Bugzilla
- Involved in regression testing to uncover breakages
- Involved in updating the requirements report

## ACADEMIC CREDENTIALs

**Professional Qualification:**

- B.Tech. (CSE) from Shoolini University, Solan (H.P.) with OCPA 7.14
- Diploma (CSE) from Govt. Polytechnic Kangra (H.P) with 62.83 %

**Qualification:**

- Senior Secondary from HP Board of School Education in Arts with 60.2%
- Matriculation from HP Board of School Education with 82.7%
