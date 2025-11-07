# FreeCodeCamp NPM Package Manager Learning Project

## Overview
This is the FreeCodeCamp boilerplate for learning how to manage Node.js projects and npm packages using package.json. It's part 1 of the Backend Challenges from FreeCodeCamp.

**Current State**: Fully configured and running in Replit environment.

## Project Architecture

### Technology Stack
- **Runtime**: Node.js
- **Framework**: Express.js v4.14.0
- **Frontend**: Static HTML/CSS

### Project Structure
```
.
├── public/          # Static assets (CSS)
├── views/           # HTML templates
├── server.js        # Main Express server
├── package.json     # npm configuration
└── README.md        # Original instructions
```

### Server Configuration
- **Development Port**: 5000 (configured via PORT environment variable)
- **Host**: Binds to all interfaces (0.0.0.0 in Replit)
- **Main Entry**: server.js
- **Workflow**: npm-server (PORT=5000 node server.js)

### Key Features
- Serves static HTML page at `/`
- Exposes package.json content at `/_api/package.json`
- Serves static assets from `/public`
- CORS configuration for FreeCodeCamp integration

## Recent Changes
**2025-11-07**: Initial Replit setup
- Installed npm dependencies (Express.js)
- Configured workflow for port 5000
- Set up deployment configuration for autoscale
- Created project documentation

## Deployment
The project is configured for autoscale deployment, suitable for this stateless educational web application. The server runs using `node server.js` in production.

## Notes
- The server.js file should not be edited as it's used for FreeCodeCamp verification
- Configuration is handled through environment variables (PORT)
- This is a learning project from FreeCodeCamp's Backend Development curriculum
