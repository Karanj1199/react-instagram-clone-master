
# Instagram Clone - Full Stack Java Project

## Description

This project is an Instagram clone built using modern web technologies. It allows users to sign up, log in, and interact with a user interface that mimics Instagram. The application leverages React for the front-end, Spring Boot for the back-end, and Firebase for authentication and user management.

This project was developed as a personal learning endeavor to enhance my full-stack development skills, focusing on key areas such as authentication, state management, and responsive UI design.

## Key Technologies Utilized

- **React**: A JavaScript library for building dynamic and responsive user interfaces.
- **Spring Boot**: A powerful back-end framework for creating robust applications.
- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.
- **Redux**: A state management library for managing the application's state.
- **Firebase**: Used for authentication and user management.

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or Yarn
- Java 17 (JDK 17)
- Maven

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/instagram-clone.git
    ```
2. Navigate to the project directory:
    ```bash
    cd instagram-clone
    ```
3. Install the necessary dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

4. Start the development server:
    ```bash
    npm start
    # or
    yarn start
    ```

5. For the backend (Spring Boot), navigate to the backend directory and run:
    ```bash
    mvn spring-boot:run
    ```

## Usage

After setting up the project, you can start using the Instagram Clone. Users can sign up, log in, and interact with the various features provided by the application, such as posting images, liking posts, and viewing suggestions.

## Project Structure

- `public/` - Contains static files and the main HTML file.
- `src/` - Contains all the source code files:
  - **App.js** - The main component that handles routing and state management.
  - **Homepage.js** - The main landing page after logging in.
  - **Sidenav.js** - The sidebar navigation component.
  - **Timeline.js** - Displays the posts from followed users.
  - **Post.js** - Represents a single post with options to like and comment.
  - **Suggestions.js** - Provides user suggestions to follow.
  - **Authenticate.js** - Manages user authentication (Login/Signup).
  - **Login.js** - Handles user login.
  - **Signup.js** - Handles user signup.
  - **firebase.js** - Firebase configuration for authentication.
  - **userSlice.js** - Redux slice for managing user state.

## Key Features

- **User Authentication**: Sign up and log in using Firebase authentication.
- **Post Creation**: Users can create posts with images.
- **Responsive Design**: The UI is responsive, providing a seamless experience across devices.
- **State Management**: Uses Redux for state management across the application.

## Dependencies

This project uses the following dependencies, managed via npm/yarn:

- **React**: ^18.2.0
- **Firebase**: ^9.18.0
- **Redux**: ^4.2.1
- **@mui/material**: ^5.11.13

These dependencies are defined in the `package.json` file and will be automatically installed when you run `npm install` or `yarn install`.

## Configuration Files

- **`firebase.js`**: Contains Firebase configuration for connecting to the Firebase backend.
- **`.gitignore`**: Specifies files and directories that should be ignored by Git, including `node_modules/` and `.env` files.



This README provides a comprehensive overview of the Instagram Clone project. You can download the README.md file below:

[Download README.md](sandbox:/mnt/data/README.md)
