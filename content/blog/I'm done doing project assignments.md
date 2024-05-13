+++
title = "I'm done doing project assignments"
date = "2024-05-13"
tags = [
    "thoughts",
    "tech",
    "hiring"
]
categories = ["Thoughts"]
featured = true
+++

I used to prefer doing project assignments for job applications over coding tests but after doing a bunch of these projects I'm done with doing them. It's not that there is anything particularly wrong with these kinds of assignments but there have been so many things wrong with how they are done and how they don't respect your time at all.

Most of these would range from 3 to 5 days which would be more than enough time to finish it, but it should really be doable in one day or less. As an active job seeker having to spend almost a week on one job application while still actively applying and interviewing is such a dread that I can't even imagine what searching for a job while working full time right now is.

Another major point on these assignments not respecting people's time is how for almost half of these projects that I've worked on, there was no feedback given and I'm pretty sure some are not even run locally. I understand that there is a surge of job applicants right now and that might not be even possible for engineers to be able to spend time on all of the applications, but this is further proof that companies shouldn't be pushing this type of assessment at all.

I understand the need of assessing people's ability to be able to start and finish projects because maybe there's a lot of applicants who doesn't have working code in their portfolio, but there should really be an exception to people who've had experience and even put code in their portfolio, it should be enough to review on and talked about in the interview. 

This might sound a bit rant-ish and entitled but I honestly appreciate some of the project assignments that I've worked on, so I'm putting all of the projects that I've worked on here with the explanation of the task and the reasoning behind my design/decisions here. I have also removed any mention of the company the test belongs to.

## 1. Knowledge Graph Chat
Stack: SvelteKit, Neo4j, SQLite, ChatGPT\
Task Description: Create a chat interface that can be generated into a knowledge graph\
Repo: https://github.com/favian-cyril/knowledge-graph-chat

This might be my most hours put into a project assignment because of the sheer amount of things that I need to learn for it. This one I couldn't host because the API key might be too expensive but the project is using docker and docker-compose so it should be easy to setup.

## 2. Chat room
Stack: React + vite, Node.js & socket.io, MongoDB\
Task Description: Create a chat room, user is able to join by entering name and room code\
Url: https://chat-room-fe-production.up.railway.app \
Repo: [chat-room](https://github.com/favian-cyril/chat-room)

This has actually been a fun little project and I got to use websockets which I haven't used in a long time, however it lacks some features to be a full fledged chatroom as you can't see all the available rooms currently available.

## 3. Url Minifier
Stack: SvelteKit, Redis\
Task Description: Create a url minifier\
Url: [url-shortener-web-seven.vercel.app](https://url-shortener-web-seven.vercel.app/)\
Repo: [mini-url-web](https://github.com/favian-cyril/mini-url-web) [mini-url-backend](https://github.com/favian-cyril/mini-url-backend)

This is a fun little project that turns out to be not take much time than I thought. Links created will be stored locally and on redis but you cannot see other people's links.

## 4. Bid system
Stack: Next.js, SQLite\
Task Description: Create a bidding system, pre-populated with content\
Repo: [bidding-system](https://github.com/favian-cyril/bidding-system)

The project description for this is quite open ended and with a lot of features, so it took more time than expected. It was my first time working with next and server components so there were some issues building the project because I used both server components and api routes.

## 5. Birthday Reminder
Stack: Nest.js, Redis, SQLite\
Task Description: Create a backend API to automatically call a webhook on the user's birthday\
Repo: [birthday-reminder-nestjs](https://github.com/favian-cyril/birthday-reminder-nestjs)

I would say this is one of the more interesting ones because it is so different from the others, it was only a backend service but it is quite technical. I had to create a scheduler that can be restarted but also the webhook has a chance to fail so I also created a queue with retry functionality.

## 6. NYT News Reader
Stack: React + vite\
Task Description: Create a simple reader fetching news from NYT\
Url: https://nyt-news-web.vercel.app/ \
Repo: [nyt-news-web](https://github.com/favian-cyril/nyt-news-web)

A simple web reader to fetch data from NYT with search functionality, nothing too complex but I also added a debounce function to prevent over calling.

## 7. E-commerce App
Stack: React Native\
Task Description: Create a react native app and web to show products from a mock api\
Repo: [e-commerce-react-native](https://github.com/favian-cyril/e-commerce-react-native)

This one kind of infuriates me with how there is so much missing in the project description and also the kind of output it wants (both a react native app and a separate web). Because I felt the app and web have the same features I decided to use the same repo to generate a react native web export instead.

## 8. Simple Users List
Stack: Angular\
Task Description: Create a simple users list and description page\
Repo: [users-angular](https://github.com/favian-cyril/users-angular)

This is also a simple task but I had to re-learn to angular since I haven't used it in a while.