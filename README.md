# 🧪 E-Commerce Website QA Automation

This is a test automation project for the website [qatest-dev.indvp.com](https://qatest-dev.indvp.com/), covering both manual and automated testing scenarios using:

- Java
- Selenium WebDriver
- JUnit 5
- Page Object Model (POM)
- 
---

## ✅ What This Project Covers

### 🔍 Manual Test Cases
- ✅ **TC_001**: Verify subcategory navigation from "PORTMEIRION"
- ✅ **TC_002**: Product search using the search bar
- ✅ **TC_003**: Social media footer link redirection
- ✅ **TC_004**: Newsletter signup with a valid email
- ✅ **TC_005**: Account creation with valid information

### 🤖 Automated Test Cases
- ✅ **TC_006**: Validate subtotal calculation in cart
- ✅ **TC_007**: Submit invalid data during checkout
- ✅ **TC_008**: Register with already used email
- ✅ **TC_009**: Register with unrealistic/invalid data

---

## 🧱 Project Structure

📁 src
┣ 📂 main
┃ ┣ 📂 java
┃ ┃ ┣ 📂 pages # Page Object classes
┃ ┃ ┣ 📂 tests # Test classes
┣ 📄 testcases.docx # Manual test case documentation
┣ 📄 pom.xml # Maven project file


---

## 🚀 How to Run

1. Clone this repository
2. Open in IntelliJ IDEA or any Java IDE
3. Install dependencies using Maven:
   ```bash
   mvn clean install

4. Run all tests:
    ```bash
    mvn test
    ```
5. View Allure reports:
    ```bash
    allure serve allure-results
    ```
⚠️ Notes
The site qatest-dev.indvp.com is a testing environment — some functionalities like real email confirmation or product deletion may be limited or intentionally broken.

The account used in TC_008 for duplicate registration:
Email: gvazava.shalva5@gmail.com
Password: Any dummy value

Shalva Gvazava
QA Engineer & Automation Tester\
📍 Georgia, Tbilisi\
🔗 LinkedIn 
[Shalva Gvazava](https://www.linkedin.com/in/shalva-gvazava-1a1590285/)
