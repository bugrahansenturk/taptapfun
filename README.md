# Taptapfun
Online tapping game developed with flutter and Firebase. Every game has 2 players. Opponents should click faster than other for increasing or decreasing the Box in the middle. The faster player win the game and gain points. The game is still under development so functionalities like Leaderboard etc. is not published in the game right now.

# Why Flutter and Flame?
Flame is a modular Flutter game engine that provides a complete set of out-of-the-way solutions for games. It takes advantage of the powerful infrastructure provided by Flutter but simplifies the code you need to build your projects.

It provides you with a simple yet effective game loop implementation, and the necessary functionalities that you might need in a game. For instance; input, images, sprites, sprite sheets, animations, collision detection and a component system that we call Flame Component System (FCS for short).

In my researches I saw that Flame is highly capable of running games with not need high perfomange. So because of Flutter's cross-platform capabilities and other benefits I wanted to give Flutter Flame a shot.


# Why Firebase?

I used Firebase's FireStore, Realtime Database, Authentication and Cloud Functions systems in TapTapFun. 

-I used Firestore for storing user and past game data. Because of it's highly scalability options i think it will give better performance in the future.
-I used Realtime Database to store realtime games because of it's speed and performance in scale I have choosed it to run games.
-I used Cloud functions for matchmaking and other functionalities.


# You can download TapTapFun from Google Play Store:
https://play.google.com/store/apps/details?id=com.dumbooctopus.taptapfun
