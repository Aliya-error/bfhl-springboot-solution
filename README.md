# BFHL Spring Boot Webhook Solution

## Instructions

1. Modify the SQL query in `StartupRunner.java` (`finalSQL` variable) after solving the question.
2. Run the application using Maven:
   ```bash
   mvn spring-boot:run
   ```
3. The app will:
   - Generate the webhook using your details.
   - Solve the question (insert your query).
   - Submit the solution to the webhook with the access token.

## Requirements
- Java 11 or above
- Maven

## Notes
- No controllers or endpoints are defined; logic runs automatically on startup.
- Uses `RestTemplate` for HTTP communication.
