# ReactJS-boilerplate-2024

## ReactJS app Setup

Create ReactJS app using [Vite](https://vitejs.dev/guide/)

    npm create vite@latest reactjs-boilerplate -- --template react

Husky Setup

    # Add husky to your ReactJS project
        Two ways we can install husky
            Automatic (recommended)
            Manual

        # Automatic (recommended)
            create ReactJS Project
                npm create vite@latest reactjs-boilerplate -- --template react
            cd reactjs-boilerplate
            Initialize a Git Repository (if not already a GitHub repo)
                git init
            initiate husky
                npx husky-init
                This command will create a prepare script in the package.json file.
            run npm install 
                This will create node_modules folder and .husky folder

