this code relies on some python dependencies: numpy, pymongo, flask

it also requires mongodb to be running. An example:
```
~/mongodb/bin/mongod --bind_ip 127.0.0.1 --dbpath pilot3db --logpath pilot3db.log --port 5002
```

Can simply create a Heroku dyno app and link to GitHub and it will automatically serve the site
