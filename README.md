![Hackatime Badge](https://hackatime-badge.hackclub.com/U0857UWECTS/text_share)

# Text Share

Text share is a simple node.js app that utilizes websockets to sync text in a text box accross multiple users.

## Installation

1. Clone this repo and run ```npm i``` to install dependencies

2. Create a ```.env``` file as following:
```vim
PASSWORD="<insert your secret password here>"
PORT=<optional, insert your port here. default is 8080>
```

## Usage

Run ```npm run start``` to run the server, and open ```http://localhost:8080``` in your browser (if you set the port value in the ```.env``` file, replace the port number to the one you set).

Aditionally, if you have the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed, you can run ```heroku local```.
