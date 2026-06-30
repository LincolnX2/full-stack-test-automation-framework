# QA-Automation-Portfolio

🧪 Yinus Sabur – QA Automation Portfolio
QA Automation Engineer | Selenium | Cypress | Cucumber (BDD) | Postman | k6 | JMeter | SQL | CI/CD

"Building world-class test automation frameworks to enable continuous delivery of high-quality code."

📍 Based in South Africa (Remote / On-site)
📧 sabur.yinus@gmail.com | 🔗 LinkedIn | 🐙 GitHub

📌 About Me
I am a QA Automation Engineer with 2+ years of remote freelance experience in front-end and back-end test automation, plus 10+ years of disciplined QA/QC experience from Huawei telecommunications projects. I help engineering teams ship high-quality code faster by building robust automation frameworks, integrating CI/CD pipelines, and fostering an automation-first culture.

Currently seeking: Roles in QA Automation Engineering (junior/mid-level) that value Selenium, Cypress, Cucumber (BDD), Postman, k6, JMeter, SQL, and CI/CD pipelines.

🛠️ Tech Stack & Tools (What I Know)
Category	Tools / Technologies
Languages	C#, .NET, Java, SQL
UI Automation	Selenium WebDriver, Cypress
BDD	Cucumber (Gherkin)
API Testing	Postman, REST API
Performance Testing	k6, JMeter
CI/CD & DevOps	Azure DevOps / Jenkins, CI/CD Pipelines, Git
Test Management	Azure Test Plans / Jira
Databases	SQL (MySQL, PostgreSQL, SQL Server)
IDEs	Visual Studio, VS Code, IntelliJ
📂 Projects
Below are automation projects I completed during freelance work and personal upskilling.

1. 🧪 E-Commerce Regression Suite – Selenium + C# + NUnit
Tech: Selenium WebDriver, C#, NUnit, ExtentReports
Description:
Automated 50+ critical test cases for an e-commerce web app (login, cart, checkout, order history). Integrated with CI/CD pipeline to run on every push.

Key achievements:

Reduced regression test time by 40%

Achieved 95% test pass rate

Added parallel execution support

🔗 Repository Link (add your actual link)

2. 🎭 Modern Web Testing – Cypress + JavaScript
Tech: Cypress, JavaScript, Mocha
Description:
Built a fast, reliable automation suite for a modern Single Page Application (SPA). Tests cover user journeys, form submissions, and dynamic content loading.

Key achievements:

3x faster execution than Selenium on same app

Built custom Cypress commands for reusable actions

Added video recording and screenshots on failure

🔗 Repository Link

3. 🥒 BDD Framework – Selenium + Cucumber + Java
Tech: Selenium, Cucumber (Gherkin), Java, JUnit
Description:
Created a Behavior Driven Development (BDD) framework where test scenarios are written in plain English Gherkin. Non-technical stakeholders can read and contribute.

Sample Feature File:

gherkin
Feature: User Login
  Scenario: Successful login with valid credentials
    Given User is on login page
    When User enters valid username and password
    Then User should see dashboard
Key achievements:

Bridged communication gap between product and dev teams

Reduced flaky tests by 25%

🔗 Repository Link

4. 🔌 API Test Suite – Postman + Newman + CI/CD
Tech: Postman, Newman, CI/CD (Azure DevOps/Jenkins)
Description:
Created 40+ automated API tests for a CRUD application (users, orders, products). Integrated with CI/CD pipeline for daily execution.

Key achievements:

Caught 3 production-breaking API contract changes before release

Reduced manual API testing effort by 70%

Generated HTML reports with Newman

🔗 Repository Link

5. ⚡ Performance Testing – k6 & JMeter
Tech: k6 (JavaScript), JMeter (Java), CI/CD
Description:
Simulated high user loads on REST APIs and web applications to identify bottlenecks and ensure stability under pressure.

k6 Project:

