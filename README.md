# Practical Test

Install the server
```sh
npm i
```
Read the server code and understand its function

Start the server
```sh
node index.js
```
Open the client http://localhost:3000/client (the file is located in the static/client directory)

Client application should be able to do the following:
1. Show if the Client is connected to the server or not
2. Display a candlestick chart of the incoming data according to an aggregation period (default should be 10 seconds)
3. Have a dropdown menu that allows to choose the aggreagation period (10 seconds, 30 seconds, 1 minute ...)

Questions:
1. how would you allow saving and sending of historic data?
2. how would you reduce the amount of data sent to the client and make sure the data is correct according to the aggregation period they chose?

Answer the questions in the Answers.txt file

Choose one of the answers you provided and refactor the server/client accordingly

Zip the code and send it to fullstack@colu.com

# Good luck!
