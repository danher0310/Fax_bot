## ******BOT TO CHECK AND NOTIFY NEW FILES IN DOCTOR'S FOLDER******

 ![header](https://raw.githubusercontent.com/danher0310/Fax_bot/pdfconvert/img/pythonbot.jpg) 

**DESCRIPTION:**

This bot has several uses. with this bot the user can move the file to a specific folder, this folder is from different doctors, and each doctor has their group to be notified, when they have a new file, in a different folder. also inside the folder, each doctor has a different folder to classify the new files. 

When the files are in the respective folder, the bot saves the path file, and date created in the database, and also creates a copy in another path to save the files in other programs, but in this case, if the file is a pdf, the bot converts the PDF file in a JPG file to process. 

Also if the user put files in specific folder the bot print the document and move to archive 

**USAGE:**

First after all, you need create your bot in https://t.me/BotFather on telegram, after that you should be have your token to use the code.

To use the code you need run `*pip install -r requirements.txt*`

after that you need configure your .conf file:

1. Copy your token from botfather.
2. Execute fax_sql.sql in your database
3. run the code