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

If you want to install this on your local machine copy folder and give CLI :
 `npm i`
