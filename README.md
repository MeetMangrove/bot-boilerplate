# Mangrove Bot Boilerplate

A boilerplate for Mangrove Bots in Node.js.

## Usages

### Set environmental variables

Create a .env file with the following variables and their values:
```
SLACK_CLIENT_ID=***************
SLACK_CLIENT_SECRET=***************
AIRTABLE_API_KEY=***************
AIRTABLE_BASE_KEY=***************
AIRTABLE_MEMBERS=***************
NEW_RELIC_LICENSE_KEY=***************
NEW_RELIC_APP_NAME=***************
NEW_RELIC_APDEX=***************
NEW_RELIC_NO_CONFIG_FILE=***************
MONGO_URL=***************
NODE_ENV=DEVELOPMENT
PORT=3000
```

### Run the bot

In local for development:
```bash
$ npm run start
```

Lint code:
```bash
$ npm run lint
```

Fix lint errors:
```bash
$ npm run fix
```

Building:
```bash
$ npm run build
```

Running in production mode after building:
```bash
$ npm run serve
```

Heroku dynos:
```bash
$ npm run web
```
