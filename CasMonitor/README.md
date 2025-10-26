# CasMonitor

<img width="100" src="https://github.com/user-attachments/assets/24e678d3-2687-45a9-8e82-fe5ae40c3428" />

## Description
CasMonitor is an Android application designed for the management and monitoring of available POS terminals. The app connects to all available terminals via TCP sockets, enabling the user to manage transactions, view device states, and monitor the location of each terminal within a physical space. It supports various payment methods, including card transactions, cash transactions (with receipt generation), and account payments using QR codes. The app also provides real-time data, such as device status and resource information (e.g., memory, storage, and battery levels), allowing users to manage the terminals effectively. Additionally, it offers a top-view interactive map for easy tracking of POS device locations within the environment.

## Technologies Used  
- **Kotlin** – Programming language  
- **Android Studio** – Development environment  
- **MVVM** – Architecture pattern for clean code  
- **Retrofit** – Networking library for API communication  
- **Firebase** – Analytics and crash reporting  
- **Dagger - Hilt** – Dependency injection framework  
- **Coroutines** – Asynchronous programming
- **WilliamChart** – Library for displaying charts
- **GSON** – JSON parsing  
- **MapView** – Map integration for interactive top-view

## Features  
- TCP Socket Connectivity: Connect to all available POS terminals via TCP socket for seamless communication and monitoring
- Transaction Management: Initiate card, cash (with receipt generation), and account transactions via QR codes
- Device State Monitoring: View the current state of each POS terminal in real-time with the option to decode the status (e.g., idle, currency conversion, authorization)
- Top-View Map: Interactive map showing the location of each POS terminal in the physical space for easy tracking
- Resource Monitoring: Gather information about the terminal's memory, storage, and battery levels to ensure optimal functionality
- Real-Time Data: Access detailed charts or text information on the device's current state and transaction status
- Crash Reporting & Analytics: Integration with Firebase for crash reporting and app analytics
- Dependency Injection with Hilt: Ensures a clean and maintainable codebase
- Offline Access: Capability to handle and store data offline when needed

## Video
https://github.com/user-attachments/assets/0eb66326-d971-4bc7-a035-b286c346927a

## Screenshots
### Start Transaction
<img width="8099" alt="Cardlink flows2" src="https://github.com/user-attachments/assets/ef6625a4-5a2f-4340-aba3-95f67488c082" />

### Overview
<img width="4097" alt="Cardlink flows3" src="https://github.com/user-attachments/assets/ca5afb2c-9404-4822-8d79-5674a0fdb1b5" />

### Dashboard
<img width="4097" alt="Cardlink flows" src="https://github.com/user-attachments/assets/7de32242-ebfa-4ffb-a610-c720172bc787" />

### Transaction from Map
<img width="2176" alt="Cardlink flows4" src="https://github.com/user-attachments/assets/830f3ac4-d684-4496-8ed2-1ebe269b5e78" />
