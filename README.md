# Blog Admin
## Project Overview: 
1. [BlogAPI](https://github.com/Arussel1/blogAPI): The backend of the blog application built using Node.js and Express, handling routes for posts, users, and comments. GitHub: BlogAPI.

2. [BlogClient](https://github.com/Arussel1/blogClient): The user-facing client application built with React, TypeScript, and TailwindCSS. It allows users to:

   + Create and log in to accounts.
   + View posts.
   + Post comments. GitHub: BlogClient.

[AdminClient](): The admin-facing client with extended permissions, including:

    + All user permissions from BlogClient.
    + Creating and managing posts.
    + Changing post status (e.g., publish/unpublish).
    + Deleting comments.
**Demo**: :point_right:[**Not yet ready**]():point_left:. <br>
Please allow up to 1 minutes for the website to load.
## Install and set up
Follow these step below to set up the website in your local machine.

### Steps:
1. Clone the repo: <br>

```bash
git clone https://github.com/YourUserName/blogClient
```

2. Navigate to the project folder:<br>

```bash
cd blogClient
```

3. Install the dependencies:<br>

```bash
npm install
```

4. Create the .env file:<br>

```bash
touch .env
```

5. Add your environment inside the file: <br>

```bash
VITE_BACKEND_WEB=
```

6. Start the dev server:<br>

```bash
npm run dev
```


After these step, you should browser and navigate to http://localhost:5173 to view the application in action.
## Production:

To prepare the project for production deployment, please use the following command: <br>

```bash
npm run build
```
## Tech stack:
+ [React](https://react.dev/): as runtime environment. <br>
+ [TailwindCSS](https://tailwindcss.com/): Utility-first CSS framework for styling. <br>
+ [Typescript](https://www.typescriptlang.org/): Strongly-typed programming language for building robust applications. <br>
+ [Axios](https://axios-http.com/): Promise-based HTTP client for making API requests. <br>
+ [TinyMCE](https://www.tiny.cloud/): Powerful and customizable web-based rich text editor that allows users to create and edit content