# LSEG_Chatbot
LSEG Assignment

##Prerequisites
* Node Js (v18.x.x recommended)
* npm
* Git

##Project Structure

1.lseg_chatbot -> React Frontend Application
2.lseg_chatbot_backend -> NdeJs Backend Application

##Setup Instructions

1. Clone the repository
    clone the repository to local system.
   `git clone https://github.com/Madumali/LSEG_Chatbot.git
     cd LSEG_Chatbot `
2. Setup Frontend
   * Navigate to the 'lseg_chatbot' directory.
   `cd lseg_chatbot`

  * Install Dependencies
  Run the following command to install dependencies.
  `npm install`

  ###Start the development server
  Start the rect development server
  `npm run dev`

####The React app will run on http://localhost:5173/.

3. Setup Backend
   * Navigate to the 'lseg_chatbot_backend' directory.
    `cd lseg_chatbot_backend`

  * Install Dependencies
  Run the following command to install dependencies.
  `npm install`

  ###Configure Environment Variables
  Create a '.env' file in the 'lseg_chatbot_backend' directory and add following variables.

  `PROTOCOL=http
   HOST=localhost
   PORT=4001
   API_URL=https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=AIzaSyDv4gtrD6VJ4feZe4r9WUpuwMEKgTSC2lw`

   ###Start the backend server
  Start the Nodejs backend server
  `npm start`

  ####The backend server will run on http://localhost:4001.

  ## Running The Full Stack Application
  1. Open two terminal windows and navigate to 'lseg_chatbot' and 'lseg_chatbot_backend' in each terminal.
  2. Start both frontend and backend servers as instructed above.
  3. The frontend will accessible via 'http://localhost:5173/' and will communicate with the backend at 'http://localhost:4001'.
