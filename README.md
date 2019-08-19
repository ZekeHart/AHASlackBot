# slackbot-initial

## Instructions:
Registration website is available at http://ahabot-registration.herokuapp.com

You can register your Home Assistant info there and then add our bot to your slack workspace. After that you can issue it commands by simply including @Aha_bot in a message. It will try to understand you if you use natural language but there is a list of explicit commands availabale at http://ahabot-registration.herokuapp.com/help.


## Bot Info:

We built this bot in Node.js, connected it to Slack using their Node SDK, and used Natural.js for NLP help. The primary NLP methods we used were Logistic Regression Classification to try and get user intents, and Levenshtein Distance to make inputs more tolerant of spelling mistakes.
