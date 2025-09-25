# 🛒 E-Commerce Automation Framework
This is a **Selenium Web Automation Framework** built using **Java**, **Maven**, and **TestNG**, following the **Page Object Model (POM)** design pattern.  
The project automates functional test cases of an e-commerce web application.

## 📂 Project Structure  
src/main/java
└── com.mystore.pageobject
├── Account_Creation.java
├── Login_Page.java
├── My_Account.java
├── Register_Page.java
├── validate_SearchResult.java
└── VerifySignOut.java

src/test/java
├── com.mystore.testcase
│ ├── Base_Class.java              # Test initialization and teardown
│ └── TC_login.java                # Sample login test case
│
├── com.mystore.utilities
│ ├── listener_with_extent.java    # Extent report listener
│ ├── Read_Config.java             # Config file reader
│ ├── Read_Excel_File.java         # Excel data reader
│ └── Reporter_File.java           # Reporting utilities
│
└── com.mystore.testdata
# Handles test data integration

src/test/resources                # Property files, test data
configuration                     # Log4j, config files
Drivers                           # Browser drivers (Chrome, Edge, etc.)
Log                               # Generated log files
ScreenShort                       # Screenshots for failed test cases
