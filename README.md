# Discord Bot Integration Coding Assessment

## Overview
This assessment evaluates your proficiency with the MERN stack (MongoDB, Express.js, React.js, Node.js) by having you build a Discord integration application.

## Requirements

### Functionality
- Create a full-stack application with:
  - Frontend built with React.js
  - Backend using Express.js
  - MongoDB for data storage
- The application should:
  1. Allow users to connect with Discord via OAuth
  2. Redirect to a dashboard after successful authentication
  3. Enable users to send text messages to selected Discord channels from the application UI
  4. Display messages from the selected Discord channels

### Technical Specifications

#### Frontend (React.js)
- Create a clean, responsive UI using React
- Implement the following pages/components:
  - Landing page with a "Connect with Discord" button
  - Dashboard displaying:
    - User information from Discord (username, avatar)
    - List of available channels
    - Message input form
    - Message display area showing channel messages
  - Navigation between different sections
- State management of your choice (Redux, Context API, etc.)
- Proper error handling for API calls

#### Backend (Express.js)
- Implement Discord OAuth flow
- Create REST API endpoints for:
  - User authentication
  - Channel listing
  - Sending messages
  - Retrieving messages
- Connect to MongoDB for storing:
  - User authentication tokens
  - Message history (optional)
- Implement proper security measures for tokens

#### Database (MongoDB)
- Design and implement appropriate data schemas
- Store necessary user data and authentication information

### Deployment
- Deploy both frontend and backend on a hosting platform of your choice (Vercel, Netlify, Heroku, Render, etc.)
- Include proper environment variable configuration
- Provide links to both the live application and your GitHub repository

## Evaluation Criteria
1. **Functionality**: Does the application meet all requirements?
2. **Code Quality**: Is the code well-structured, readable, and maintainable?
3. **UI/UX**: Is the interface intuitive and responsive?
4. **Security**: Are proper security measures implemented for authentication?
5. **Documentation**: How well is the code and setup process documented?

## Submission Guidelines
1. Create a GitHub repository for your project with a detailed README.md
2. The README should include:
   - Project description
   - Setup instructions (local development)
   - Technologies used
   - API endpoints documentation
   - Live demo link
3. Deploy your application and provide the link in the README
4. Make your repository **private** until the assessment deadline
5. Submit the GitHub repository link via email to [your email address]

## Important Notes

### Timeline
- Assessment Start Date: 13-04-2024
- Assessment End Date: 4 Days From the Date it is sent to You at [12:00 AM]
- No commits will be accepted after the deadline

### Academic Integrity
- **This assessment evaluates your individual skills. Plagiarism will result in immediate disqualification.**
- You may use AI tools (like ChatGPT, GitHub Copilot) for reference and learning, but the core logic and implementation must be your own work.
- You will be required to explain your code and design decisions during the interview if you advance to that stage.

### Resources
- [Discord Developer Portal](https://discord.com/developers/docs/intro)
- [Discord OAuth2 Guide](https://discord.com/developers/docs/topics/oauth2)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Express.js Documentation](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)

## Getting Started

1. Register a new Discord application in the [Discord Developer Portal](https://discord.com/developers/applications)
2. Set up OAuth2 redirect URLs
3. Get your Client ID and Client Secret
4. Create a new Discord Bot and add it to a server for testing
5. Follow [Discord's Bot Documentation](https://discord.com/developers/docs/topics/oauth2#bots) to set up the proper permissions

Good luck! We look forward to reviewing your submission.
