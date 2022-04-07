# reactapp

- In this document, i'm giving instructions for how to create react app and install tailwind css.

## Instructions

1.  Go to your terminal and type

        'npx create-react-app my-project'

    for create a new project. and it takes few mins to create react project and install all packages

2.  afterthat type

        'cd my-project'

    now you are in your newly created project.

3.  Now you can open your newly created project into VS Code all the files and packages are already installed.

4.  Use

         'npm start'

    to start the development.Your app will show in localhost.

Let's see how to install tailwind in this cnewly created app.

5.  Copy and paste the below command in terminal to inatll tailwind and it's peer dependencies via npm

          'npm install -D tailwindcss postcss autoprefixer'

6.  Copy and paste the below command in terminal, it generates two files, 'tailwind.config.js' and 'postcss.config.js'

          'npx tailwindcss init -p'

7.  Go to your 'taiwind.config.js' file, Cop and paste the the content section into your module exports section

           'content: [
               "./src/**/*.{js,jsx,ts,tsx}",
            ],'

8.  Go to './src/index.css' file.Copy and paste the below content to add '@tailwind' directives.

             '@tailwind base;
              @tailwind components;
              @tailwind utilities;'

9.  The tailwind css successfully added into your page.

10. Now use
    'npm run start'
    to run your build process.
