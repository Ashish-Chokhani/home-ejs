# Home EJS

This project is a simple blogging website using EJS templating with Node.js, Express, and MongoDB. The application allows users to compose posts and view them on the home page. It also includes static pages for About and Contact.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)

## Overview
The Home EJS project is a web application built with Node.js and Express.js, using EJS for templating and MongoDB for database management. Users can create, read, and view blog posts.

## Features
- Create and view blog posts
- Static About and Contact pages
- EJS templating for dynamic content rendering

## Getting Started

### Prerequisites
- Node.js
- MongoDB

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ashish-Chokhani/home-ejs.git
   ```
2. Navigate to the project directory:
   ```bash
   cd home-ejs
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start MongoDB:
   ```bash
   mongod
   ```
5. Run the application:
   ```bash
   node app.js
   ```
6. Open your web browser and navigate to http://localhost:3000.

### Usage
- Home Page: Lists all the posts with a snippet and a "Read More" link.
- Compose Page: Allows you to create a new post.
- About Page: Static about page with predefined content.
- Contact Page: Static contact page with predefined content.

### Files
Directory Structure
home-ejs
```bash
├── public
│   └── css
│       └── styles.css
├── views
│   ├── partials
│   │   ├── header.ejs
│   │   └── footer.ejs
│   ├── about.ejs
│   ├── compose.ejs
│   ├── contact.ejs
│   ├── home.ejs
│   └── post.ejs
├── .gitignore
├── app.js
├── package-lock.json
└── package.json
```

### Contributing
Feel free to submit issues and enhancement requests. Fork the repository and make your changes in a separate branch, then submit a pull request.

- Fork the repository
- Create a new branch (git checkout -b feature-foo)
- Commit your changes (git commit -am 'Add some foo')
- Push to the branch (git push origin feature-foo)
- Create a new Pull Request
