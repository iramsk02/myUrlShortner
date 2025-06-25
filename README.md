

# URL Shortener

A simple URL Shortener web application built using Node.js, Express, MongoDB, and EJS.

### https://myurlshortner-pogo.onrender.com/

## Features
- Shorten long URLs into short, shareable links.
- Redirect shortened URLs to their original destination.
- Simple and user-friendly UI.

## Tech Stack
- **Frontend:** EJS, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/url-shortener.git
   cd url-shortener
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file and add:
   ```sh
   MONGODB_URI=your_mongodb_connection_string
   BASE_URL=http://localhost:3000
   ```

4. Start the server:
   ```sh
   npm start
   ```
   The app will run on `http://localhost:3000`.

## API Endpoints
| Method | Endpoint         | Description                |
|--------|-----------------|----------------------------|
| POST   | `/shorten`      | Shorten a long URL        |
| GET    | `/:shortCode`   | Redirect to original URL  |

## Contributing
Feel free to submit issues or pull requests!

