## Chat App With Sentiment Analysis Using Next.js

Realtime applications have been around for quite a long time as we can see in contexts such as multi-player games, realtime collaboration services, instant messaging services, realtime data analytics tools, to mention a few. As a result, several technologies have been developed over the years to tackle and simplify some of the most challenging aspects of building apps that are sensitive to changes in realtime.

## Prerequisites
Before you begin, ensure that you have Node and npm or Yarn installed on your machine. Here is a run-down of the core technologies we will be using.

- Next.js (https://learnnextjs.com/)— A framework for building server-side rendered(SSR) React applications with ease. It handles most of the challenges that come with building SSR React apps.
- Pusher (http://bit.ly/pusher-tutorial)— Pusher is a technology for building apps with varying realtime needs like push notifications and pub/sub messaging. It is the engine behind the realtime ability of our comments widget.
- Sentiment (https://github.com/thisandagain/sentiment)— Sentiment is a module that uses the AFINN-165(http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010) wordlist and Emoji Sentiment Ranking(http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0144296) to perform sentiment analysis(http://en.wikipedia.org/wiki/Sentiment_analysis) on arbitrary blocks of input text.
- React (https://reactjs.org/) — A very popular JavaScript DOM rendering framework for building scalable web applications using a component-based architecture.
- A few other libraries will be used as we will see in a moment. Also ensure that you have Node installed on your machine.

Installing dependencies
Create a new directory for the application and run the following command to install the required dependencies for the app.

# Create a new directory
    mkdir realtime-chat-app
    
    # cd into the new directory
    cd realtime-chat-app
    
    # Initiate a new package and install app dependencies
    npm init -y
    
    npm install react react-dom next pusher pusher-js sentiment
    npm install express body-parser cors dotenv axios
