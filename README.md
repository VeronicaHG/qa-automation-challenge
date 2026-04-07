# QA Automation Project – N26 Challenge

## 📌 Overview

This project demonstrates a complete QA approach for a web application, including:

- Exploratory testing
- UI test automation
- API testing
- Bug identification and reporting

The goal is to simulate a real-world QA workflow, focusing on **quality, coverage, and maintainability**.

---

## 🎯 Scope

The following areas were covered:

- Functional testing of core user flows
- Validation of input fields and error handling
- UI behavior and consistency
- API request/response validation
- Edge cases and negative scenarios

---

## 🛠️ Tech Stack

- **Automation Framework:** Playwright / Cypress  
- **Language:** TypeScript / JavaScript  
- **API Testing:** Postman  
- **Version Control:** GitHub  
- **Test Design:** Manual + Automated  

---

## 📂 Project Structure 

├── tests → UI automated test cases 
├── api-tests → API validation tests 
├── exploratory-testing → notes, findings, scenarios 
└──fixtures → test data
  
---

## ▶️ How to Run the Tests

1. Clone the repository:
```bash
git clone https://github.com/VeronicaHG/your-repo-name.git
```
2. Install dependencies:
```bash
npm install
```
3. Run tests:
```bash
npx playwright test
```

## 🧪 Test Strategy

This project combines:
- **Exploratory testing** to discover unexpected issues
- **Automated UI testing** for critical flows
- **API testing** to validate backend behavior
  
Priority was given to:

- Critical user journeys
- High-risk functionalities
- Input validation and error scenarios
  
## ✅ Key Test Scenarios
- Add transaction flow
- Form validation (valid/invalid inputs)
- Error messages handling
- UI consistency
- API response validation

## 🐞 Bugs & Findings
Some issues identified during testing include:

- Missing validation on input fields
- Inconsistent error messages
- UI behavior issues in edge cases

👉 See detailed findings in:
/exploratory-testing

## 🚀 Improvements

Future improvements could include:

- Integration with CI/CD (GitHub Actions)
- Test reporting (HTML reports)
- Increased test coverage
- Data-driven testing
 
 ## 🤝 Contribution

This project is open to improvements and collaboration.

If you'd like to contribute:

- Fork the repo
- Create a feature branch
- Submit a pull request

## 👩‍💻 Author
Veronica Herrera
QA Engineer focused on test automation and quality processes

⭐ If you find this project useful, feel free to star it!
