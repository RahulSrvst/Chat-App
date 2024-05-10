Chat-App 
The Chat Application Project (Snappy) is made up of ReactJS to create a dynamic and responsive platform for real-time communication. Users can engage in text-based conversations, share media, and create groups. With features like message encryption, notifications, and user authentication, it ensures both security and usability. Its sleek interface and scalability make it ideal for personal and professional communication needs, fostering seamless and engaging interactions in the digital realm.


![login page](./images/snappy_login.png)

![home page](./images/snappy.png)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/RahulSrvst/Chat-App
cd chat-app-react-nodejs
```
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

                                                      # THANK YOU
                                              # Created by- Rahul Srivastava
