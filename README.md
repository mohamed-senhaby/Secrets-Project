# Secrets Web App

Welcome to the Secrets Web App project! This application allows users to access random secrets and display them on a webpage. It's built using Node.js, Express.js, Axios, and EJS templates.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [API Used](#api-used)
- [Contributing](#contributing)


## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- Git: [Download and Install Git](https://git-scm.com/)

### Installation

1. Clone this repository using Git:

   ```bash
   git clone https://github.com/your-username/secrets-web-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd secrets-web-app
   ```

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

### Running the Application

1. Start the server:

   ```bash
   npm start
   ```

2. Open your web browser and visit `http://localhost:3000` to view the Secrets Web App in action.

## Project Structure

The project is structured as follows:

- `public/`: Directory containing static assets like CSS, images, and client-side JavaScript.
- `views/`: Directory containing EJS templates.
- `index.js`: Main application file containing Express server setup and route handling.

## API Used

The Secrets Web App fetches random secrets and usernames from the [Secrets API](https://secrets-api.appbrewery.com/random).

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Create a pull request.

