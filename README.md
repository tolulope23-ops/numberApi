PROJECT DESCRIPTION 
The Number API provides interesting mathematical properties and fun facts about a given number. It supports checking if a number is Armstrong, Even, or Odd, isPrime, isPerfect and isDigitSum, returns data in JSON format, CORS enabled for public access and fetches a fun fact using the Numbers API.

SETUP INSTRUCTIONS
Clone the repository git clone https://github.com/tolulope23-ops/numberApi.git 
Install dependencies: npm install
SetUp environment variables create a .env file and add your environment variables e.g PORT.
Run the Server npm app.js

API DOCUMENTATION 
  Endpoint: get "https://your-deployment-url.com/api/classify-number/"
Response format: {
  "number": 6,
  "isPrime": ,
  "isPerfect": true,
  "properties": ["armstrong", "even"],
  "funFact": "6 is the smallest perfect number."
}


 
