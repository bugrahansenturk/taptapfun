## Taptapfun

Taptapfun is an online tapping game developed using the Flutter and Firebase technologies. Each game consists of two players, where each opponent has to click faster than the other to increase or decrease the Box in the middle. The player who clicks faster wins the game and gains points. Currently, the game is still under development, and functionalities like Leaderboard are not published in the game.

## Why Flutter and Flame?

Flame is a modular Flutter game engine that offers a complete set of out-of-the-box solutions for games. It takes advantage of the powerful infrastructure provided by Flutter but simplifies the code needed to build your projects.

Flame provides a simple yet effective game loop implementation and the necessary functionalities that you might need in a game. For example, input, images, sprites, sprite sheets, animations, collision detection, and a component system that we call Flame Component System (FCS for short).

In my research, I found that Flame is highly capable of running games that do not require high performance. Due to Flutter's cross-platform capabilities and other benefits, I wanted to give Flutter Flame a shot.

## Why Firebase?

I used Firebase's Firestore, Realtime Database, Authentication, and Cloud Functions systems in TapTapFun. 

*I used Firestore for storing user and past game data because of its highly scalable options, which I think will give better performance in the future.
*I used Realtime Database to store real-time games because of its speed and performance in scale. I chose it to run games.
*I used Cloud Functions for matchmaking and other functionalities.

## Download

You can download TapTapFun from the Google Play Store:
https://play.google.com/store/apps/details?id=com.dumbooctopus.taptapfun
