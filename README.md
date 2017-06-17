Slack bot
=========

Install
-------

Install node from https://nodejs.org/en/download/

Then:
```
npm install             # install deps from package.json
npm install -g nodemon  # optional
```

```
touch config.json
chmod 600 config.json
```

Get token from https://my.slack.com/apps/build/custom-integration and store it in `config.json`:

```
{
    "token": "<token>"
}
```

Run
---

```
node index.js
```

Sources
-------

Paul Asjes: Building Slack Bots
