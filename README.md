# 🛒 Amazon ECommerce Automation

## 📄 Description

An automation testing framework for the Amazon website that covers:

1. Automated testing for key user flows on Amazon.
2. Functions covered: **Login**, **Search Product**, **Add to Cart**, **Buy Product**, and **Logout**.
3. Implements the **Page Object Model (POM)** design pattern using **Selenium WebDriver**.
4. Uses **TestNG** for managing and executing test cases.
5. Supports **Data-Driven Testing (DDT)** with data fetched from Excel files using **Apache POI**.
6. Ensures reliability and efficiency with detailed test reporting for analysis.

---

## 🌐 Overview

This is a robust automation test framework for Amazon ECommerce. It covers essential scenarios such as:

- Adding/removing products from the cart  
- Searching for products  
- Viewing product details  
- Testing the checkout flow  

---

## 🛠️ Tech Stack

| Technology           | Purpose                                        |
|----------------------|------------------------------------------------|
| **Java**             | Core programming language                      |
| **Maven**            | Project and dependency management              |
| **Selenium WebDriver** | Browser automation and UI testing           |
| **TestNG**           | Testing framework for writing and executing tests |
| **Apache POI**       | Reading and writing Excel files (for test data) |
| **Custom Module** (`Automationmaven1`) | Reusable components/utilities |

---

## 🚀 Installation

### ✅ Prerequisites

- Java 8 or above
- Maven
- WebDriver (e.g., ChromeDriver) installed and added to system PATH

### 📦 Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/MANIKJAIN3604/Amazon-Ecommerce-Testing.git
   cd Amazon-Ecommerce-Testing
   ```

2. Install the dependencies using Maven:

   ```bash
   mvn install
   ```

3. Make sure to set up WebDriver and ensure it's available in your system's PATH.

## Running Tests

To run the tests, use the following command:

```bash
mvn test
```
