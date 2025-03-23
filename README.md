# URL Shortener

A simple URL Shortener web application built using Node.js, Express, MongoDB, and EJS.

## Features
- Shorten long URLs into short, shareable links.
- Redirect shortened URLs to their original destination.
- Simple and user-friendly UI.

## Tech Stack
- **Frontend:** EJS, CSS, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Installation

1. Clone the repository:

   git clone https://github.com/your-username/url-shortener.git
   cd url-shortener
   Here’s a **README.md** file for your URL Shortener app:  


# URL Shortener

A simple URL Shortener web application built using Node.js, Express, MongoDB, and EJS.

## Features
- Shorten long URLs into short, shareable links.
- Redirect shortened URLs to their original destination.
- Track usage statistics (click count, created date).
- Simple and user-friendly UI.

## Tech Stack
- **Frontend:** EJS, CSS, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Hosting:** (Specify if you are hosting it)

## Installation

1. Clone the repository:

   git clone https://github.com/your-username/url-shortener.git
   cd url-shortener


2. Install dependencies:

   npm install
 

3. Set up environment variables:
   Create a `.env` file and add:

   MONGODB_URI=your_mongodb_connection_string
   BASE_URL=http://localhost:PORT


4. Start the server:

   npm run dev

   The app will run on `http://localhost:PORT`.

## API Endpoints
| Method | Endpoint         | Description                |
|--------|-----------------|----------------------------|
| POST   | `/shorten`      | Shorten a long URL        |
| GET    | `/:shortCode`   | Redirect to original URL  |

## Contributing
Feel free to submit issues or pull requests!

