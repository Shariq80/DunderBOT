# DunderBOT - The Office Chatbot

Welcome to **DunderBOT**, a chatbot project built with Next.js and Google Generative AI. This chatbot allows you to interact with characters from *The Office*, such as Michael Scott, Dwight Schrute, and Jim Halpert, in a fun and engaging way.

## Features

- **Character Emulation:** Interact with a chatbot that responds with the humor and style of *The Office* characters.
- **Personalized Greeting:** Start the conversation by entering your name, and the bot will greet you in character.
- **Responsive Design:** The chatbot is optimized for both mobile and desktop devices.
- **Smooth Interaction:** The chatbox auto-scrolls to the latest message and displays a loading indicator while generating responses.

## Installation

To set up and run DunderBOT locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/dunderbot.git
   cd dunderbot
   ```
2. **Install Dependencies**
    ```bash
    npm install
    ```
3. **Set Up Environment Variables**
    ```bash
    GOOGLE_API_KEY = your_google_api_key
    ```
4. **Run the Development Server**
    ```bash
    npm run dev
    ```
    open `http://localhost:3000` in your browser to interact with DunderBOT.

## Usage
1. Enter Your Name: The chatbot will prompt you to enter your name to personalize the chat.
2. Chat with The Office Characters: After the introduction, type your message and click "Send" to receive responses from the bot.

## Code Overview
 - `/src/app/page.js`: Main entry point of the application where the Chatbot component is included.
 - `/src/app/components/Chatbot.js`: Contains the chatbot logic, including state management and API integration.
 - `/src/app/globals.css`: CSS file for styling the chatbot and ensuring responsiveness.