# Netflix Clone

A full-stack Netflix clone that mimics the core features of the Netflix streaming platform. This project includes user authentication, a responsive UI, and the ability to browse, search, and view details about movies and TV shows.

## Features

- **User Authentication**: Sign up, log in, and manage user profiles.
- **Browse Content**: View a catalog of movies and TV shows categorized by genres.
- **Search**: Find movies or TV shows by their titles.
- **Responsive Design**: Works seamlessly across desktops, tablets, and mobile devices.
- **Dynamic Data**: Fetched using APIs (e.g., TMDB API) to display real movie/show data.
- **Streaming Simulation**: Embedded trailers for selected content.

---

## Tech Stack

- **Frontend**: React.js, Redux, Material-UI, CSS3, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens), bcrypt
- **API**: TMDB (The Movie Database) API for movie/show data

---

## Installation and Setup

Follow these steps to get the Netflix clone running locally on your system:

### Prerequisites

1. **Node.js**: Download and install [Node.js](https://nodejs.org/).
2. **MongoDB**: Set up a local or cloud MongoDB instance.
3. **API Key**: Get an API key from [TMDB](https://www.themoviedb.org/documentation/api) by creating an account.

### Clone the Repository

```bash
git clone https://github.com/pawarchandrakant29/netflix-clone.git
cd netflix-clone
```

### Backend Setup

1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` folder and configure the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret_key
   TMDB_API_KEY=your_tmdb_api_key
   ```
4. Start the backend server:
   ```bash
   npm start
   ```
   The backend server will start on `http://localhost:5000`.

### Frontend Setup

1. Navigate to the `frontend` folder:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `frontend` folder and add the backend API base URL:
   ```env
   REACT_APP_API_URL=http://localhost:5000
   ```
4. Start the frontend server:
   ```bash
   npm run dev
   ```
   The frontend server will start on `http://localhost:5173`.

---

## Usage

1. Open `http://localhost:5173` in your browser.
2. Sign up for an account or log in with existing credentials.
3. Browse movies and TV shows, search for content, and explore details.
4. Enjoy the streaming simulation with trailers!

---

## Acknowledgements

- [TMDB API](https://www.themoviedb.org/documentation/api) for providing movie/show data.
- [Netflix](https://www.netflix.com) for the inspiration.
- Open-source libraries and tools used in this project.

