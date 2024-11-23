# Backend Project - DevBackend

## Getting Started

Follow the steps below to set up and run the backend project:

### 1. Clone the Repository
Copy and clone the project from the GitHub repository:
```bash
git clone https://github.com/danifeyrus/DevBackend
```

### 2. Install Dependencies
Navigate to the project folder and install all the required dependencies:
```bash
npm install
```
The main dependencies used in this project are:
- **axios**: `^1.6.7`
- **bcrypt**: `^5.1.1`
- **dotenv**: `^16.4.5`
- **express**: `^4.18.2`
- **jose**: `^5.2.2`
- **mongoose**: `^8.2.0`
- **nodemon**: `^3.1.0`
- **yup**: `^1.3.3`

### 3. Configuration
Inspect and configure the `.env` file with the necessary environment variables (e.g., database connection string, API keys).

### 4. Run the Project
Start the backend server:
```bash
npm run dev
```

The server should now be running, and you can interact with the API endpoints.

---

### Project Structure
- **models/**: Contains database models and schemas.
- **public/**: Static files and assets.
- **utils/**: Utility functions and helpers.
- **db.js**: Database connection configuration.
- **index.js**: Entry point of the application.

### Notes
- Ensure you have **Node.js** and **npm** installed.
- Check `package.json` for additional scripts or configurations.
