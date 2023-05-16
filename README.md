# React Project Installation

By using the following comment anyone can create a simple react project from this `README.md` file using code blocks.

Create react app:

```shell
npm create vite@latest name-of-your-project -- --template react
```

Install react router dom:

```shell
npm install react-router-dom localforage match-sorter sort-by
```
### Install Tailwind CSS with Vite:
```shell
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
Add the paths to all of your template files in your `tailwind.config.js` file.
```plaintext
content: [ "./index.html", "./src/**/*.{js,ts,jsx,tsx}",],
```
