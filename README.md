# Survey Maker

Large feedback-collection app. It is a full stack application. This app includes the full gamut of features, including everything from authentication to email handling. App that can be used to send mass emails to a big list of users for the purpose of collecting feedback.

## Stack of technologies

- Frontend created using [Create-React-App](https://reactjs.org/docs/create-a-new-react-app.html)
- On the backend [NodeJS](https://nodejs.org/en/) and [Express](https://expressjs.com/)
- [Mongo](https://www.mongodb.com/cloud) database
- Routing on the frontend using React Router and on the backend using Express
- Google OAuth authentication with [PassportJS](https://www.passportjs.org/)
- Credit cards and payments are handled by [Stripe](https://stripe.com/en-gb-nl)
- Email provider - [SendGrid](https://sendgrid.com/)
- App deployed to [Heroku](heroku.com)

## Running the app

You can run the app in the development mode with `npm run dev` command from the `servey-maker` directory. Script starts both front-end on [http://localhost:3000](http://localhost:3000) and the backend on the [http://localhost:5000](http://localhost:5000).
For Webhooks in development mode can be used [Ngrok](https://ngrok.com/).

Production version of the app can be found [https://survey-maker-taraniev.herokuapp.com/](https://survey-maker-taraniev.herokuapp.com/).
