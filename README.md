MovieSearch App
Welcome to MovieSearch! This is a step-by-step guide to building our application. We'll use CodeSandbox.io to generate code at each intermediate step, making it easy to test.

Overview
I've already created an appbase app with the MovieSearch dataset indexed in it. You can browse it with DejaVu over here:

Open MovieSearch DejaVu

Note: Please ensure you're logged in to your appbase account to access the DejaVu interface.

Getting Started
Click on the above link to open MovieSearch DejaVu.
Click on the "Open React" button.
Follow the steps below to set up your local development environment:
bash
Copier le code
# Create a new React app
npx create-react-app moviesearch
cd moviesearch
npm start
Project Structure
java
Copier le code
moviesearch
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── package-lock.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── registerServiceWorker.js
Installation
Install the ReactiveSearch library:

bash
Copier le code
npm install @appbaseio/reactivesearch
Usage
Start building your application by importing necessary components from ReactiveSearch and integrating them into your React components.

Note
We'll be utilizing DejaVu UI for managing Elasticsearch indices and data. Make sure to explore its features to effectively work with our dataset.
