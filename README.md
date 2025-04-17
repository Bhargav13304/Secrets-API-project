# Secrets API Project

The Secrets API Project is a secure and minimalistic web application where users can anonymously submit and view secrets. It is built using Node.js and Express.js for robust backend support, with EJS as the templating engine and CSS for front-end styling. This project showcases how to implement user input handling, routing, and dynamic page rendering in a secure and accessible manner.

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Templating**: EJS
- **Styling**: CSS
- **Runtime**: JavaScript

## 🚀 How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Bhargav13304/Secrets-API-project.git
   cd Secrets-API-project
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start the server**:

   ```bash
   node server.js
   ```

4. **Access the application**:

   Open your browser and go to `http://localhost:3000`

## ✨ Features

- **Submit** secrets anonymously through a clean interface
- **View** a collection of secrets shared by all users
- Dynamic content rendering with EJS templates
- Modular and scalable codebase for future enhancements

## 🧪 How to Use the API

This application is primarily a web-based interface, but you can simulate interactions using tools like Postman for testing routes.

### Endpoints

- `GET /` - Home page
- `GET /submit` - Form to submit a secret
- `POST /submit` - Submit a secret (use Postman or form submission)
- `GET /secrets` - View all submitted secrets

### Using Postman

1. Launch Postman
2. Use `POST` method for `http://localhost:3000/submit`
3. Set the body type to `x-www-form-urlencoded`
4. Add key-value pair: `secret`: `your secret text`
5. Send the request and check output at `http://localhost:3000/secrets`

## 📁 Folder Structure

```
Secrets-API-project/
├── public/
│   └── styles/          # CSS files for styling
├── views/               # EJS templates for rendering pages
├── server.js            # Main server file
├── solution.js          # Additional logic or helper functions
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation
```

