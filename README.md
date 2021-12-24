## ReactJS Stack
Now you can quickly spin up a [ReactJS](https://reactjs.org/docs/getting-started.html) app with support of [TypeScript](https://www.typescriptlang.org/), [React Router](https://reactrouter.com/) and [Redux](https://redux.js.org/) hosted on [Heroku](https://www.heroku.com).

Using this stack as template would create a new repository for codebase and host the ReactJS app on the Heroku URL provided as input by the user.

## Prerequisites
Having a Heroku account (Yes, that's it!! )

## What are the inputs to pass while setting up the stack?
```
- API_KEY (Heroku Secret API Key) 🤫
- APP_NAME (Unique host URL on which the app will be deployed on Heroku) 🖥
- EMAIL (Email id associated with Heroku account) 📧
```

## How to get Heroku API Key? 🔑
```
Login/Signup to Heroku -> Account Settings -> API Key
```
Check [this](https://help.heroku.com/PBGP6IDE/how-should-i-generate-an-api-key-that-allows-me-to-use-the-heroku-platform-api) out for more details on getting Heroku API Key.

## App hosted URL would be:
```
<APP_NAME>.herokuapp.com

Example: APP_NAME input by user is: sample-website
Hosted URL: https://www.sample-website.herokuapp.com
```

## Tech Details:
- NodeJS: 16.13.1
- React Router: 6.2.1
