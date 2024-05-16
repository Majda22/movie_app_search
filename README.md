![Capture d'écran 2024-05-16 141251](https://github.com/Majda22/movie_app_search/assets/167624199/d6b86c16-caa9-4c7d-a61f-a6ae49a877fd)# MovieSearch App README

Welcome to the MovieSearch app development journey! In this guide, we will walk you through step-by-step instructions to build an application utilizing the MovieSearch dataset indexed in an appbase app. To visualize and interact with the dataset, we'll leverage DejaVu, an intuitive UI for Elasticsearch.

## Prerequisites

Before diving into the development process, ensure you have access to the following:

- **Appbase Account**: Create an account on [Appbase.io](https://appbase.io/) to set up your appbase app and index the MovieSearch dataset.
- **DejaVu The missing web UI for Elasticsearch**: Access the DejaVu interface to browse the indexed data and configure settings as needed.
- **Codesandbox.io**: We'll use Codesandbox.io to generate code at each intermediate step, facilitating testing and development.

## Getting Started

1. **Initialize React App**:

```bash
npx create-react-app moviesearch
cd moviesearch
npm start
```

2. **Install Dependencies**:

```bash
npm install @appbaseio/reactivesearch
```

## Browsing MovieSearch Dataset

To explore the MovieSearch dataset, navigate to the DejaVu interface using the following link:

[Open DejaVu The missing web UI for Elasticsearch](https://dejavu.appbase.io/?appname=movies-demo-app&url=https://81719ecd9552:e06db001-a6d8-4cc2-bc43-9c15b1c0c987@appbase-demo-ansible-abxiydt-arc.searchbase.io&mode=view)

## Project Structure

Your project structure should resemble the following:

```
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
```

## Development Flow

Throughout the development process, we'll adhere to the following flow:

1. Initialize React app.
2. Install required dependencies.
3. Explore the MovieSearch dataset using the DejaVu interface.
4. Develop the application incrementally, generating code snippets in Codesandbox.io at each step for easy testing.
5. 
## Demostration

You can test the demo by clicking on the image below:

[![Demo][Uploading Capture d'écran 2024-05-16 141251.png…]()](https://5ddg9h-3000.csb.app/)

## Utilizing DejaVu for Elasticsearch

We'll harness the power of DejaVu, a comprehensive UI for Elasticsearch, to seamlessly interact with our indexed MovieSearch dataset. This interface offers intuitive navigation and visualization options, enhancing our development experience.

Let's embark on this exciting journey to build our MovieSearch application!

Feel free to reach out if you encounter any challenges or have questions along the way. Happy coding! 🚀
