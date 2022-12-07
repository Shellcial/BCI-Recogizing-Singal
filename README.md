# BCI-Recogizing-Singal

## Summary

This is a game specific project, using affordable devices to receive brain's electrical activity during human performing specific events in mind, then use unsupervised learning to classify the signal in order to figure out signal pattern occuring when performing specific events, then we can detect the pattern to indicate what the person want to do, so he just needs to "think" and the computer can read his mind and perform relative tasks in game.

## Background

* Perform motion and object detection on device that receives physical input is becoming common 
In recent years, tracking and identifying objects have been more common and friendly for public to use. There are many libraries that can detect human body and hands in real time such as mediapipe in Python. Custom Labelling and training and then detecting objects can be done in a rather easy approach via yolov7. There are more tutorials are shoot on youtube, people can try roboflow online to perform object training and detection at once. VR-chat, vtuber, VR and AR games, the type of using sensor to detect environment has become more common in these 10 years. However, these sensors all requires and receives physical input, it requires user to give physical movement and changes for the device to notice what you want to do.

Instead, Perform BCI have the advantage below:
* As vr and ar technique become less and less eye-catching as these things become common, developing a game via BCI can bring users to another entertainment level
* as the AI trained model identify the user brain signal and guessing what user wants to do, as long as the computation of the algorithm is finished quickly, it can be performed in real time and the response time will be faster than human doing physical movement, which means user can really see their decision outcome reflected in game even faster than using a mouse, keyboard or input console control. Thus, the user will have a more synchronized and immersive game experience.
* gamers don't need to perform any physical movement, so people with disability is also welcome to play.

## How is it used?

In recent year, individual BCI device is starting to be mature, for both the user or developer, they need to buy a biosensing gadget like the upcoming [Galea](https://openbci.com/), so that their brain singal can be detected. Then, an AI model should be built and the recongizing solution will be performed and print out the user intended events, these event command will be sent to the game. For starter, buying a [start kit from OpeneBCI](https://shop.openbci.com/products/bundle2) can start to receive data and develop the AI model too. Here is a demonstration using the device (https://www.youtube.com/watch?v=Dgo7F-lpyYE&t=397s)

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

## Data sources and AI methods
The data comes from users/participants connecting BCI device and performing game activity with four cases, with camera capturing player physical behavior to help later procedure such as triming out specific data of player doing specific action so that the data can be 
1. Using physical devices to play a game
2. Thinking you are going to use physical device to play the game, while you don't perform any physical movement
3. Thinking you are playing the game, conceptually thinking doing certain actions without considering the physical device input.
4. After players are familar with the game, they need to see other players playing the game, it leads the participants to think what events they will perform at the moment when they are seeing the players playing.

These experiments aim to capture two different data individually. Since when player is playing, they will conceptually want the game character to move and they  perform phyiscal movement on keyboard and mouse. These behaviors may behave differently on brain signal so different experiments which separate and combining them is also needed.

## Challenges
* brain is super complicated and there are many details we don't know even in biological field
* noise is still significantly large and the signal between performing differnt actions may not be distinguish
* it is difficult to have a standard classification of one brain signal to one action since different people mind may perform differently

## What next?
* include different game and different ranges of people to perform same experiments
* using different algorithm and AI model to see any improvement of classifying features

## Acknowledgments
* sources of inspiration
* [OpenBCI](https://www.youtube.com/@OpenBCI-official/featured), demonstrating the usage and potential of BCI device
