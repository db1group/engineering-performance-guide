# **Engineering Performance Guide Manifest (EPG)**
This guide is a DB1 Group's initiative that enables your team and/or business unit to measure the maturity of your software engineering. The evaluation model is simple, straightforward and has the intention to give you insights about where your technical strengths and weaknesses are so you can work on them. 

This guide is meant to companies that understands the value of a healthy software engineering structure and how that impacts the business. 

# **How does it work ?**

EPG will provide you two engineering pilars:

## **Processes**

The process pilar will provide you information of how your team works and how adhearent they are to modern market practices. You'll need a technical person to guide this evaluation.

## **Metrics**

The metrics pilar will rely on modern tools to provide both quality and security code   metrics. Despite the initial workload to set things up, when it's running all you need is to work on the collected metrics.

-------------------

## **Premises**

* Implementation of the EPG will require a lead engineer or an engineer manager (or any capable engineer available)
* To get the most benefit from the EPG, link the work and goals of technical managers to the indicators in the guide

-------------------

## **Indicators**

The **EPG** implementation will provide you indicators. Indicators are measurable result guides to benchmark with other teams and yourself.

We separate indicators into 3 categories:

- ### **Strategic**
    high-level indicators to support your high-level decision making. Bring these to approach your board and executive level.
- ### **Tactical**
    mid-level indicators that will allow your tactical areas to set healthy and unhealthy engineering technical levels. This indicator level is meant to coordinators, engineer managers and lead engineers.
- ### **Operational**
    low-level indicators that will tell your operational team if their work is performing or not at a good level of excellence. This category is recommended for the engineering team such as: developers, qa, devops

|**Category**|**Indicator**|**Name**|**Description**|
|------------|---------------|-------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Strategic](#strategic), <br> [Tactical](#tactical) | [**EMPA**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/strategic/EMPA.md)           | Engineering Maturity Panel Adoption | This indicator measures how many % of the projects are technically visible, that is, they are being monitored within the engineering performance guide            |
| [Strategic](#strategic), <br> [Tactical](#tactical) | [**TRA**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/strategic/TRA.md)            | Technical Responsibility Adherence  | This indicator measures adherence to the premise where every project must have at least 1 technical person (lead engineer or engineer manager)                    |
| [Strategic](#strategic) | [**EML**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/strategic/EML.md)           | Engineering Maturity Level          | This indicator measures the average engineering maturity level of projects, using the following criteria: 3- Optimal; 2- Managed; 1- Standard; 0- Unmapped/Chaos. |
| [Tactical](#tactical), <br> [Operational](#operational) | [**EPH**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EPH.md)           | Engineering Process Health          | This indicator measures the adherence to development process best practices recommended by the EPG |
| [Tactical](#tactical) | [**EMH**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/tactical/EMH.md)           | Engineering Metrics Health          | This indicator represents the average engineering metrics value |
| [Operational](#operational) | [**CC**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/CodeCoverage.md)           | Code Coverage          | Code coverage is a software testing metric that determines the number of lines of code that is successfully validated under a test procedure |
| [Operational](#operational) | [**Maintainability**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/Maintainability.md)           | Maintainability          | Rating given to a project related to the value of the Technical Debt Ratio (Ratio between the cost to develop the software and the cost to fix it) |
| [Operational](#operational) | [**DD**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/DuplicationDensity.md)           | Duplication Density          | Number of duplicated blocks of lines |
| [Operational](#operational) | [**Reliability**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/Reliability.md)           | Reliability          | Number of bug issues |
| [Operational](#operational) | [**Security Rating**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/SecurityRating.md)           | Security Rating          | Security Rating(security_rating)<br>A = 0 Vulnerabilities<br>B = at least 1 Minor Vulnerability<br>C = at least 1 Major Vulnerability<br>D = at least 1 Critical Vulnerability<br>E = at least 1 Blocker Vulnerability |
| [Operational](#operational) | [**Security Review**](https://github.com/db1group/engineering-performance-guide/tree/main/indicators/operational/SecurityReview.md)           | Security Review          | The Security Review Rating is a letter grade based on the percentage of Reviewed Security Hotspots.<br>A = >= 80%<br>B = >= 70% and <80%<br>C = >= 50% and <70%<br>D = >= 30% and <50%<br>E = < 30% |

# Contributing
EPG is the work of all DB1 Group's business units. We appreciate your help!

To contribute, please read the contribution guidelines at [contributing guide](https://github.com/db1group/engineering-performance-guide/CONTRIBUTING.md)