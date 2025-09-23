# FreeCodeCamp NPM Package Management Project

## Project Overview
This is a Node.js Express web application that serves as part of the FreeCodeCamp backend challenges. It demonstrates package management with npm and includes both frontend and backend components.

## Project Structure
- `server.js` - Main Express server file
- `package.json` - NPM configuration and dependencies
- `views/index.html` - HTML frontend
- `public/style.css` - CSS styling
- `README.md` - Original project documentation

## Technical Setup
- **Language**: Node.js with Express framework
- **Port**: 5000 (configured for Replit environment)
- **Host**: 0.0.0.0 (allows Replit proxy access)
- **Dependencies**: Express ^4.14.0

## API Endpoints
- `GET /` - Serves the main HTML page
- `GET /_api/package.json` - Returns package.json content as text
- `GET /public/*` - Serves static files from public directory

## Configuration Changes for Replit
- Modified server to bind to 0.0.0.0:5000 instead of default port 3000
- Added trust proxy setting for Replit's proxy environment
- Configured workflow to run npm start
- Set up autoscale deployment target

## Recent Changes
- 2025-09-23: Initial Replit environment setup
  - Configured server for port 5000 and 0.0.0.0 binding
  - Added proxy trust configuration
  - Set up workflow and deployment configuration
  - Verified all endpoints working correctly