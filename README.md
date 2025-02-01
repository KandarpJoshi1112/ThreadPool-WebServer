# ThreadPool Web Server  

## Overview  
The **ThreadPool Web Server** is a Java-based concurrent server using a fixed thread pool to efficiently manage multiple client connections. Load testing and capacity evaluation were performed using Apache JMeter.  

## Features  
- **Thread pool implementation** for efficient resource management.  
- **Handles multiple concurrent requests** with optimized threading.  
- **Load testing with JMeter** to analyze server performance.  

## How It Works  
- The **server** listens on port `8080`, accepting multiple connections.  
- A **fixed thread pool** manages client requests, reducing thread creation overhead.  
- The **JMeter test plan** is used to simulate high user loads and measure performance.  

## Setup and Usage  
### Prerequisites  
- Java (JDK 8 or later)  
- Apache JMeter (for load testing)

## Running the Project
1. **Compile the files:**
   ```sh
   javac Server.java 
   ```
2. **Start the server:**
   ```sh
   java Server
   ```

### Should Look Like Following

![Screenshot (17)](https://github.com/user-attachments/assets/cbe10782-d671-4c72-b0b2-2e56e37c606e)




## Now Load Testing with JMeter
1. Open `ThreadPoolTest.jmx` in Apache JMeter.
2. Configure the number of threads (users) and test duration.
3. Run the test to analyze performance metrics such as response time and throughput.

## Performance Testing
- The JMeter test plan simulates **30,000 concurrent users** over **30 seconds**.
- Performance metrics such as response time, success rate, and error handling are collected.
- The test plan includes graphical and tabular result analysis.

### Following are Test Results simulating **30,000 concurrent users** over **30 seconds**.
![Screenshot (12)](https://github.com/user-attachments/assets/7ada904a-2925-46d8-872d-86e06f08c811)
![Screenshot (14)](https://github.com/user-attachments/assets/a1ce4f42-9cc7-40df-8f97-6ffd3944eff1)
![Screenshot (13)](https://github.com/user-attachments/assets/fdc07c4a-b62b-4b02-a812-97dbb277d424)




👤 **Kandarp Joshi**

* Github: [@Kandarp Joshi](https://github.com/KandarpJoshi1112)
* LinkedIn: [@Kandarp Joshi](https://www.linkedin.com/in/kandarp-joshi-3451231bb/)

Enjoy coding! 🚀
