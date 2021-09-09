# Docker Compose Projects

When you finished cloning the repo

Make chmod -R 755 app/src to let apache read the folder content

Change the config/config.php file to your domain and your path

Open your phpmyadmin on port 8001 and create a new database and call it **hashtag** then import hashtag.sql from install folder (will make it automatic later)

Edit connect.php file in config folder and set the username and password of the database you've created

I've made it DBUser/DBPassword by default in the .env file so don't miss to change it
