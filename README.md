# AI Wrapper Chatbot

This web application demonstrates a simple chat box where you can chat with a mental wellness therapist AI. Authentication and backend communication are handled by [Skapi](https://www.skapi.com).

## Running

Open `index.html` in your browser. All pages initialize the `skapi-js` library and handle login state. Use the sign up form to create an account, then log in to access the chat page.

Messages sent in the chat are forwarded to OpenAI's API using Skapi's `clientSecretRequest` with the client secret name `gpt`.
