### Backend Setup

**Clone the Backend Repository:**
   git clone https://github.com/devu11/CALENDAR_APP_BACKEND.git backend

Navigate to the Backend Directory:
cd backend



Install Backend Dependencies:
npm install cookie-parser cors dotenv express express-async-handler express-session googleapis mongoose nodemon



Create a .env File in the Backend Directory:
.env


Add the Following Environment Variables to the .env File:
PORT=your_port
GoogleClientId=your_google_client_id
GoogleClientSecret=your_google_client_secret
RedirectURL=your_redirect_url
GoogleAPIKey=your_google_api_key
MONGO_URI=your_mongo_uri

Start the Backend Server:
npm start
