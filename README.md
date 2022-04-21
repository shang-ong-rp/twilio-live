# Build Live Streaming with Twilio Live

[Master](https://github.com/shang-ong-rp/twilio-live) repo with a good [tutorial](https://www.twilio.com/blog/build-livestreaming-application-twilio-live-express)

1. Next, set up a new Node.js project with a default package.json file by running the following command: `npm init -y`

2. You're ready to install the needed dependencies:

> Express, a Node.js framework
> Twilio Node Helper Library, to use the Twilio APIs
> dotenv, to load the environment variables from a .env file into your application
> nodemon, to automatically reload the server when you make code changes
> @twilio/live-player-sdk, the Twilio Live Player SDK for JavaScript

3. Run the following command in your terminal to install the packages listed above:

```
npm install express twilio dotenv nodemon @twilio/live-player-sdk
```

4. Save your Twilio credentials safely as environment variables

Create a new file named .env at the root of your project and open it in your code editor. The .env file is where you will keep your Twilio account credentials. Add the following variables to your new file:

```
TWILIO_ACCOUNT_SID=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
TWILIO_API_KEY_SID=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
TWILIO_API_KEY_SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

5. To run the start script, return to your terminal window and run the following command: `npm start`

Once you have done this, you should see the following log statement in your terminal window, letting you know that the Express server is running:

```
Express server running on port 5000
```

You can leave this server running while you work through the tutorial. Nodemon will watch for changes in the server.js file and reload the server to keep it up to date with your latest additions.
