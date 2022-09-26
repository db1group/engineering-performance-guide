# **Engineering Performance Guide Manifest (EPG)**
This guide is a DB1 Group's initiative that enables your team and/or business unit to measure the maturity of your software engineering. The evaluation model is simple, straightforward and has the intention to give you insights about where your technical strengths and weaknesses are so you can work on them. 

This guide is meant to companies that understands the value of a healthy software engineering structure and how that impacts the business. 

-------------------

### **Premises**

* Implementation of the EPG will require a lead engineer or an engineer manager (or any capable engineer available)
* To get the most benefit from the EPG, link the work and goals of technical managers to the indicators in the guide

-------------------

## **How does it work ?**

This guide will provide you two engineering pilars: process and code metrics.

Both pilars will help you understand how to connect your tactical and operational teams work to your strategic goals. The EPG connects to the Business Performance Guide (BPG) adding more technical tools to track and monitor your improvements on engineering.

### **Processes**

The process pilar will provide you information of how your team works and how adhearent they are to modern market practices. You'll need a technical person to guide this evaluation.

### **Metrics**

The metrics pilar will rely on modern tools to provide both quality and security code metrics. Despite the initial workload to set things up, when it's running all you need is to work on the collected metrics.

-------------------

## **Indicators**

The **EPG** implementation will provide you indicators. Indicators are measurable result guides to benchmark with other teams and yourself.

We split indicators into 3 levels:

- ### **Strategic**
    high-level indicators to support your high-level decision making. Bring these to approach your board and executive level.
- ### **Tactical**
    mid-level indicators that will allow your tactical areas to monitor their technical action plans and show their impact on the strategic level. This indicator level is meant to coordinators, engineer managers and lead engineers.
- ### **Operational**
    low-level indicators that will tell your operational team if their work is performing or not at a good level of excellence. This category is recommended for the engineering team such as: developers, qa, devops

In addition to the 3 levels, the indicators can also be divided into 3 categories:

- ### **Code Metric**
    A static analysis of the code base to evaluate on technical criteria, its quality. In addition, code metrics can help us anticipate bugs, create mandatory quality criteria, as well as protect code against some security vulnerabilities.
- ### **Process**
    In a simple and direct way, measure the implementation of best practices recommended for the programmer and his engineering team in the development process.
- ### **Business**    
    Indicators that directly impact the business: whether in productivity, engineering efficiency, customer perceived quality or delivery assertiveness
     
<br>

|**Level**|**Category**|**Indicator**|**Name**
|---------|------------|-------------|--------
| [Operational](#operational) | [Code Metric](#code-metric) | [**Code Coverage**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-9)           | Code coverage is a software testing metric that determines the number of lines of code that is successfully validated under a test procedure |
| [Operational](#operational) | [Code Metric](#code-metric) | [**Maintainability**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-4)           | Rating given to a project related to the value of the Technical Debt Ratio (Ratio between the cost to develop the software and the cost to fix it) |
| [Operational](#operational) | [Code Metric](#code-metric) | [**Duplication Density**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-2)            | Number of duplicated blocks of lines |
| [Operational](#operational) | [Code Metric](#code-metric) | [**Reliability**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-6)            | Number of bug issues |
| [Operational](#operational) | [Code Metric](#code-metric) | [**Security Rating**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-7)                | Security Rating<br>A = 0 Vulnerabilities<br>B = at least 1 Minor Vulnerability<br>C = at least 1 Major Vulnerability<br>D = at least 1 Critical Vulnerability<br>E = at least 1 Blocker Vulnerability |
| [Operational](#operational) | [Code Metric](#code-metric) | [**Security Review**](https://docs.sonarqube.org/latest/user-guide/metric-definitions/#header-7)             | The Security Review Rating is a letter grade based on the percentage of Reviewed Security Hotspots.<br>A = >= 80%<br>B = >= 70% and <80%<br>C = >= 50% and <70%<br>D = >= 30% and <50%<br>E = < 30% |
| [Tactical](#tactical), <br> [Operational](#operational) | [Process](#process) | [**Engineering Process Health (EPH)**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EPH.md)           | This indicator measures the adherence to development process best practices recommended by the EPG |
| [Tactical](#tactical), <br> [Operational](#operational) | [Code Metric](#code-metric) | [**Engineering Metrics Health (EMH)**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EMH.md)           | This indicator represents the average engineering code metrics value |
| [Tactical](#tactical) | [Process](#process) | [**Engineering Maturity Panel Adoption (EMPA)**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EMPA.md)       | This indicator measures how many % of the projects are technically visible, that is, they are being monitored within the engineering performance guide            |
| [Tactical](#tactical) | [Process](#process) | [**Technical Responsibility Adherence (TRA)**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/TRA.md)           | This indicator measures adherence to the premise where every project must have at least 1 technical person (lead engineer or engineer manager)                    |
| [Tactical](#tactical), <br> [Strategic](#strategic) | [Code Metric](#code-metric)<br> [Process](#process) | [**Engineering Maturity Level (EML)**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EML.md)             | This indicator measures the average engineering maturity level of projects, using the following criteria:<br>3- Optimal;<br>2- Managed;<br>1- Standard;<br>0- Unmapped/Chaos. |
| [Strategic](#strategic) | [Business](#business) | [**Delivery Cost/Throughput**](https://db1global.sharepoint.com/:b:/s/db1_documents/EbmFZtQTULpHsCsvagtYHSQB-R9LEIE-3dTjcPamvrSjVg?e=N4VoTb)             | This indicator measures the total cost of an engineering team by the number of deliveries made by it |
| [Strategic](#strategic) | [Business](#business) |  [**Performance**](https://db1global.sharepoint.com/:b:/s/db1_documents/EbmFZtQTULpHsCsvagtYHSQB-R9LEIE-3dTjcPamvrSjVg?e=N4VoTb)       | This indicator shows how your team's time is spent |
| [Strategic](#strategic) | [Business](#business) |  [**Effort**](https://db1global.sharepoint.com/:b:/s/db1_documents/EbmFZtQTULpHsCsvagtYHSQB-R9LEIE-3dTjcPamvrSjVg?e=N4VoTb)         | This indicator shows how your team's time is spent in a more granular level |
| [Strategic](#strategic) | [Business](#business) | [**On-Time Delivery**](https://db1global.sharepoint.com/:b:/s/db1_documents/EbmFZtQTULpHsCsvagtYHSQB-R9LEIE-3dTjcPamvrSjVg?e=N4VoTb)    | This indicator measures how effective you were in meeting the deadlines of commitments agreed with customers |
| [Strategic](#strategic) | [Business](#business) | [**Delivery Satisfaction**](https://db1global.sharepoint.com/:b:/s/db1_documents/EbmFZtQTULpHsCsvagtYHSQB-R9LEIE-3dTjcPamvrSjVg?e=N4VoTb)       | This indicator measures the number of deliveries made as well as the rate of deliveries evaluated in a period  |

# Contributing
EPG is the work of all DB1 Group's business units. We appreciate your help!

To contribute, please read the contribution guidelines at [contributing guide](https://github.com/db1group/engineering-performance-guide/CONTRIBUTING.md)