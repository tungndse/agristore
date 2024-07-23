# Agristore

Agristore is a comprehensive application designed to facilitate the management of cattle food and other related products. It features a mobile frontend built with Flutter and a backend powered by Spring Boot. The app supports product management, order handling, and QR code payment integration.

## Features

- **Product Management:** Store and manage information about cattle food products.
- **Order Processing:** Handle customer orders with QR code generation for payments.
- **QR Code Integration:** Generate QR codes for payment through VNPAY/MOMO.
- **Multi-database Support:** Uses PostgreSQL, MongoDB, and Redis for various data needs.
- **Security:** Implements OAuth2 for secure third-party authentication.
- **WebSocket Support:** Real-time updates through WebSocket.

## Technologies Used

- **Frontend:** Flutter
- **Backend:** Spring Boot
- **Databases:** PostgreSQL, MongoDB, Redis
- **Security:** Spring Security, OAuth2
- **AI Integration:** OpenAI for advanced functionalities
- **Database Migration:** Liquibase for managing schema changes

## Getting Started

### Prerequisites

- **Java 17** or higher
- **Flutter SDK** for the mobile frontend
- **PostgreSQL**, **MongoDB**, and **Redis** installed and configured
- **Maven** for building the Spring Boot application

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/agristore.git
   ```

2. **Navigate to the Project Directory**

   ```bash
   cd agristore
   ```

3. **Set Up the Backend**

   - **Install Dependencies:**

     ```bash
     mvn clean install
     ```

   - **Configure Database Settings:** Update `application.properties` or `application.yml` with your database connection details.

   - **Run the Application:**

     ```bash
     mvn spring-boot:run
     ```

4. **Set Up the Frontend**

   - **Navigate to the Flutter Project Directory:**

     ```bash
     cd path-to-flutter-project
     ```

   - **Install Dependencies:**

     ```bash
     flutter pub get
     ```

   - **Run the Application:**

     ```bash
     flutter run
     ```

## Usage

- **Access the Backend API:** The backend API is available at `http://localhost:8080`. Use endpoints to manage products, process orders, and handle payments.
- **Frontend Application:** The Flutter app provides an interface for users to interact with the backend, manage products, and place orders.

## Contributing

1. **Fork the Repository**
2. **Create a Feature Branch:**

   ```bash
   git checkout -b feature/your-feature
   ```

3. **Commit Your Changes:**

   ```bash
   git commit -am 'Add some feature'
   ```

4. **Push to the Branch:**

   ```bash
   git push origin feature/your-feature
   ```

5. **Create a New Pull Request**

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or feedback, please contact coldev.ok@gmail.com.
