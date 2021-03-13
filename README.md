# convrt.io

Convrt.io is an alternative chatting interface for the messenger provided by LinkedIn. Along with a well arranged design, convrt.io offers the possibility to sort your different contacts via a labeling functionality. The long-term goal is to implement an intelligent assistant, which helps the user organizing his messaging as well as his appointment scheduling.

## Prerequisities

You need to have docker installed on your system.

## Running the project

Simply run:

`make run`

After running through the setup CONVRT should be available at localhost:5000. Sign up with your LinkedIn credentials,
sign in afterwards and get your conversations from LinkedIn by clicking the refresh button on the top right site. After a few minutes, your messages should appear in the interface. By clicking the refresh button again, the application will crawl any new message from LinkedIn as well as inserting the messages you sent via convrt.io back into LinkedIn.
