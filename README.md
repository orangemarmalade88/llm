# llm

## Running the React App

1. Change directory to the React app folder:
   ```bash
   cd react
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the app.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


---

## Spring Boot Docker Build and Run

1. Go to the spring-boot directory:
   ```bash
   cd spring-boot
   ```

2. Build the jar file (if not already built):
   ```bash
   mvn package
   ```

3. Build the Docker image:
   ```bash
   docker build -t spring-boot-app .
   ```

4. Run the Docker container:
   ```bash
   docker run -p 8080:8080 spring-boot-app
   ```

---
