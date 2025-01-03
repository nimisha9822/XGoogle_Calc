# XGoogle Calc
# Selenium Test Cases

This project demonstrates the usage of Selenium WebDriver for automating browser actions using Java. It includes test cases for validating the functionality of the Google Calculator available on the Google search page.

# Features

Automated browser setup using WebDriverManager.

Test cases for basic calculator operations: addition, subtraction, multiplication, and division.

Logging and debugging support with detailed logs for browser and driver.

Implicit waits and thread sleeps for synchronization.

# Prerequisites

Ensure you have the following installed:

Java Development Kit (JDK) 8 or higher

Maven (for dependency management)

Google Chrome browser

# Getting Started

1. Clone the Repository
git clone <repository_url>
cd <repository_folder>

2. Set Up Dependencies

Add the following dependencies to your pom.xml file (if using Maven):
<dependencies>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.14.0</version>
    </dependency>
    <dependency>
        <groupId>io.github.bonigarcia</groupId>
        <artifactId>webdrivermanager</artifactId>
        <version>5.6.0</version>
    </dependency>
</dependencies>
