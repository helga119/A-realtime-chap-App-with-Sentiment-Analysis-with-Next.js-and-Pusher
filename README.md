# A-realtime-chap-App-with-Sentiment-Analysis-with-Next.js-and-Pusher

This repository contains the source code for a simple chat application that operates in real-time and includes sentiment analysis. By utilizing sentiment analysis, we can determine the mood of users based on the language they use in their chat messages.

Getting Started
Follow these instructions to set up and run the project on your local machine for development and testing purposes.

Prerequisites
Make sure Node and npm or yarn are installed on your machine. You can download Node and npm from the Node download page. If you prefer using Yarn as your package manager, you can obtain it from their website.

Create a Pusher application by registering on the Pusher Dashboard. This will provide you with the necessary app credentials.

Setup Instructions
Clone the repository into a new directory on your machine.

From the new directory, install the project dependencies by executing the following command:

npm install
or using yarn:

yarn add
Create a .env file in the root directory of the project and include the following content:

Pusher App Credentials
PUSHER_APP_ID=YOUR_APP_ID
PUSHER_APP_KEY=YOUR_APP_KEY
PUSHER_APP_SECRET=YOUR_APP_SECRET
PUSHER_APP_CLUSTER=YOUR_APP_CLUSTER
Start the application by running the following command. The app will run on port 3000, unless that port is already in use.

npm run dev
For production:

npm start
Built With
The project utilizes the following key technologies:

Next.js - A framework that simplifies the development of server-side rendered (SSR) React applications. It handles many challenges associated with building SSR React apps.

Pusher - A technology that enables the creation of apps with real-time features such as push notifications and pub/sub messaging. It powers the real-time functionality of our data visualization application.

Sentiment - A module that employs the AFINN-165 wordlist and Emoji Sentiment Ranking to conduct sentiment analysis on text input.

React - A highly popular JavaScript framework for rendering the DOM, widely used for building scalable web applications based on a component-based architecture.
