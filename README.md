# esthers-senior-buddy
Elders Companion for my Grandaunt Esther

## What my Grandaunt Esther needs 
Esther is 96yo. Our family is big. Nobody lives far away, but nobody "has got time" to visit her frequently. 

Fortunately her grandnephews Alberto and Luís Alberto (me) are going to put some ideas to use. We think she should be able to see what's going on in the day-by-day of her family. She doesn't want to use a phone, as it's screen is too small, or a tablet, as she doesn't want to carry anything around. Other options have so many functions that overwhelms her patience. We'll make it be simple. 

## Project description
A "real time" chat / album application

## The Software
The Software is supposed to be written mostly in PY, JS(node) & JS(Front-end) using Socket.io. There is going to be the Family Member's (FMP) page and Esther's page (EP). For the first version, in FMP family members are going to upload pictures with descriptions to a remote server. In EP, she will receive the messages/pictures/videos and be able to go backwards or forwards, looking at all the content. 

### Family Member's Page (FMP)
The first version is going to allow family members to push messages/photos/videos with description to a cloud server via an API. The page is going to be mobile-ready (responsive) and members will mostly use their phones to do so. They will be able to see what they had previously uploaded, but not be able to edit. They will only be able to delete what has not been seen yet by Esther.

### Esther's Page (EP)
Esther will have a TV mounted in her living room, "always on", with a 3D printed controller (large colored push buttons), where she will be able to see the current message/image/video or push the buttons to go to the previus or to the next. 

We will think about her usability a lot (even though she is super smart and active, it's got to be easy and intuitive for her to use), and we're going to monitor how she uses it, metrics we have thought about are: how many times per day she uses it, how long does she look at each message, how many messages she sees at each time..

We are also thinking of a simple way she could interact back. For example record audio/video to reply a message if she wants. 


## B.O.M.
One TV 
Tv Mount
One Raspberry Pi 3B+/4
3D Printed case for the RasPi
One Camera (usb webcam or picam)
Push Buttons for user interaction
3D Printed controller (for the buttons)
The Software
