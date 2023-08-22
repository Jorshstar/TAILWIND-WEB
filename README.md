# Tailwind Manage Landing Page

This is a project built with Tailwind css. I worked on this while learning Tailwind css 

![Alt text](/img/Landingpage.jpeg?raw=true)

# Usage

Install dependencies (Tailwind)

npm install

Run the Tailwind CLI to compile the *input.css* during development. The output file is *css/main.css*

Package.json file
{
  "name": "tailwind-learning",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "build": "tailwindcss -i ./styles.css -o ./css/main.css",
    "watch": "tailwindcss -i ./styles.css -o ./css/main.css --watch"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "tailwindcss": "^3.3.2"
  }
}
npm run watch

To build once run...

npm run build

You can edit the scripts in package.json and the tailwind.config.js file to change input/output locations
