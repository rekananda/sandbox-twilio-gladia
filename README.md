# Getting Started

Store your Twilio credentials in the .env file:
1. In your Twilio console click on 'Settings' and take note of your Account SID.
2. Navigate to Settings/API Keys to generate a new Key SID and Secret

```.env
TWILIO_ACCOUNT_SID=ACxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_API_KEY_SID=SKxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_API_KEY_SECRET=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

optional if need to use conversation service
TWILIO_CONVERSATIONS_SERVICE_SID=IS00000000000000000000000000000000
```

## Available Scripts

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.\
Service BE will run in [http://localhost:8081](http://localhost:8081) to view it in the browser.

### `npm run dev`

Runs the app in the development mode without the service, you must have running service clone from [twilio-interaksi-service](https://github.com/talentlytica/twilio-interaksi-service.git).\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.\
you must config/edit the `package.json` file 'http://localhost:8081' to your url service
