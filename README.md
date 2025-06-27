# AI Wrapper Chatbot

This web application demonstrates a simple chat box that translates any text you send. Authentication and backend communication are handled by [Skapi](https://www.skapi.com).

## Running

Open `index.html` in your browser. All pages initialize the `skapi-js` library and handle login state. Use the sign up form to create an account, then log in to access the chat page.

Select a target language from the drop-down menu above the input box, type your text, and the app will display the translation. Messages are forwarded to OpenAI's API using Skapi's `clientSecretRequest` with the client secret name `gpt`.
