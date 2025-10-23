# 🍔 Manual Testing Portfolio: FoodyApp

This repository contains the full test documentation (Test Cases and Bug Report) for the functional and regression testing of the FoodyApp web application.

---

## 📜 1. Description

A complete Manual Testing project covering critical user flows for an E-commerce/Recipe Management web application. The testing focused on Functional and Boundary Value Analysis (BVA) testing based on 6 core Use Cases.

## 🔗 2. Deployment link

**Tested Environment URL:**
[Foody App Staging Environment](http://softuni-qa-loadbalancer-2137572849.eu-north-1.elb.amazonaws.com:85/)

## 💻 3. Technology Stack

* **Methodology:** Manual Functional Testing, Test Case Design.
* **Documentation:** Test Cases, Use Cases, Bug Reporting (following Jira/TestRail standards).
* **Tools:** Microsoft Excel/CSV (for documentation).

## 📄 4. API Documentation

* **Note:** This project focuses exclusively on **UI/Front-end Manual Testing**. API documentation is covered in the separate repository: **`API-Testing-Portfolio`**.

## 📐 5. Design Diagram

A Test Flow Diagram illustrating the main user paths covered in the Test Cases (Use Cases 1-6), rendered using GitHub's Mermaid support:

```mermaid
graph TD
Start[Start / Home Page (UC1)] --> B{Authentication}
B -- Log In (UC3) --> C(Logged In Home Page)
B -- Sign Up (UC2) --> B

C --> D(Profile Management - UC4)
C --> E(Food Creation - UC5)
C --> F(Food Management - UC6)

D --> G(End / Log Out)
E --> F
F --> G
