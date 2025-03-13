# News Media Platform

This is a backend application for a News Media Platform built using the MERN stack (MongoDB, Express, React, Node.js). The application allows users to view, add, and delete news articles.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd news-media-backend
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your MongoDB connection string:
   ```
   MONGODB_URI=<your-mongodb-connection-string>
   ```

## Usage

To start the server, run the following command:
```
npm start
```
The server will run on `http://localhost:5000`.

## API Endpoints

- **GET** `/api/news` - Retrieve all news articles.
- **POST** `/api/news` - Create a new news article. Requires a JSON body with `title`, `content`, and `author`.
- **DELETE** `/api/news/:newsId` - Delete a news article by ID.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.