# Simple React Project Installation and MongoDB server create using express

By using the following comment anyone can create a simple react project.

## Create react app:

```shell
npm create vite@latest name-of-your-project -- --template react
```
- Install react router dom:
```shell
npm install react-router-dom localforage match-sorter sort-by
```
### Install Tailwind CSS with Vite 
```shell
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
Add the paths to all of your template files in your `tailwind.config.js` file.
```plaintext
content: [ "./index.html", "./src/**/*.{js,ts,jsx,tsx}",],
```
 Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.
```plaintext
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### Install daisyUI as a Tailwind CSS plugin 🌼 
Install daisyUI:
```shell
npm i daisyui
```
Then add daisyUI to your `tailwind.config.js` files:
```plaintext
plugins: [require("daisyui")],
```
## Firebase Deployment 🔥 
- New User:
To deploy your project to Firebase, you can follow these steps:
1. Install the Firebase CLI globally by running the following command:

```shell
npm install -g firebase-tools
```
2. Log in to your Firebase account using the Firebase CLI:
```shell
firebase login
```
3. Initialize your project by running the following command in the root directory of your project:
```shell
firebase init
```

- Alrady setup firebase on this pc

## Simple Express Server and MongoDB Install 
- install the npm packages "express", "cors", "dotenv", "jsonwebtoken" and "mongodb" in one command
```shell
npm install express cors dotenv jsonwebtoken mongodb
```
