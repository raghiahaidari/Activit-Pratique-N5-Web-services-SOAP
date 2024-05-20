# Simple App : SOAP Web Service 🚀

## 📜 Description

This project demonstrates the creation and deployment of a SOAP web service using JAX-WS. The service includes functionalities to:
- Convert a monetary amount from euros to dirhams
- Consult a single account
- Retrieve a list of accounts

## 📂 Project Structure
```
client-soap
└───src
    ├───main
    │   ├───java
    │   │   └───com
    │   │       └───haidari
    │   │           └───main.java
    │   │   └───proxy
    │   └───resources
    └───test
src
├───main
│   ├───java
│   │   └───Web Services
│   │        ├───BanqueService.java
│   │        └───Compte.java
│   │   └───ServerJWS.java
│   └───resources
└───test
```

## 🌟 Features

- **Currency Conversion**: Convert an amount from euros to dirhams.
- **Account Consultation**: Retrieve details of a specific account.
- **List Accounts**: Retrieve a list of all available accounts.

## 🛠️ Getting Started

### 📋 Prerequisites

- Java Development Kit (JDK) 8 or later
- Apache Maven
- SoapUI or Oxygen (for testing)
- HTTP Browser (for analyzing WSDL)

## 🔍 Analyzing the WSDL

- Open a browser and navigate to `http://localhost:9090/?wsdl` to view the WSDL file and analyze the web service definition.

## 🧪 Testing the Web Service

- Use SoapUI or Oxygen to test the web service operations:
    1. Convert an amount from euros to dirhams.
    2. Consult an account by code.
    3. List all accounts.

## 📁 Project Files

- **BanqueService.java**:
    - Defines the web service with methods for currency conversion and account management.

- **Compte.java**:
    - Represents an account with fields for code, balance, and date.

- **ServerJWS.java**:
    - Deploys the web service using JAX-WS.

- **Main.java**:
    - Implements the client for consuming the web service.



