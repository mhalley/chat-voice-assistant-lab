# English conversation partner voice assistant

This voice assistant uses Watson Speech libraries and ChatGPT3. I've configured ChatGPT to act as a conversation partner in English to practice scenarios and provide feedback (Honestly, this may not be the best use case for this model as I've discovered Watson speech-to-text doesn't seem to handle certain terms and tone very well. Try ordering a latte and see how it does.) You can edit the prompt to your needs.

In order to run this voice assistant yourself, you'll need to build the application and run it with Docker: 

```
docker build . -t voice-chatapp-powered-by-openai
docker run -p 8000:8000 voice-chatapp-powered-by-openai
```

To access the app, you can visit http://127.0.0.1:8000/ or http://localhost:8000/ in your web browser.
