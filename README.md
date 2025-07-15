
# TI-84-Snake
A non jailbreak program to play snake on the TI-84+ CSE and TI-84+ CE coded by hand in TI-Basic on my calculator during spare time at school.

# Downloads & Compatibility
This program supports both the TI-84 Plus CE (CE) and the TI-84 Plus C Silver Edition (CSE).

You may find that version 1.0 works better on the CSE due to that version being more lightweight.

🔗[Latest Version (v6.0)](https://github.com/ZmaZes/TI-84-Snake/releases/tag/v6.0)

🔗[Old Version (v1.0)](https://github.com/ZmaZes/TI-84-Snake/releases/tag/v1.0)

Use the [TI Connect CE App](https://education.ti.com/en/software/details/en/CA9C74CAD02440A69FDC7189D7E1B6C2/swticonnectcesoftware#:~:text=TI%20Connect%E2%84%A2%20CE%20Software%20for%20Windows%C2%AE%20(EXE)) to transfer programs to your calculator.

# Controls
- Use the arrow keys to move
- Press mode to pause the game
- Press clear to end the game
- Press clear twice to skip the game over animation

# Options

|Setting|Description|Versions|
|--|--|--|
|Screen Wrap|If enabled, the edge of the screen will warp you to the opposite side instead of killing you.|1.0+|
|Speed|Either 1x or 0.5x; If 0.5x the game will run at half speed.|1.0-5.3|
|Tail Collision|If enabled, the head has collision with its tail. This is disabled by default on the CSE to improve performance.|4.0+|
|Apple Flicker|If enabled, the apple will flicker like it does in v1.0.|4.0+|
|Quick Start|If enabled, the game starts at the max speed.|4.0+|
|Initial Tail|The length (1-100) of the snake's tail at the beginning of the game.|4.0+|
|Stage Width|The width [half] of the game's boundaries. A width of 12 represents 24 horizontal squares of movement.|4.0+|
|Tail Pattern|If enabled, every 10th piece of tail will have an orange box around it.|4.0+|
|Turn Indicators|If enabled, pieces of the tail where the player turned will form a cross instead of a dot.|4.0+|
|Head Color|Controls the color of the snake's head. Not available on the CSE due to a bug in the OS.|5.0+ CE|
|Tail Color|Controls the color of the snake's tail. The border of the graphing window will also change to the closest color to this color, and the text on the main menu will also match this color.|5.0+|
|Reset Settings and High Score|Press Del on the settings screen to reset all settings to default and set the High Score to zero.|1.0-5.3|
|Reset Settings|Press the right arrow five times while selected to reset all settings to default.|6.0+|
|Reset High Score|Press the right arrow five times while selected to reset the High Score to zero|6.0+|
|Reset Settings Individually|Press Del while selecting any setting to reset that setting to its default value|6.0+|


# Variables
This program uses the variables listed below. Make sure not to store any important data in them before running the program. All variables (apart from H, which is used to store the high score) will have no effect on the game if changed while not running.

<details open>
<summary><h3>v6.0 and Newer</h3></summary>

**Number Variables:**

A, B, D, C, K, M, S, T, V, X, Y, Ans

**String Variables:**

Str1, Str2, Str3

**Function Variables:**

Y₀

**List Variables:**

∟SNAKE, ∟SNAKS, ∟TEMPA, ∟TEMPB

</details>

<details>
<summary><h3>v5.3 and Older</h3></summary>

**Number Variables:**

A, B, C, D, E, F, G, H, I, J, K, L, M, O, P, Q, R, S, T, U, V, W, X, Y, Z, Ans

(All number variables except for N, θ, 𝑛)

**String Variables:**

Str1, Str2, Str3

**Function Variables:**

Y₀

**List Variables:**

∟SNAKE, ∟TEMPA, ∟TEMPB

</details>
