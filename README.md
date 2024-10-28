
# BookSearch

## Live Application
[BookSearch Live Application](https://booksearchsite.onrender.com)

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)


## Description
**BookSearch** is a full-stack web application that allows users to search for books using the Google Books API and save their favorite books to a personal list. Users can create an account, log in, and manage their collection of saved books. The application demonstrates the use of the **MERN stack** with a **React** frontend and a **Node.js/Express** backend, utilizing **GraphQL** with **Apollo Server** and **Client** for API interactions.

## Installation
To run the application locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/BookSearch.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd BookSearch
   ```

3. **Install dependencies**

   For the server:
   ```bash
   cd server
   npm install
   ```

   For the client:
   ```bash
   cd ../client
   npm install
   ```

4. **Set up environment variables**

   Create a `.env` file in the `server` directory with the following content:
   ```env
   PORT=3001
   MONGODB_URI=mongodb://localhost:27017/booksearch
   JWT_SECRET=your-secret-key
   ```
   Replace `your-secret-key` with a secure key of your choice.

5. **Start the application**

   From the root directory, run:
   ```bash
   npm run develop
   ```
   This command will concurrently start both the server and client.

## Usage
1. **Access the Application**

   Open your browser and navigate to `http://localhost:3000`.

2. **Create an Account**
   - Click on "Login/Sign Up" to open the modal.
   - Select "Sign Up" and fill in your details to create an account.

3. **Search for Books**
   - Use the search bar on the homepage to find books by title, author, or keywords.
   - Browse through the search results.

4. **Save Books**
   - Click on "Save this Book!" to add a book to your saved list.
   - You must be logged in to save books.

5. **View Saved Books**
   - Navigate to the "See Your Books" page to view all your saved books.
   - From here, you can remove books from your list.

## Features
- **User Authentication**
  - Secure sign-up and login functionality with JWT authentication.
- **Book Search**
  - Search for books using the Google Books API.
  - View book details including title, author, description, and cover image.
- **Save and Manage Books**
  - Save books to your personal list.
  - View and remove saved books.
- **Responsive Design**
  - Mobile-first design ensures usability across various devices.

## Technologies Used
### Frontend
- React
- React Router DOM
- Apollo Client
- Bootstrap / React Bootstrap

### Backend
- Node.js
- Express.js
- Apollo Server Express
- GraphQL
- MongoDB with Mongoose ODM
- JSON Web Tokens (JWT) for authentication

### APIs
- Google Books API

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! To contribute:

1. **Fork the repository**
   - Click the "Fork" button at the top right of the repository page.

2. **Create a new branch**
   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make your changes**

4. **Commit your changes** with descriptive commit messages.

5. **Push to your fork**
   ```bash
   git push origin feature/YourFeatureName
   ```

6. **Submit a pull request**
   - Open a pull request to the main branch of the original repository.


## Live Application
You can access the live application at:

[BookSearch Live Application](#) <!-- Replace with actual live application link -->
