# ReactJS-boilerplate-2024

## ReactJS app Setup

Create ReactJS app using [Vite](https://vitejs.dev/guide/)

    npm create vite@latest reactjs-boilerplate -- --template react

## Husky Setup

### Add husky to your ReactJS project

- #### Two ways we can install husky

    - Automatic (recommended)
    - Manual

        #### Automatic (recommended)

            Create ReactJS Project
      
                > npm create vite@latest reactjs-boilerplate -- --template react
      
                > cd reactjs-boilerplate

            Initialize a Git Repository (if not already a GitHub repo)
      
                > git init

            Initiate husky
      
                > npx husky-init
      
                This command will create a prepare script in the package.json file.

            > run npm install
      
                This will create node_modules folder and .husky folder
        
        ### Manual

            Install Husky
      
                > npm install husky --save-dev

            Add a prepare script in the package.json file
      
                > npm pkg set scripts.prepare="husky"
            
            then run prepare script
      
                > npm install or npm run prepare
      
                This will create node_modules folder and .husky folder


- #### Test husky

  Add a basic rules in eslint.config.js
  
      'no-var': 'error',

   modify the App.jsx file
  
      replace const with var

   Try to commit the file, you will see an error
  
      error  Unexpected var, use let or const instead  no-var
    
  <strong>husky works!</strong>
