# Gesture-Based-Assignment

## Table of Contents

+ [Requirements](#requirements)
+ [Planning](#planning)
+ [References](#references)

## Requirements

+ An application with a Natural User Interface is required, i.e. controlled by natural means - body movements, vocal commands, etc.
+ The minimum expectations for this NUI app would be a locally run implementation.
+ Any programming language can be used.
+ Each project should be developed by teams of two.

## Planning

Upon hearing the specifications of the project, we quickly formulated an idea to build a buzz wire game. This childhood game, very familiar to most, seemed like a ideal application to be controlled by gestures, as opposed to a feigned, impractical buzz wire game controlled by keyboard or mouse controls.

Now we had settled the orientation of our app, we needed to brainstorm and figure out how to implement the application. After considering using [Myo](https://www.myo.com) armbands(supplied by the college) and camera motion tracking(with coloured finger tips), we decided to take advantage of the Myo armbands. The Myo armbands come equipped with both an accelerometer and a gyroscope. They also have prebuilt gestures which could come in handy if adding any additional features. 

Myo armbands are compatible with mulitiple languages including C# and JavaScript, which were particularly interested in.

+ **C#** - Using Unity with C# would be a suitable choice in making a game. [Unity](https://unity3d.com) is a efficient, crossplatform game engine that supports 2D and 3D graphics. The unity app could then be exported and uploaded to the [Myo Market](https://market.myo.com/).
+ **JavaScript** - JavaScript would not be as optimal for game making. However, a powerful game engine may not needed for such a simplitic game. A HTML5 canvas would probably surfice. If needed a JavaScript game framework could be applied in makeing the game, e.g. [Phaser JS](https://phaser.io/). Most notably, the application would be easily accessible - more than that of a Myo Market application. Instead of downloading and installing software, a simple HTTP request in a favoured browser would bring a user to the game. 

After considering the options, we agreed JavaScript would be ideal considering that it meets our requirements and has the optimal deployment. We will attempt to use solely HTML5 canvas - if this proves to be insufficient, we will look into the many JavaScript game frameworks. As for the actual deployment, we plan to host a simple Python server with Docker and Heroku.

## References

-----

__*Rebecca Kane - G00xxxxx@gmit.ie*__ | __*Tara O'Kelly - G00322214@gmit.ie*__
