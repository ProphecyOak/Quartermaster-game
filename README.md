# Quartermaster-game

## Contributing
To contribute you will need to clone the github repo 
```
git clone https://github.com/troop380/Quartermaster-game.git
```

You can make edits on you local machine, you will need to install Python as well as the required libraries through pip
```
pip install -r requirements.txt
```

To run the server
```
python chat.php
```

You then should be able to connect to http://localhost:5000 in your local browser.  You could connect from other conputers on your local network or from the internet if you setup port redirection on you internet firewall.

Pull request

## Persistent data storage - Redis
To store data for the server you will need a redis server, for development on a windows box you can install docker desktop then install a redis docker container
To start the docker container
```
docker run -d -p 6379:6379 redis
```
