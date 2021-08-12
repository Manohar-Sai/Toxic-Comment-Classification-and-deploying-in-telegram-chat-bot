# Toxic-Comment-Classification-and-deploying-in-telegram-chat-bot

The Internet feels to be a safe place as there is no true identity that needs to be
provided and no face to face confrontation. This is misused by many people
throughout the world which makes them enjoy bullying others. Toxic comments
sure have reached peaks in recent years due to advancement in social media
(apps). This may be an enjoyment for some but also is leading to a threat of life
for some. 

This is the main motivation for coming up with the idea of this project.

### Problem Definition
Given a group of sentences used as a part of commenting in online platforms,
classify it as toxic or not. Toxicity of a comment can be presented in several
categories - toxic, severe-toxic, obscene, threat, insult or identity-hate. Problem
statement needs to classify it as either toxic or not and then classify the
comment to which category(ies) it belongs to.

### Modelling and Evaluation
- Multinomial Naive Bayes
- Logistic Regression
- Linear SVC
- LSTM

### Architecture of LSTM
<img src="/Images/Architecture.jpeg" alt="Architecture of LSTM model" width="200"/>

### Results and Performance
<img src="/Images/loss.png" alt="Architecture of LSTM model" width="500"/>
<img src="/Images/accuracy.png" alt="Architecture of LSTM model" width="500"/>

### Deployment - Chat Bot:
We have deployed the current model in a chat bot in Telegram. It is called I’m
Seeing you bot (can be found [here](https://t.me/seeing_you_bot)). It finds the toxicity in chats and reports
them if there is any toxicity in the message. It can be added to the groups in
Telegram, where you need the feel of safety from abuse of others. Further it
masks the message, i.e the toxic words.
Some of the works of the bot are shown:

<p float="left">
  <img src="/Images/pic1_pixel_quite_black_portrait.png" width="500" />
  <img src="/Images/pic1_pixel_quite_black_portrait.png" width="500" /> 
</p>

Dataset link here
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
