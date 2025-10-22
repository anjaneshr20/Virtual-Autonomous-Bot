# Virtual-Autonomous-Bot

<img width="723" height="687" alt="image" src="https://github.com/user-attachments/assets/a1682b6b-81e2-4e6d-a13b-f0d86181361d" />


Arena Description

The arena consists of two square paths: an inner square and an outer square.

There are 4 connecting paths of different colours that join the inner and outer squares.

The bot can switch between the inner and outer paths using these connecting paths.

Movement is allowed only in the clockwise direction.

Areas marked in black are restricted, and the bot cannot move there.

The arena contains 3 different shapes — square, circle, triangle — each available in 2 colours, resulting in 6 distinct types of blocks.

The position and colour of the shapes may vary, but all will be easily distinguishable.

On the outermost path, there are 4 arrows at the ends of the connecting paths pointing clockwise. These arrows mark the Starting Zones, where the bot can be initially placed.

The center of the arena is designated as the Home Zone.

The bot must traverse the arena, complete a full clockwise round, and finish at the Home Zone.

A video feed from an overhead camera will be provided, and the team’s computer should autonomously control the bot using this feed.

Game Description

The bot starts at one of the Starting Zones.

The team will receive a shape-colour abbreviation, which corresponds to a specific block:

RT – Red Triangle

RS – Red Square

RC – Red Circle

YT – Yellow Triangle

YS – Yellow Square

YC – Yellow Circle

The bot must find the closest block matching the given shape-colour along its clockwise path.

If two matching blocks are equidistant, the bot can choose either one.

When the bot reaches the block and stops, it must signal that it has stopped.

The bot should then request the next input using the provided function.

This process continues until the bot has completed a full round around the center.

After completing the round, the bot must return to the Home Zone via the same connecting path it started from.

Upon reaching the Home Zone, the bot must signal that it has finished the task.
