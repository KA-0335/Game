# Endless Runner

## Abstract
EndLess Runner is a PC game developed on Unreal Engine. It’s an endless game with various obstacles coming in the way of the player which it must avoid to survive. There are coins on the way which can be collected and a high score calculation system. The game keeps on going with endless obstacles, coins, and powerups coming in the way of the character.

## Introduction
EndLess Runner, a third person game, is as the name suggests a game in which the path spawns endlessly and our character runs on it. There is a basic objective of the game to achieve a high score. Coins are also there to collect them. During the game there are two types of obstacles which the player has to avoid. First category is box and the other is pipe. There are two types of power boosters as well: magnets, which attract all coins towards itself, and boots, which allow you to jump higher than normal. The game is playable on PC and can be packaged to other platforms as well like Android, Apple, Linux, Lumin, etc.

## Work Done
There are basically two main things which make the game work:
1. Third Person Blueprints
2. Runner Files and Meshes

### Third Person Blueprints
It contains the third person character and third person game mode. The character mesh can be made via Blender or other 3D modeling software or use the in-game basic character. The blueprints include:
- **Viewport**: Camera adjustments to define the angle and height of the character display.
- **Lerp Function and Death Graph**: Steer the character onto the specified course and make the character inactive upon touching obstacles.
- **Event Graph**: Controls player speed, direction, coin pickup, and other actions.

### Runner Files and Meshes
These contain all the files, blueprints, and code essential for making the game objects like coins, magnets, floor, main menu, pause screen, and endless spawning of the track.
- **Master Tile**: The platform where the character runs, spawning endlessly.
- **Pickup Objects**: Coins, magnets, and boots, with respective functionalities.
- **Runner HUD**: Displays game information on the screen and contains the pause button.

## Method
The game is made using Unreal Engine which has a very interactive and friendly user environment.
1. Select game mode (third person view for PC).
2. Set up camera and player character design.
3. Set floor tiles for endless spawning.
4. Apply arrow components for lane switching.
5. Set point scoring and attach to HUD.
6. Embed obstacles and pickup objects with respective blueprints.
7. Set ragdoll death for character upon collision with obstacles.
8. Implement high score system and menus.
9. Apply spawn weighing and controls for the platform.
10. Create and implement the main menu.
11. Fix bugs and set default game level.
12. Package the game for Windows 64-bit system.
13. Run the `CGLoopRun.exe` file to play the game.

## Controls
**Movement:**
- Switch Lanes: Left Arrow Key and Right Arrow Key
- Jump: Spacebar
- Break Jump: Down Arrow Key

**Menu Navigation:**
- Select Menu options: TAB key to highlight then Enter Key to select (Mouse after GameOver Screen and while in game)

## Tools/ Software
- Unreal Engine 4.24 - game development
- Blender - character modeling
- Laptop with Nvidia graphics card - Hardware

## Output


1. Main Menu
2. In-game
3. Super Jump
4. Game Over Screen


![Endless Runner](https://github.com/KA-0335/Game/blob/main/Screenshot%202024-06-08%20160611.png)

## References
- [VirtusHUB for game development](https://www.virtushub.com/)
- [Unreal Engine Documentation](https://docs.unrealengine.com/en-US/index.html)
- [Virtus Resources](https://virtushub.co.uk/runner-course/)
- [Discord GameDev Community](https://discord.gg/hs37bev)
- [YouTube](https://www.youtube.com/watch?v=yS-yQfo0lc0&list=PLZlv_N0_O1gbY4FN8pZuEPVC9PzQThNn1)

## Demo
Please download the files and run the CGLoopRun.exe file in the Endless Runner folder after reading the Instructions.txt file
