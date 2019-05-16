# Unity's Tanks

<p align="center">
  <img src="https://user-images.githubusercontent.com/33335169/57844679-66c43080-7785-11e9-9806-1d28ee0a95c0.png"/>
</p>

This game was created with [Unity's Tanks tutorial](https://unity3d.com/learn/tutorials/s/tanks-tutorial). It was the second video game tutorial I completed, continuing my plan to learn game development: completing as many tutorials as possible. This strategy has served me quite well as a beginner to coding, allowing me to familiarize myself to the development environment and the game engine. 

![TanksRound1](https://user-images.githubusercontent.com/33335169/57844714-793e6a00-7785-11e9-9067-44036ca1d0bf.png)

Click [here](https://youtu.be/TSbotf9V-gs) for a video demo of the game. 

## What Went Well
Months ago, I attempted to create a tower defense game but gave up when I couldn’t get my enemy spawner to work correctly. After creating the spawner in the tower defense game, my whole game didn’t work.I couldn’t figure out how to return to an earlier version of my project since I didn’t use version control through GitHub like I do now (as you can see :eyes:)

This Tanks game also uses a spawner in the game manager to spawn the tanks every round. It was great getting the spawner and game manager to work this time around and makes me want to return to the previous tutorial now that I have more knowledge. When I was originally working on the tower defense tutorial, it was just after I had completed the first tutorial for Cube Run, so I was still completely new to making games with Unity.

## What Went Wrong
When testing the game halfway through the tutorial, the tank was getting instantly demolished when I dropped a projectile on it. The game works that if you shoot the projectile from further away, it deals less damage. No matter the distance, the whole tank would just explode and disappear. I figured it was likely a problem with the tank health, tank shooting, or shell explosion script. Eventually, I found that it was the shell explosion script.

## What I Learned
As my second successful game tutorial, I got to use assets from the asset store from the first time - provided by Unity. In my last project, [Cube Run](https://github.com/xixi743/Cube-Run), I created my own assets by adding 3D shapes in the IDE. 

Audio mixing was entirely new to me so that was exciting to learn. The few tutorials/games that I worked on before didn’t involve any kind of sound. It was nice to hear the sound effects come through clearly by making the background music duck.

It was also cool to learn to make things vary depending on which tank it was interacting with. For example, each tank makes a different pitched driving sounds so the users can tell just from the sound effects which tank is driving. Also when displaying the points, the round winner, and the game winner, the UI text will match the color of the specific player’s tank.

## What to Come Back to
I don’t think I want to adjust anything in this tutorial unless I find any bugs. I’m pretty happy with the way the settings are. It feels more complete than my previous games as it includes many more components. 
