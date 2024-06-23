# Angular Tic-Tac-Toe

This project is a simple Tic-Tac-Toe game built using Angular. The game allows two players to take turns marking spaces in a 3×3 grid, with the objective of placing three respective marks in a horizontal, vertical, or diagonal row.

## Author

- Fares Yusuf

## Features

- Two-player gameplay
- Win detection for rows, columns, and diagonals
- Game reset functionality
- Basic UI for easy interaction

## Project Structure

- **src/**: Contains the source code for the Angular application.
- **e2e/**: Contains end-to-end tests for the application.
- **.editorconfig**: Configuration file for code editors to maintain consistent coding styles.
- **.firebaserc**: Firebase project configuration.
- **firebase.json**: Firebase hosting configuration.
- **angular.json**: Angular CLI configuration.
- **package.json**: Contains metadata about the project and its dependencies.
- **tsconfig.json**: TypeScript configuration for the project.
- **karma.conf.js**: Configuration for the Karma test runner.
- **README.md**: Project documentation.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (with npm)
- [Angular CLI](https://angular.io/cli)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/angular-tic-tac-toe.git
   ```
2. Navigate to the project directory:
   ```bash
   cd angular-tic-tac-toe
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the Application

1. Start the development server:
   ```bash
   ng serve
   ```
2. Open your browser and navigate to `http://localhost:4200`.

### Running Tests

- Run unit tests:
  ```bash
  ng test
  ```
- Run end-to-end tests:
  ```bash
  ng e2e
  ```

## Deployment

This application can be deployed using [Firebase Hosting](https://firebase.google.com/docs/hosting).

1. Build the project:
   ```bash
   ng build --prod
   ```
2. Deploy to Firebase:
   ```bash
   firebase deploy
   ```

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Angular](https://angular.io/)
- [Firebase](https://firebase.google.com/)
