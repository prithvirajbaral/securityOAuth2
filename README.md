# Security OAuth2 with Spring Boot

This project demonstrates how to implement OAuth2 authentication and authorization using Google and GitHub in a Spring Boot application.

## Features
- OAuth2-based authentication using Google and GitHub.
- Role-based access control.
- API endpoint security.

## Prerequisites
- Java 8 or higher
- Maven
- Google and GitHub OAuth2 credentials

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prithvirajbaral/securityOAuth2.git

2. **Add your OAuth2 credentials:** Update the ```application.properties``` file with your Google and GitHub OAuth2 client IDs and secrets.
    ```properties
    # Google OAuth2 credentials
    spring.security.oauth2.client.registration.google.client-id=your-google-client-id
    spring.security.oauth2.client.registration.google.client-secret=your-google-client-secret

    # GitHub OAuth2 credentials
    spring.security.oauth2.client.registration.github.client-id=your-github-client-id
    spring.security.oauth2.client.registration.github.client-secret=your-github-client-secret
3. **Build the project:**
    ```bash
    mvn clean install
4. **Run the application:**
    ```bash
    mvn spring-boot:run

## Security
- OAuth2 with Google and GitHub integration.
- Sensitive data is stored securely in ```application.properties```.
