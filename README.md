# Chat Application 
![image](https://github.com/vinodkhichar/chat-app/assets/95199749/f0e12d85-5641-45c8-ac86-3ec7c4d70dcf)
![image](https://github.com/vinodkhichar/chat-app/assets/95199749/c74cd29b-a789-4a49-97e1-8e2145c3123d)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
