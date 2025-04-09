@michaeldavis246611119version: '3.8'

services:
  app:
    image: my-node-app
    build:
      context: .
      dockerfile: Dockerfile
    ports:
      - "3000:3000"
    volumes:
      - .:/usr/src/app
    depends_on:
      - db

  db:
    image: mongo
    ports:
      
- "27017:27017"## Hi there 👋

<!--
**michaeldavis246611119/michaeldavis246611119** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on learning how to efficiently use AI
- 🌱 I’m currently learning The laws of the universe 
- 👯 I’m looking to collaborate on game development 
- 🤔 I’m looking for help with establishing basic knowledge of game development 
- 💬 Ask me about how much I'm learning through AI
- 📫 How to reach me: email 
- 😄 Pronouns: Him
- ⚡ Fun fact: I still have a baby tooth

📫