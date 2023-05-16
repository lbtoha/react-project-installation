# Simple React Project Installation ⚛️ and MongoDB server create using express

By using the following comment anyone can create a simple react project.

## Create react app:

```shell
npm create vite@latest name-of-your-project -- --template react
```
### Install react router dom:
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
1. Install the Firebase:

```shell
npm install  firebase
```
2. Initialize a Firebase project in your director:
```shell
firebase init
```

3. Deploy your project to Firebase by running the following command:
```shell
firebase deploy
```
## Vercel Deployment
### New user

1. Create a Vercel account:
   - Go to the [Vercel website](https://vercel.com) and sign up for an account.
   - Follow the on-screen instructions to create your account.

2. Install the Vercel CLI:
   - Open your terminal or command prompt.
   - Run the following command to install the Vercel CLI globally using npm:
     ```shell
     npm install -g vercel
     ```

3. Build your project:
   
     ```shell
     npm run build
     ```

4. Log in to Vercel:
   - In your terminal, run the following command to log in to your Vercel account:
     ```shell
     vercel login
     ```

5. Deploy your project:
     ```shell
     vercel
     ```
 ### Existing User

1. Build your project:
     ```shell
     npm run build
     ```

2. Deploy your project:
   - Navigate to the root directory of your project using the terminal.
   - Run the following command to deploy your project to Vercel:
     ```shell
     vercel
     ```
  
## Simple Express Server and MongoDB Install 
- install the npm packages "express", "cors", "dotenv", "jsonwebtoken" and "mongodb" in one command
```shell
npm install express cors dotenv jsonwebtoken mongodb
```
