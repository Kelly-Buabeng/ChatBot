# ChatBot

A simple chatbot application built with a **Node.js backend (Express + Axios)** and a **React frontend**.  
The backend handles authentication with the [ChatEngine API](https://github.com/chatengine-io/react-chat-engine), while the frontend provides a clean interface for chatting.

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ChatBot.git
cd ChatBot
```
### 2. Backend Setup
```bash
Copy code
cd backend
npm install
node index.js
The backend will run on http://localhost:3001

```


### 3. Frontend Setup
```bash
Copy code
cd frontend
npm install
npm start
The frontend will run on http://localhost:3000
```

# Environment Variables
Update your backend index.js with your own ChatEngine credentials:
Copy code
headers: { "private-key": "your-private-key-here" }
And set user authentication secrets accordingly.

# Usage
Start the backend:

```bash
Copy code
node index.js

```
Start the frontend:
```bash
Copy code
npm start
(inside /frontend directory)
Register/login with a username
Start chatting
```
# Dependencies

## Backend
### 1.express
### 1.cors
### 3.axios

## Frontend
### 1.react
### 2.react-dom

# License
## This project is open-source under the MIT License.
