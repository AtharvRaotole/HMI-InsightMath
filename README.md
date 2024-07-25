# HMI-InsightMath
This project consists of a Flask-based API that interacts with the ChatGPT model using the revChatGPT library, and a React frontend for user interaction.

## Prerequisites

- Python 3.7+
- pip (Python package manager)
- Node.js and npm (for React frontend)

## Backend Setup

1. Navigate to the backend directory:
```
cd backend
```
2. Create a virtual environment:
```
python -m venv venv
```
3. Activate the virtual environment:

- On Windows:

  ```
  venv\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source venv/bin/activate
  ```
4. Create a config.json file in the backend directory with your ChatGPT token:
  ```
  "access_token": "your-chatgpt-access-token-here"
  ``` 
## Frontend Setup

1. Navigate to the frontend directory:
   
   ```
   cd frontend
   ```
2. Install dependencies:
   
   ```
   npm install
   ```

## Running the Application

- Make sure you're in the project directory and your virtual environment is activated.
- Run the Flask application:
  
  ```
  python main.py
  ```
The API will be available at http://127.0.0.1:5000/.

- In a new terminal, start the frontend:
  
  ```
  npm start
  ```
The React app will be available at http://localhost:3000/.
