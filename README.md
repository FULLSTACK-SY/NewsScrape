# Mongo News Scrapper

This app uses the axios and cheerio NPM packages to scrape news articles, and Mongoose to create models for easy use with MongoDB.

## User Stories

1. Create sign up as a new user, and log in as an existing user.
2. Make a button to scrape articles
3. User can click a button to add an article to saved articles tab.
4. User can add a note to any of saved articles.
5. User can delete a note created on any of saved articles.
6. User can see notes left by other users on my saved articles.
7. User can remove an article from saved list.
8. At any time user can clear all data in the db by going to the `/clear` route.
9. If user request a page that does not exist , show 404 error.
10. If user request a page and do not have permission to acccess show 403 error. (Ex: accessing saved artiles without being authenticated)

## Download and Installation

If you want to install this on your local machine, first install all modules with `npm i`.

This application uses gulp for task automation as well as running a live server. Once all dependencies are installed you can easily get the Bootstrap and jQuery source files by running `gulp getfiles`. This will create a directory in public called vendor, and it will store the Bootstrap and jQuery core files. It will then automatically move the needed files from `./public/vendor` to `./public/js` & `./public/css`. Once Bootstrap and jQuery files are moved the vendor directory can be deleted.

The live server is set as the default gulp task. To run the server first start `mongod` from the terminal, and then execute the `gulp` command. This starts up browser-sync, which auto-reloads the browser on any html and css change, as well as re-starts the node server upon any change to a .js file.

Once gulp is watching for changes it will automatically run the tasks to compile scss down to css, as well as minify the js and css files.
