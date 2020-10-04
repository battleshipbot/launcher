# launcher

## Self-hosting
Make sure you have both docker, docker-compose and git set up.  
Clone the project recursively `git clone --recurse-submodules git@github.com:battleshipbot/launcher.git`  
Rename `example.env` to `.env`  
Fill out the env file  
Build the containers using `docker-compose build`  
Start the bot using `docker-compose up -d`  
Stop the bot using `docker-compose down`
