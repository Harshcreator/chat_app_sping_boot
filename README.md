# Real-time Chat Application

This is a real-time chat application built with Spring Boot and WebSocket.

## Features

- Real-time messaging
- WebSocket communication
- Simple and intuitive UI

## Technologies Used

- Spring Boot
- Spring WebSocket
- Thymeleaf
- SockJS
- STOMP

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/chat-app.git
    cd chat-app
    ```

2. Build the project:
    ```sh
    ./mvnw clean install
    ```

3. Run the application:
    ```sh
    ./mvnw spring-boot:run
    ```

4. Open your browser and navigate to [http://localhost:8080/chat](http://_vscodecontentref_/0).

## Usage

1. Enter your name in the "Type your name here..." input field.
2. Type your message in the "Type your message here..." input field.
3. Click the "Send" button to send your message.

## Project Structure

- [app](http://_vscodecontentref_/1) - Main application code
- [templates](http://_vscodecontentref_/2) - Thymeleaf templates
- [application.properties](http://_vscodecontentref_/3) - Application configuration
- [app](http://_vscodecontentref_/4) - Test cases
