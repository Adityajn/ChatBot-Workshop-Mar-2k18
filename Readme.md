# ChatBot Workshop 2k18 at MIT-Pune by Exatt Systems

ChatBot is a computer program that simulate human conversation, through artificial intelligence.

Some Famous Chatbots
a. 1966 ELIZA
b. 2015 ALEXA
c. 2016 TAY

Why?
1. More Secure for privacy
2. Less Latency for requests
3. Faster than Human Resposne
4. Flexibilty
5. Personalized Experience
6. Easy Customer Suport and Service

Archirecture-

```
| Sensory Layer | <--> | ChatBotPlatforms | <--> | API Brokerage Layer |
                                |
                                |
                       (NLP and ML modules)
```

### Sensory Layer (utterances) - voice based, text based
### ChatBotPLatforms -  Dialog FLow, AWS lex

## Intents
1. Each chatbots has a set of intent which shows intentions of user.
2. Suppose a pizza delivery chatbot has 2 intent i.e. order and cancel
3. Suppose a banking chatbot has following intents i.e. check balance, change pin, transfer money
4. Based on input chatbot select a particular intent

## Slots
1. Additional information user has to provide. Can be called as constraints.
2. Suppose order a pizza has 2 slots i.e. what kind of pizza and size of pizza
3. Change my pin requires current pin.

## Context
1. Makes Chatbots intelligent,
2. identify context of chat.
3. Like in change pin after entering current pin it should change pin. 

## Fulfillment
1. Actual work we want chatbot to do.
2. In case of pizza delivery, request must be sent to restaurant by chatbot.
3. request is sent to API brokerage layer.


# This Project uses following technologies
1. AWS Lex as a Chatbot platform
2. AWS Lambda as a compute service.
3. AWS DynamoDB as a NoSQL database.

```
https://exadatum-mit.signin.aws.amazon.com/console
Username :- registered email
Password :- exadatum-mit
```