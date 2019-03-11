# Installation

Node Version: v8.9.3

Just clone this repo or download the zip file. `cd` into the directory and run

    npm install

To run the migrations go to server directory then run the following command

    cd server

then run the following command

    ../node_modules/.bin/sequelize db:migrate

Then return to app root

    cd ..

Then to start the server run

    npm start

Then goto http://localhost:8080


SELECT tasks.t_name, tasks.slider_id , services.name from tasks
INNER JOIN services ON services.slider_id = tasks.slider_id 
INNER JOIN products ON products.slider_id = tasks.slider_id
INNER JOIN news ON news.slider_id = tasks.slider_id

login page
