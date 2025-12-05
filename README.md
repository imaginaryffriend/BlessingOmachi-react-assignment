# BlessingOmachi-react-assignment
React project for graded assignment
# React Assignment Submission

Note: Due to technical constraints (working from mobile device), I'm submitting the written answers. The React project setup would normally be done on a computer with Node.js installed.

Answers to Questions:

 1. What is NPM & package.json?

- NPM (Node Package Manager) is like an "app store" for JavaScript code. It allows developers to:
- Share reusable code packages
- Install tools and libraries needed for projects
- Manage different versions of dependencies

- package.json is the configuration file for a Node.js project. It contains:
- Project name and version
- List of required packages (dependencies)
- Scripts to build and run the project
- Author information and licensing

2. What is Vite?

Vite is a modern build tool and development server for web projects. Key advantages:
- Extremely fast - Starts development server in milliseconds
- Hot Module Replacement - Changes appear instantly without full page reload
- Optimized for production - Creates smaller, faster-loading bundles
- Simpler configuration than older tools like Webpack

Vite is now the recommended tool for creating new React projects because of its speed and simplicity.


*** The React project setup involves these key steps: ***

1. Prerequisites Installation

Install Node.js from nodejs.org (includes NPM)
Verify installation in terminal:

bash
node --version
npm --version

2. Project Creation

Using the recommended tool Vite:

bash
npm create vite@latest project-name --template react
This command:

Downloads Vite tools
Creates project folder with basic structure
Sets up React with necessary configuration

3. Project Structure Created

4. Installing Dependencies

bash
cd project-name
npm install
This installs all packages listed in package.json including:

React and React DOM
Vite and its plugins
Development tools

5. Running the Development Server

bash
npm run dev
Starts local development server at http://localhost:5173
Enables hot module replacement (instant updates)
Provides development tools and error overlays

6. Building for Production

bash
npm run build
Creates optimized, minified files in dist/ folder
Ready for deployment to web hosting services

7. Version Control Setup

bash
git init
git add .
git commit -m "Initial commit"
Initialize Git repository
Track all project files
Commit the initial setup

8. Deployment to GitHub

bash
git remote add origin https://github.com/username/repo-name.git
git push -u origin main
Connect local repository to GitHub
Push code to remote repository
Make project accessible online
