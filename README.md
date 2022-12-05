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

To play VR game at home, this sounds incredible exciting 10 years before, but it just requires 400 USD to buy a Oculus Quest 2. Same for BCI, this may sound insane for the past few years, but as the AI solution of physical detection enhances, BCI development is also developing although less people pay attention on this.

for the user, they need to buy a biosensing like the upcoming [Galea](https://openbci.com/), so that their brain singal can be detected. Then, the recongizing solution will be performed and print out the user intended events, these event command will be sent to the game to perform.

https://galea.co/
For starter, buying a start kit from OpeneBCI

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
The data comes from users/participants connecting BCI device and performing game activity with four cases.
1. Using physical devices to play a game
2. Thinking you are going to use physical device to play the game, while you don't perform any physical movement
3. Thinking you are playing the game, doing which action and which action.
4. After players are familar with the game, they need to see other players playing the game, in a kind of bad or not perfect mannar, it leads the participants to think what events they will perform at the moment when they are seeing the players playing.

Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
