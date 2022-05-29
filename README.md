# Contra-Drag
Against drugs.



This project aims to prevent youth from being involved into drug dealing. 
The neural network detects dangerous content, which is then: a) blocked; b) deleted; c) sent to special services. 
Currently, it is integrated into telegram-bot as mvp. 

The dataset contains random messages from [open-source dataset]() and data exported from telegram chats selling drugs. 
Now prediction is calculated using linear regression. ~~Unfortunately, now it is overtrained~~

It is planned that in the future:
1. The model will detect dangerous content based on its context (NLP)
2. The model will be trained on a larger dataset

Usage:
* Ad-blocking
* Browser history scanning and subsequent reporting to special services

Long-term results:
* Reduction of number of youth involved in drug dealing
* Destruction of the [drug trade network in Central Asia](https://russian.eurasianet.org/node/60796)
