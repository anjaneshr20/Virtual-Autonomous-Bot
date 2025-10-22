# Virtual-Autonomous-Bot

<img width="723" height="687" alt="image" src="https://github.com/user-attachments/assets/a1682b6b-81e2-4e6d-a13b-f0d86181361d" />


Arena Description
There are 2 paths (inner and outer square) and there are 4 connecting paths of different colours joining them.
Bot can change from outer path to inner path or vice versa. Bot is allowed to move in a clockwise direction only. The portion of the arena in black colour is restricted for the movement of the bot.
There will be 3 shapes (square, circle and triangle) of 2 different colours, distinguishing each block in 6 different ways. All shape colours might change but they will be distinguishable easily. The position of shapes in the final area will not be the same as the indicative pictures
On the outermost path there will be 4 arrows at the end of connecting paths pointing in clockwise direction. These arrows mark the Starting Zone where the bot will be placed initially on any one of the arrows.
The Centre of the arena is the home zone.
The bot has to traverse the arena, complete a full round and finish at the home zone.
A video feed from the overhead camera will be provided to the team. The team’s computer should autonomously instruct their bot throughout the arena using this feed.
Game Description
The bot is placed at one of the Starting Zones.
Team will be given an abbreviation which associate to specific colour and shape. RT for Red Triangle. RS for Red Square. RC for Red Circle. YT for Yellow Triangle. YS for Yellow Square. YC for Yellow Circle.
The bot must then find the closest block which it can reach following a clockwise path. If two positions with the required colour and shape are at the same distance from the bot then the bot may choose either.
Signal must be sent to when bot stops moving.
As soon as the bot stops moving, bot has to ask for input using the function provided.
This continues till bot has completed a full round around the center, Then it should move to home via the connecting paths that it started on.
On reaching home the bot should signal that it has finished the task.
