# Backend for Customer Management System

Imagine you are tasked with setting up a backend for a customer management system. The system's database is hosted on MongoDB, and you need to create a Node.js server using Express.js to interact with the database. Your job is to set up the server, connect it to MongoDB Atlas, and ensure the connection status is logged appropriately.

## Instructions:

### Initialize the Project:
A basic Express template is provided. You need to install all the necessary packages required for the task.

### Environment Configuration:
Set up a `.env` file in the root directory. Store the MongoDB connection string securely in the `.env` file. The connection string must follow this format:  
`MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<databaseName>?retryWrites=true&w=majority`

### Backend Server Requirements:
Go to `index.js`. Set up an Express.js server. Write the code to load and use environment variables from the `.env` file and connect to MongoDB using a database library.

### Logging Requirements:
On a successful connection to the database, the server should log: `Connected to database`. If the connection fails, the server should log: `Error connecting to database: <Error details>`.

### Testing the Backend:
Start the server and test the connection to MongoDB. Ensure appropriate messages are logged based on the connection status.

## How to Fork and Set Up Your Repository

### 1. Fork the Repository on StackBlitz
You will be provided with a **StackBlitz** link for the assignment. Open the link in your browser and click on the **Fork** button in StackBlitz. This will create a copy of the repository in your StackBlitz account.

### 2. Clone the Repository to Your Personal GitHub
After forking, you can download the project or push it directly to your personal GitHub repository.

#### Option 1: Download and Push
1. Download the repository files from StackBlitz.  
2. Open your terminal/command prompt, navigate to the project folder, and run:  
   ```bash
   git init
   git remote add origin <your_github_repo_url>
