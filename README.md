# Project Title
Chatbot

## Overview

An advanced AI-powered application with AI chat, PDF processing and AI image generation. This app will provide a convenient way to interact with OpenAI's powerful language models, such as GPT-3.

I frequently use the free tier of ChatGPT in my day-to-day tasks, but I wanted to do more. To unlock additional features, I would need to subscribe to ChatGPT Plus, which costs $20 per month. However, by using this app to interact with ChatGPT through the OpenAI APIs, I can explore and use it as much as I want while only being charged for the requests I make. This approach can save me over $2,000 annually compared to subscribing to ChatGPT Plus.

While still having access to ChatGPT for everyday use, I can use this app for specific requests. Here are some of the key benefits this app offers me:

- **Unlimited document/image uploads**: Unlike ChatGPT, which has daily limits for image and PDF uploads, this app removes those restrictions.
- **Access to any GPT model**: I can freely choose the model I want, including more advanced, accurate, and capable ones.
- **Greater flexibility in requests**: The app allows me to make requests that ChatGPT doesn't support, such as summarizing YouTube videos, among other advanced functionalities.


### Features

- As a user, I want to be able to chat with an AI.
- As a user, I want to be able to upload a PDF and ask an AI questions about the PDF document.
- As a user, I want to be able to generate random AI images.

## Implementation

### Tech Stack

- Frontend:
    - React

- Backend:
    - Node
    - Express
    - Axios


### APIs

- OpenAI APIs

### Sitemap

- Login page
- Chat page (Landing page)
- PDF Manager page
- Image generation page

### Auth

- Implement a basic access code auth, users will need to provide access code to log in
- Create random access codes (not to be pushed to the server) - and disable after use

### Mockups

#### Login and Chat Page
![](login-and-chat-page.jpeg)

#### PDF Manager and Image Generations Page
![](pdf-and-image-page.jpeg)


## Roadmap

### Frontend

- UI:
    - Create a mockup for the four pages
    - Create pages with basic styling and complete app functionalities
    - Create re-usable components
    - Finish up styling

### Backend

- Chat:
    - Update Chat system from terminal to user input
    - Add response streaming feature
    - Implement webscoket for real time communication
    - Add other GPT pro features

- Auth:
    - Implement a basic access code auth, users will need to provide access code to log in
    - Create random access codes (not to be pushed to the server) - and disable after first time use
    - Track token limit for each access code and log users out after reaching limit

- File upload:
    - Allow users to upload PDF, set a PDF size limit.
    - Allow users to image upload.
    - Allow users paste image into the chat
    - Allow users drag/drop PDFs and images

- Image Generator:
    - Handle image export/download
    - Implement a different image upload feature (Like Fooocus/Claude - but still OpenAI)
