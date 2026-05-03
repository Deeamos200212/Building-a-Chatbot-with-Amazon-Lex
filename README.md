# Building-a-Chatbot-with-Amazon-Lex
Build a chatbot using Amazon Lex and the AWS Console

Amazon Lex Chatbot — Banking Bot

https://img.shields.io/badge/AWS-Lex-orange?logo=amazonaws

https://img.shields.io/badge/Status-Completed-brightgreen  

https://img.shields.io/badge/Category-AI%2FChatbot-blue

https://img.shields.io/badge/Time%20Spent-A%20few%20hours-lightgrey

Table of Contents
Project Overview

What is Amazon Lex?

Key Concepts Learned

Setting Up the Chatbot

Creating the Bot

IAM Role Configuration

Intent Classification Threshold

Intent Design & Testing

Handling Unrecognized Inputs

Customizing the FallbackIntent

Response Variations

Initial Responses

Testing the Chatbot

Personal Reflections

Future Improvements

Project Overview
In this project, I built a chatbot using Amazon Lex and the AWS Console, following the full workflow from design to deployment. I modeled intents, defined utterances, configured dialog flows, and integrated fallback logic to create a natural conversational experience.

“The goal is to strengthen my practical understanding of applied AI within AWS.”

What is Amazon Lex?
Amazon Lex is an AWS service for building conversational chatbots using natural language understanding (NLU) and speech recognition.

“Amazon Lex is an AWS service for quickly building conversational chatbots using built‑in NLU and speech recognition.”

Key Concepts Learned
Intents

Utterances

Slots

FallbackIntent

Response variations

Confidence thresholds

IAM roles for Lex permissions

“I learned how to use Amazon Lex to build a chatbot using intents, utterances, slots, and the FallbackIntent…”

Setting Up the Chatbot
Creating the Bot
I created the chatbot from scratch using the Lex Console. The initial setup took only a few minutes.

“The initial setup took only seven minutes.”

IAM Role Configuration
I created an IAM role with basic permissions so Lex could interact with AWS services such as Lambda.

“Amazon Lex requires authorization to interact with other AWS services such as Lambda.”

Intent Classification Threshold
I kept the default confidence threshold of 0.40, meaning Lex must be at least 40% confident before selecting an intent.

Intent Design & Testing
I created a WelcomeIntent to greet users. Testing showed that Lex correctly recognized greetings like “Hiya” and “Hello.”

“The model successfully mapped user utterances such as ‘Hiya’ and ‘Hello’ to the WelcomeIntent.”

Handling Unrecognized Inputs
When the bot could not classify an input with enough confidence, it triggered the built‑in FallbackIntent.

“Since no intent met the minimum confidence threshold, Lex routed the request to the built‑in FallbackIntent.”

Customizing the FallbackIntent
Response Variations
I added multiple fallback responses to make the bot sound more natural and less repetitive.

“End users receive slightly different friendly messages instead of the same repeated response.”

Initial Responses
I added initial reactions like:

“Hmmm, this is interesting …”

“One moment …”

These give the bot a more human‑like conversational flow.

“This gives end users a smoother experience by making the system feel less rigid.”

Testing the Chatbot
I tested the bot with various inputs:

Recognized greetings → WelcomeIntent

Unrecognized phrases → FallbackIntent

Multiple fallback variations triggered correctly

“It was most rewarding to see the chatbot respond naturally after customizing the FallbackIntent…”

Personal Reflections
The most challenging part was understanding how Lex handles intent recognition and fallback behavior. The most rewarding part was seeing the chatbot respond naturally after customizing the fallback logic.
