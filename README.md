# node-azure
Demo getting Node to run on Azure

## Create Microsoft and Azure accounts
1. Hit up [Microsoft Azure's site](https://azure.microsoft.com/en-us/)
2. Click [Free Trial](https://azure.microsoft.com/en-us/pricing/free-trial/) or [Try it now](https://account.windowsazure.com/signup)
3. Create a Microsoft Account and verify your email address
    * You should now be automagically logged in
4. Fill out your information to begin free Azure trial
    * Name
    * Work Phone
    * Verification by phone (Phone number will be verified by Microsoft)
    * Verification by card (Credit card info is kept if you migrate to a paid plan)
    * Agreement (Check the box and click Sign up)
    
## Create an Azure Web Application
1. Go to **Web Apps** and select **+ Add**
2. Enter a name for the web app (e.g. kamrenz will become [http://kamrenz.azurewebsites.net/](http://kamrenz.azurewebsites.net/))
    * Select a **Resource Group** and **App Service plan/Location**
    * Click **Create**
3. Your Azure server will now deploy the new website... this will take a few seconds
    * After deployment you will now see **kamrenz** listed as one of your Web Apps
    
## Create a Local Application
1. Open an editor and create an index.html page
    * You can use the one in this project (i.e. index.html)
2. Create a basic Node server file
    * You can use the one in this project (i.e. server.js)
3. Install Node to run our server.js file
    * Here is a great [tutorial](http://blog.teamtreehouse.com/install-node-js-npm-mac) on getting it installed on a Mac
    Get the OSX missing package manager [Homebrew]()
    * You will install [Homebrew](http://brew.sh/)
    * You will install [Node & NPM](https://nodejs.org)
4. Create a package configuration file
    * This configuration file will keep track of the packages Node will be using 
        * Express is a package utilized for serving up web pages
    * In the terminal run: `npm init`
        * Make sure you are in the directory where the server.js and index.html files are located
        * This will create the needed package.json file
        * Don't sweat too much the questions it asks you :)
        * P.S. name means application name not your name ;)
        * Say yes to let the package.json file be created
5. Install the Express Web Framework
    * Express is a Node package
    * Express will be installed via the Node Package Manager [NPM](https://www.npmjs.com/)
        * No worries NPM came with our install of Node.js
    * Now we can install Express
        * In the terminal run: `npm install express --save`
        * Take a look at the package.json file and you will see express added to the dependencies
6. Start Express and enjoy your site
    * In the terminal navigate to the directory where your server.js and index.html
    * Run: `node server.js` to start up your local server
    * Go to http://localhost:8080 to see your web page
        * If it works you should see `Hello Azure` in the browser

## Create a GitHub Repo 
    * Push your local code into the GitHub repo
    
## What's next
    * Install Azure CLI
    * Login to Azure account
    * Get publishing profile
    * Generate deployment scripts
    * Setup Azure Web App for Continuous Integration    



