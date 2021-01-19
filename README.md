**ManVSEvilForces**

*By Zairi Marion Pineda*

ManVSEvilForces is an Unreal Engine application for PC made using blueprints.

**Game Development:**

This game was developed using Unreal Engine 4 version 4.15.6, in the image you
can see the game structure.

![]https://cdn.discordapp.com/attachments/799826831368126464/801218788724310026/unknown.png

The game starts in a game map, there is a Player and an enemy’s spawner.

The game starts and you can see the map, then you must shoot to the enemies, you
can defeat the enemies, and the enemy’s spawner create more (always 6 in the
map), you can pick up ammunition (Max 100), you lose when you die, then you lose
your points and start again.

The map and some components are imported from Epic Games Marketplace.

When the game starts you can see a matinee cinematic

![](media/3173255a3cb24e91772da37fb9c5cac7.png)

And a widget with HUD

![](media/4946f100e6a98853a2bd2d0be29179c8.png)

Player’s blueprint controls movements and the action fire.

The enemies have many components as you can see:

Blueprint class to the artificial intelligence, Blackboard, Behavior Tree and
some Behavior Tree Tasks.

![](media/54d3b4a2d0a69350c895c910784963c7.png)

There is Behavior Tree. To control the enemy’s artificial intelligence, their
moves, and actions.

![](media/23270a94fffb7b23bd0738b77fe7b82f.png)

Also, there is the Game Mode, Game mode controls the enemies and player respawn.

![](media/524fce6acab09160028ee699d7871251.png)

The pickup ammunition has their own blueprint to control the floating movement
and when the player picks up it.

![](media/302392a89e9c575b3694566b5c3646b7.png)

If you want to see all project and how it works you can see it in the GitHub
repository:

<https://github.com/ZairiM/UnrealPlatzi>

There you can clone the project and see what is inside.

**Let’s Play:**

There is a link where you can find the game:

[**https://drive.google.com/file/d/1EL3y7wY_Du3tnjBn6ui6lyrFahtjSxc5/view?usp=sharing**](https://drive.google.com/file/d/1EL3y7wY_Du3tnjBn6ui6lyrFahtjSxc5/view?usp=sharing)

There you can see this:

![](media/0b3bcf098ab5f261ef558246e39ba02c.png)

You only need to download it. But you can see this message. It is ok the file
its ok, it will not destroy your PC, just download it.

![](media/273fe95b8e6073f0f1a7e12cf6b74fc9.png)

To play to need to download it, unzipped and run MyFirstProject application. You
can find it in
“\\ManVsEvilForcesRelease.zip\\UnrealBuild\\WindowsNoEditor\\MyFirstProject”

![](media/bbbd9f30e94b58a9f5eda33846e14343.png)

**Game Presentation:**

**What ManVsEvilForces is about?**

In ManVsEvilForces you are a man in a frozen cove. There are some enemies
patrolling, when they see you, they follow you and shot you. You can defeat them
shooting back, but there are an enemy’s spawner and the enemy’s will be
infinity, you have to survive.

**Game Rules:**

-   You move using ‘w’, ’a’, ’s’, ’d’, shot with left click and jump with
    spacebar.

-   You get one point when you defeat one enemy.

-   Enemies move random. You cannot know what the enemy’s next position is.

-   You and the enemies have life points, both lose life points when get damage
    both can lose if lose all the points.

-   When you lose all of life points you start in the map again with 0 points.

**Game Intro:**

When you start the game, you see an intro screen.

There is a bar that shows your life, another to show your ammunition and on the
right side a point
counter.![](media/85dc501ffb997508a09a47b3375e8aed.png)![](media/40b8fc95da9b564f21d87752dad1f350.png)

**Game Over:**

You lose when you lose all your life points. And now there are not ammunition
picks up and 0 points.

![](media/ac3680562137b25bbeccac125da1a55e.png)

