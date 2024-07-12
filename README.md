# InfoStream

InfoStream is a web application that aggregates and displays news articles from various sources using the NewsAPI. This project is built using TypeScript, HTML/CSS, and React, with Firebase for backend services and Git for version control. The goal of InfoStream is to provide users with a centralized platform to stay updated on the latest news across different categories.

## Features

- **News Aggregation:** Fetches and displays news articles from multiple sources.
- **Category Filtering:** Allows users to filter news articles based on categories like technology, sports, business, and more.
- **Responsive Design:** Optimized for both desktop and mobile devices.
- **Real-Time Updates:** News articles are updated in real-time to ensure users get the latest information.
- **User Authentication:** Users can sign up, log in, and manage their profiles.

## Tech Stack

- **Frontend:**
  - TypeScript
  - React
  - HTML/CSS

- **Backend:**
  - Firebase Authentication
  - Firebase Firestore
  - Firebase Hosting

- **APIs:**
  - NewsAPI

## Getting Started

### Prerequisites

- Node.js and npm installed
- Firebase account
- NewsAPI key

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AryanKumar1401/Info-Stream.git
    cd Info-Stream
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Set up Firebase:

- Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
- Enable Authentication and Firestore Database.
- Get the Firebase configuration and replace it in the `firebaseConfig` object in your project.

4. Set up NewsAPI:

- Sign up for an API key at [NewsAPI](https://newsapi.org/).
- Replace the placeholder API key in the project with your own.

5. Run the development server:

    ```bash
    npm start
    ```

The application will be available at `http://localhost:3000`.

### Deployment

To deploy the application to Firebase Hosting:

1. Build the project:

    ```bash
    npm run build
    ```

2. Deploy to Firebase:

    ```bash
    firebase deploy
    ```

## Usage

- **Home Page:** Displays the latest news articles.
- **Category Filter:** Use the navigation bar to filter news by categories.
- **Authentication:** Users can sign up or log in to save their preferences.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please contact:

Aryan Kumar - [ak2488@cornell.edu](mailto:ak2488@cornell.edu)
