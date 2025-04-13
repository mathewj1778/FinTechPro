
# FinTech Pro - Financial Management System

## Project Overview
FinTech Pro is a comprehensive web-based financial management application that helps users track their finances, manage investments, and make informed financial decisions. The system provides real-time portfolio management, transaction tracking, and AI-powered financial assistance.

## How to Run It / Setup Instructions
1. Fork this template
2. Click the "Run" button to start the server
3. The application will be available at port 5000
4. Create an account or login with existing credentials
5. Start managing your finances!

## Features / What It Does
- **User Authentication** 
  - Secure login/register system
  - Personal account management
- **Portfolio Management**
  - Real-time stock tracking
  - Buy/sell stock functionality
  - Portfolio value visualization
- **Transaction Tracking**
  - Income and expense recording
  - Transaction categorization
  - Historical transaction view
- **AI-Powered Assistant**
  - Financial advice
  - Investment recommendations
  - Market insights
- **Financial Predictions**
  - Portfolio growth projections
  - Investment opportunity analysis
- **Recurring Payments**
  - Automated payment tracking
  - Payment scheduling
  - Regular transaction management
- **Report Generation**
  - Comprehensive financial reports
  - Portfolio analysis
  - Transaction summaries

## Technologies / Libraries Used
- **Core Technologies**
  - Java 17 (GraalVM CE)
  - Jetty Server (v9.4.44)
  - Maven Build System
- **Libraries**
  - junit:junit (v4.12) - Testing framework
  - org.eclipse.jetty:jetty-server (v9.4.44) - Web server
  - org.eclipse.jetty:jetty-servlet (v9.4.44) - Servlet handling
  - com.google.code.gson:gson (v2.12.1) - JSON processing
  - com.theokanning.openai-gpt3-java:service (v0.18.2) - OpenAI integration

## Credits & Licenses
This project uses the following open-source software:
- Jetty Server (Apache License 2.0)
- Gson (Apache License 2.0)
- JUnit (Eclipse Public License 1.0)
- OpenAI GPT3 Java (MIT License)

## Source Code Structure
- `src/main/java/Main.java` - Main application code
- `pom.xml` - Maven dependencies and build configuration
- `.replit` - Replit configuration
- `replit.nix` - Nix environment configuration

## Complex Data Structures Implementation
The application demonstrates appropriate use of complex data structures:

1. Multi-dimensional Arrays & Lists
   - `ArrayList<String>[][] transactions` - 3D structure for user transaction history
   - Arrays for managing multiple user accounts

2. HashMaps for Key-Value Storage
   - `Map<String, Double>[] stockPrices` - Array of HashMaps for stock price tracking
   - `Map<String, Integer>[] stockHoldings` - Array of HashMaps for user portfolio management

3. Variable Scope Management
   - Class-level static variables for shared data
   - Method-level variables for temporary calculations
   - Proper encapsulation of data structures
