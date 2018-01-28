## Inspiration

The IBM cloud development platform as well as Watson is full of great features, and we wanted to put them together in a single chatbot, towards a useful translation tool for all ages.

## What it does

Wryss can translate user input into a variety of languages. It can identify objects in images that are sent to it, and provide the translation of the image subject! The entire platform can also be controlled by the user's voice. As an extra feature, Wryss can try to guess how old you are!

## How we built it

The backend was build with Node-Red, which integrates with many IBM services. It is hosted on IBM Bluemix. The speech-to-text IBM service was used to turn voice into text for the chatbot. All messages were processed by IBM Conversation, which then used IBM Translator to translate the them into a selection of languages. Images sent to the bot were classified using IBM's Visual Recognition, and visual face recognition is used to guess the users age.

## Challenges we ran into

It was quite difficult at first to understand the concept behind node-red vs. traditional programming. We found the learning curve to be quite high; it was not the most intuitive tool. We also had a lot of difficulty with debugging certain functionalities. More specifically, certain bugs did not provide very clear or specific error messages, and documentation online about the specific issues that we were facing were almost non-existent. This forced us to abandon the main feature that we intended to implement (integration with Amazon). 

## Accomplishments that we're proud of

Having a finished hack despite the many hours that were wasted on trying to debug.

## What we learned

We learned that node-red is a very powerful tool once you really understand how it works, but that getting there isn't the most pleasant experience.

## What's next for WryssBot
