# devops-bot
## Commands for getting started 
First build the image from the Dockerfile
`docker build -t merlin-bot .`
Then start the container with
`docker run -p 8501:8501 merlin-bot:latest`

You should now find the app running on http://
localhost:8501/

## Note about api key
For the bot to work, create .env file in the project root with an OpenAI key in it. Example .env file:
```
OPENAI_API_KEY_CHAT=<"sk-thishereismyopenaikey">
```