Simulated 500+ concurrent users on login API

Measured response time (p95, p99) and error rate

Exported results to CSV for stakeholder reports

JMeter Project:

Created thread groups for 1000+ users

Added assertions, listeners, and distributed testing setup

Identified memory leak at 600 concurrent users

Key achievements:

Found critical bottleneck fixed before production release

Reduced average response time by 30% after recommendations

🔗 k6 Repository Link | 🔗 JMeter Repository Link

6. 🗄️ SQL Test Data Setup & Validation
Tech: SQL (MySQL, SQL Server), DBeaver (optional), Azure Data Studio
Description:
Wrote complex SQL queries to seed test data, validate post-API call database state, and clean up between test runs.

Example queries included:

Insert test users with specific roles

Validate foreign key relationships after POST request

Delete test data after test completion

Join queries to verify order ↔ customer mapping

🔗 Repository Link

7. 🔄 CI/CD Pipeline Integration (Azure DevOps / Jenkins)
Tech: Azure DevOps Pipelines / Jenkins, Git, YAML
Description:
Integrated all automation suites into CI/CD pipelines to run automatically on every code push or nightly schedule.

Pipeline features:

Trigger automated tests on pull requests

Publish test results (JUnit/XML format)

Email notifications on build failure

Parallel test execution across multiple browsers

🔗 Pipeline YAML Examples

📜 Certifications
Certification	Status
ISTQB Foundation Level	In Progress (Exam: [Month Year])
Selenium WebDriver with Java/C#	Completed
Cypress Automation	Completed
Cucumber BDD	Completed
Postman API Testing	Completed
k6 Performance Testing	Completed
JMeter Performance Testing	Completed
SQL for Testers	Completed
CI/CD (Azure DevOps/Jenkins)	Completed
CCNA (Cisco)	Completed (2013)
📊 GitHub Stats (Optional)
https://github-readme-stats.vercel.app/api?username=yinus-sabur&show_icons=true&theme=default

https://github-readme-stats.vercel.app/api/top-langs/?username=yinus-sabur&layout=compact

📫 How to Reach Me
Email: sabur.yinus@gmail.com

WhatsApp: +27744471216

LinkedIn: linkedin.com/in/yinus-olamilekan-sabur

✅ Alignment with Pkasti Sandton Role
Requirement	My Tool	Project #
Front-end automation	Selenium, Cypress	#1, #2, #3
Back-end automation	Postman, REST API	#4
BDD (Cucumber/SpecFlow)	Cucumber (Gherkin)	#3
CI/CD environment	Azure DevOps / Jenkins	#7
API testing	Postman	#4
k6 (load/performance)	k6, JMeter	#5
SQL	SQL queries	#6
Test planning tools	Azure Test Plans / Jira	Throughout
Risk & quality controls	QA processes	Telecom background
📝 Notes to Recruiters
This portfolio demonstrates my ability to:

✅ Build automation frameworks using Selenium & Cypress
✅ Implement BDD with Cucumber (Gherkin syntax)
✅ Set up CI/CD pipelines (Azure DevOps / Jenkins)
✅ Automate REST API tests using Postman
✅ Run load & performance tests using k6 and JMeter
✅ Write SQL queries for test data setup & validation
✅ Train dev teams on test frameworks & infrastructure
✅ Conduct Proof of Concept (PoC) for QA process improvement

Last updated: May 2026
Open to work: ✅ Yes (Junior/Mid-level QA Automation roles)

### INITIALIZED ALL FRAMEWORKS MODULES IN ONE GO

# Ensure you're in the root directory
cd C:\Users\USER\Documents\full-stack-test-automation-framework\full-stack-test-automation-framework

Write-Host "🔧 Initializing all test modules..." -ForegroundColor Green

# 1. Playwright-Tests-Framework
cd Playwright-Tests-Framework
npm init -y
npm install @playwright/test
New-Item -ItemType Directory -Force -Path tests, pages
@'
import { test, expect } from "@playwright/test";

