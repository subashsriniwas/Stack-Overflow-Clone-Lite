# StackOverflow Lite - My Version

## Contributor
- Subash Sriniwas M
- smsubash234@gmail.com
- Happy coding! 🚀

## Gallery



## Contact Information:

Feel free to reach out for collaboration opportunities, project partnerships, or to discuss potential roles. I am open to connecting with fellow professionals, enthusiasts, and hiring managers.

Email: smsubash234@gmail.com

LinkedIn: https://www.linkedin.com/in/subash-sriniwas/

### ---

This project is a StackOverflow clone with basic features, including user authentication, question creation, answering, image uploading, and voting. The frontend is developed using Angular, and the backend is built with Spring Boot. JWT is used for security.

## Note

-Some of the features were under development. Stay tuned for more updates👽.

## Prerequisites

- Node.js and npm (for Angular)
- Java 8 or higher
- Maven
- MySQL database

## Setup

### Frontend (Angular)

1. Navigate to the `frontend` directory:

   ```bash
   cd frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   ng serve
   ```

   The app will be accessible at `http://localhost:4200/`.

### Backend (Spring Boot)

1. Navigate to the `backend` directory:

   ```bash
   cd backend
   ```

2. Set up your MySQL database and update the `application.properties` file with the database configuration.

3. Build the project:

   ```bash
   mvn clean install
   ```

4. Run the Spring Boot application:

   ```bash
   java -jar target/stackoverflow-clone.jar
   ```

   The backend will be accessible at `http://localhost:8080/`.

## Endpoints

### User

- `POST /signup` - Register a new user.
- `POST /auth` - Login and obtain JWT token.

### Question

- `POST /api/question` - Create a new question (requires authentication).
- `GET /api/questions/{pageNumber}` - Get all questions with pagination.
- `GET /api/question/{userId}/{questionId}` - Get a question by ID with answers.
- `GET /api/questions/{userId}/{pageNumber}` - Get questions by user ID.
- `POST /api/vote` - Add vote to a question (requires authentication).

### Answer

- `POST /api/answer` - Create a new answer for a question (requires authentication).

### Image

- `POST /api/image/upload` - Upload an image into the database (requires authentication).

## Notes

- Make sure to configure your MySQL database and update the application.properties file accordingly.
- Ensure that the frontend and backend are running simultaneously for the full application experience.

## Notes

- If you have any queries, feel free to contact me. Contacts details were given in bio. Happy coding! 🚀

