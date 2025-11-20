# Simple Chat Application

A simple, beautiful, and interactive real-time chat application built using **Spring Boot, Thymeleaf, WebSockets, SockJS, and STOMP protocol**.

![Chat Application Demo](chat-app/src/main/resources/static/img.png)
![Chat Application Demo](chat-app/src/main/resources/static/img_1.png)

## Overview

This is a Maven-based Spring Boot project demonstrating how to create live two-way communication between clients and server using WebSocket messaging. The chat app provides a modern chat experience with instant message delivery, leveraging Spring’s WebSocket and STOMP support, and an easily customizable UI built with Thymeleaf.

## Features

- **Real-time Chat:** Instant messaging between users, no refresh needed.
- **WebSocket & STOMP Protocol:** Efficient, bidirectional client-server communication.
- **SockJS Fallback:** Compatible with browsers lacking native WebSocket support.
- **Thymeleaf Templates:** Dynamic, elegant user interface powered by Thymeleaf.
- **Spring Boot Backend:** Rapid Java application development.
- **Maven Build:** Easy dependency management and build process.

## Technologies Used

- **Spring Boot**
- **Thymeleaf**
- **WebSocket**
- **SockJS**
- **STOMP**
- **Maven**

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven 3.6.x or higher

### Installation & Running

1. **Clone the Repository**
    ```bash
    git clone https://github.com/its-vikash-Kushwaha/Simple-Chat-Application.git
    cd Simple-Chat-Application
    ```

2. **Build the Project**
    ```bash
    mvn clean install
    ```

3. **Run the Application**
    ```bash
    mvn spring-boot:run
    ```
    Access at `http://localhost:8080`.

## How It Works

- Users send messages via their browser using WebSocket.
- The server receives messages and broadcasts them to all clients using STOMP over WebSocket.
- SockJS provides fallback compatibility for unsupported browsers.
- Thymeleaf updates chat messages in real-time for all connected users.

## Project Structure

```
Simple-Chat-Application/
├── src/
│   └── main/
│       ├── java/             # Spring Boot Controllers, Configurations
│       └── resources/
│           ├── static/       # Static assets
│           └── templates/    # Thymeleaf HTML files
├── pom.xml                   # Maven project configuration
```

## Contributing

Contributions are welcome! Please open issues and pull requests.

## License

MIT License

---

Feel free to use, modify, and extend this Maven-based chat application for your own projects!
