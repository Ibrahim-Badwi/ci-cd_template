# CI/CD system

simple ci/cd pipeline, that lint, test, build and deploy software to heroku and send success or failure messages to slack.

add these variables to actions secrets in your repository settings:
- secrets.HEROKU_API_KEY
- secrets.HEROKU_APP_NAME
- secrets.HEROKU_EMAIL
- secrets.SLACK_WEBHOOK_URL

## Commands

Start by running `npm install` inside the project folder

`npm start` to run dev server

`npm run lint` to run eslint

`npm test` to run tests

`npm run build` to make a production build

`npm run start-prod` to run your production build
