# International telephone input validation

This project will show you one way to validate phone number inputs with the [`intl-tel-input`](https://github.com/jackocnr/intl-tel-input) library and Twilio's [Lookup API](https://www.twilio.com/docs/lookup/api). For a production use case we recommend adding [phone verification](https://github.com/twilio-labs/function-templates/tree/main/verify), which is a best practice for collecting phone numbers from your users in order to make sure they have control of the number.

## Installing

Create a .env file and add your environment variables found in the [Twilio console](https://twilio.com/console)
```
cp .env.example .ev
```

Then install the dependencies and run with npm:

```
npm install
npm start
```

Navigate to http://localhost:3000/index.html