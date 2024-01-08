# Basic calculator using client-server architecture

## Overview

This project implements a Basic Calculator using client-server architecture in Java programming, allowing users to perform real-time calculations across different machines. The system supports user input via the console, real-time calculation, logging mechanism, choice of storage, and robust error handling.

## Features

### User Input via Console

Users can interact with the calculator by providing input through the console. The system processes input commands and performs calculations accordingly.

### Real-Time Calculation

The calculator provides real-time calculations, allowing users to perform arithmetic operations promptly. The client-server architecture facilitates efficient communication for seamless calculations.

### Logging Mechanism

The system incorporates a logging mechanism to keep track of user activities and calculations. Logs provide insights into the history of operations, aiding in debugging and auditing.

### Choice of Storage

Users have the flexibility to choose the storage mechanism for saving calculation results. Options may include local storage, remote databases, or cloud storage, enhancing the scalability and adaptability of the system.

### Error Handling

The system is designed with robust error-handling mechanisms to gracefully manage and report errors. Users receive informative messages, and the logs capture details for further analysis.

## Usage

To run the Basic Calculator, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SudeeptaGiri/Calculator_Client_Server_Arch.git
   ```
2. Navigate to the project directory:

   ```bash
   cd .\Calculator_Client_Server_Arch\
   ```
3. Build and run the server:

   ```bash
   javac Calc_Server.java
   java Calc_Server
   ```
4. Build and run the client on another machine:

   ```bash
   javac Calc_Client.java
   java Calc_Client
   ```

## Contributing
We welcome contributions to enhance the functionality, performance, and documentation of the Basic Calculator project. Feel free to open issues, submit pull requests, or participate in discussions.