test("homepage has title", async ({ page }) => {
  await page.goto("https://example.com");
  await expect(page).toHaveTitle("Example Domain");
});
'@ | Out-File -FilePath tests\example.spec.js -Encoding UTF8
cd ..
Write-Host "✅ Playwright-Tests-Framework initialized" -ForegroundColor Yellow

# 2. Selenium-Tests-Framework
cd Selenium-Tests-Framework
New-Item -ItemType Directory -Force -Path src\test\java, src\test\resources, src\main\java
@"
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 
         http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>
    <groupId>com.framework</groupId>
    <artifactId>selenium-tests</artifactId>
    <version>1.0.0</version>
</project>
"@ | Out-File -FilePath pom.xml -Encoding UTF8
cd ..
Write-Host "✅ Selenium-Tests-Framework initialized" -ForegroundColor Yellow

# 3. Cypress-Tests-Framework
cd Cypress-Tests-Framework
npm init -y
New-Item -ItemType Directory -Force -Path cypress\e2e, cypress\fixtures, cypress\support
cd ..
Write-Host "✅ Cypress-Tests-Framework initialized" -ForegroundColor Yellow

# 4. Cucumber-BDD-Framework
cd Cucumber-BDD-Framework
New-Item -ItemType Directory -Force -Path src\test\java, src\test\resources
cd ..
Write-Host "✅ Cucumber-BDD-Framework initialized" -ForegroundColor Yellow

# 5. k6-Performance-Tests
cd k6-Performance-Tests
New-Item -ItemType Directory -Force -Path scripts
@'
import http from "k6/http";
import { check } from "k6";

export const options = {
  vus: 10,
  duration: "30s",
};

export default function () {
  const res = http.get("https://test.k6.io");
  check(res, { "status is 200": (r) => r.status === 200 });
}
'@ | Out-File -FilePath scripts\load-test.js -Encoding UTF8
cd ..
Write-Host "✅ k6-Performance-Tests initialized" -ForegroundColor Yellow

# 6. JMeter-Performance-Tests
cd JMeter-Performance-Tests
New-Item -ItemType Directory -Force -Path test-plans, results
cd ..
Write-Host "✅ JMeter-Performance-Tests initialized" -ForegroundColor Yellow

# 7. Postman-API-Tests
cd Postman-API-Tests
New-Item -ItemType Directory -Force -Path collections, environments
"# Postman API Tests" | Out-File -FilePath README.md -Encoding UTF8
cd ..
Write-Host "✅ Postman-API-Tests initialized" -ForegroundColor Yellow

# 8. SQL-Test-Data
cd SQL-Test-Data
New-Item -ItemType Directory -Force -Path scripts, test-data
"# SQL Test Data" | Out-File -FilePath README.md -Encoding UTF8
cd ..
Write-Host "✅ SQL-Test-Data initialized" -ForegroundColor Yellow

# 9. Mobile-Tests
cd Mobile-Tests
New-Item -ItemType Directory -Force -Path android, ios, appium-tests
cd ..
Write-Host "✅ Mobile-Tests initialized" -ForegroundColor Yellow

# 10. CI-CD-Pipelines
cd CI-CD-Pipelines
New-Item -ItemType Directory -Force -Path github-actions, jenkins, azure-devops
cd ..
Write-Host "✅ CI-CD-Pipelines initialized" -ForegroundColor Yellow

Write-Host "`n🎉 All modules initialized successfully!" -ForegroundColor Green

# Show summary
Write-Host "`n📁 Module Summary:" -ForegroundColor Magenta
Get-ChildItem -Directory | ForEach-Object {
    $itemCount = (Get-ChildItem $_ -Recurse -File 2>$null).Count
    Write-Host "  📂 $_ ($itemCount files)" -ForegroundColor White
}
