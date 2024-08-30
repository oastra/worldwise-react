# React + Vite

# Worldwise

Worldwise is a React application designed to explore and interact with global cities and countries. The application utilizes modern React features, including hooks, context, and React Router for navigation. Additionally, it integrates with a JSON server for data handling and uses Vite for a fast development environment.

## Features

- Explore cities and countries worldwide.
- Search and filter cities based on various criteria.
- Interactive UI with modern styling and responsive design.
- Integration with JSON server to simulate a backend API.
- Display maps and user information.
- Sidebar navigation for easy access to different parts of the application.
- Real-time form handling and messaging.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: You can download it from [nodejs.org](https://nodejs.org/).
- **npm**: Node Package Manager is included with Node.js.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/worldwise.git
   ```
   Replace your-username with your GitHub username.

Navigate to the project directory:

```bash
cd worldwise
```

2. **Install dependencies**:

```bash
npm install
```

3.**Running the Project**:
To start the development server and run the project locally, use the following command:

```bash

npm run dev
```

This will start the development server using Vite on http://localhost:3000. Open this URL in your web browser to view the application.

### Available Scripts

In the project directory, you can run:

`npm run dev`

Runs the app in development mode using Vite.
Open http://localhost:3000 to view it in your browser.

`npm run build`

Builds the app for production to the dist folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

`npm run preview`

Serves the production build locally. This is useful for testing the final build before deploying.

`npm run server`

Runs a JSON server to serve city data. The server will run on http://localhost:9000. This script uses the json-server package to simulate a backend for handling city data.

## Project Structure

- main.jsx: The entry point for the React application, where the root component is rendered.
- App.jsx: The main component that handles the core application logic and routes.
- AppNav.jsx: Navigation component for the application.
- City.jsx: Component to display city information.
- CityItem.jsx: Component for individual city items.
- CityList.jsx: Component to list all cities.
- CountryItem.jsx: Component for displaying information about a country.
- Footer.jsx: The footer component for the application.
- Form.jsx: Handles user input and form submissions.
- Logo.jsx: Displays the application logo.
- Map.jsx: Integrates map functionality to display city locations.
- Message.jsx: Component to display messages to the user.
- PageNav.jsx: Navigation component for different pages within the app.
- Sidebar.jsx: Sidebar component for additional navigation options.
- Spinner.jsx: Displays a loading spinner.
- SpinnerFullPage.jsx: Full-page loading spinner for use during data loading.
- User.jsx: Displays user information.
- index.css: Contains all the global styles used in the application, ensuring the app is visually appealing and responsive.
- package.json: Manages the dependencies and scripts for the project.

## License

This project is licensed under the ISC License. See the LICENSE file for details.

## Author

Olha Chernysh
