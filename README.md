# Capstone Project

## Description

This project is a application that displays the latest news about Batik using the Google News API via SearchAPI.io. The application is built with Node.js, Express.js, and uses EJS as its template engine. The interface is enhanced with Bootstrap for a responsive and appealing design.

## Key Features
- Fetch data from an external API (SearchAPI.io) for Batik news.
- Display news in responsive cards with images, titles, short descriptions, and links to read more.
- Responsive interface using Bootstrap.

## Prerequisites
- Node.js installed on your machine.
- API Key from SearchAPI.io to access the Google News API.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/KarsaNusa/karsa-nusa-newsapi.git
   cd capstone
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in your project directory and add your API Key:
   ```env
   APP_KEY=your_api_key_here
   ```

4. Run the application:
   ```bash
   npm start
   ```

5. Access the application at [http://localhost:3000](http://localhost:3000).

## Project Structure
- `server.js`: Main file for server configuration and routing.
- `index.ejs`: Main template for displaying news in the browser.
- `package.json`: Contains project information and dependencies.
- `public/`: Directory for static files (CSS, JavaScript), currently unused.

## Dependencies
- [Express.js](https://expressjs.com/): Backend framework for Node.js.
- [EJS](https://ejs.co/): Template engine for rendering dynamic pages.
- [Node-fetch](https://github.com/node-fetch/node-fetch): Used for API access.
- [@dotenvx/dotenvx](https://www.npmjs.com/package/@dotenvx/dotenvx): For managing environment variables.

## License
This project is licensed under ISC.

## Additional Notes
If you encounter issues while running the project, ensure your API Key is valid and meets SearchAPI.io requirements.
