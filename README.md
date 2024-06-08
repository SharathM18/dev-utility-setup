# Setup Guide

## React

#### Install React with vite
```bash
npm create vite@latest
```

#### Install React Router DOM
```bash
npm install react-router-dom
```

#### Install React Redux & React Redux Toolkit
```bash
npm install react-redux @reduxjs/toolkit
```

#### Install React Hook Form & Zod
```bash
npm install react-hook-form zod
```

#### Install TinyMCE React component
```bash
npm i @tinymce/tinymce-react
```

## Tailwind CSS

#### Install Tailwind CSS with Vite
```bash
npm install -D tailwindcss postcss autoprefixer
```
```bash
npx tailwindcss init -p
```

#### Configure your template paths to `tailwind.config.js` file.
```
content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
```

#### Add the Tailwind directives to your `./src/index.css` file.
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Installation of `prettier-plugin-tailwindcss` for automatic class sorting with Prettier
```bash
npm install -D prettier prettier-plugin-tailwindcss
```

#### Create a file named `.prettierrc` in the root directory
```
{
  "plugins": ["prettier-plugin-tailwindcss"]
}
```
