### Inspired Physics
Inspired Physics is an offshoot of my Refined Physics+ mod. One of the big issues I have to solve for that mod is how I can allow the boost and spin dash to co-exist in a modern Sonic title without making one more preferential than the other. After lots of thinking, experimenting, and tinkering, I ended up with something that felt inspired by older Sonic games where the boost is non-existent, hence the title of this mod.

In order to not beat around the bush, I'm gonna state outright that this mod is a one-time thing. Please do not expect updates for this mod in particular, I just wanted to share what I made with y'all :)

The rest of my development efforts for this game will be going towards Refined Physics. But just like with that mod, this is completely open source, and anyone can use the code I wrote as a base for their next project. Like literally just download the mod, open the .hmm file, and start building! All I ask is that if you do publish it, please credit me and all the other talented developers you may have based your work off of in the mod description :)

#### CHANGES
- Increased base running speed
- Running, rolling, and rail grinding momentum
- Slope physics while rolling
- Increased jump speed limit (makes incline jumps easier)
- Disabled boost while running
- Boosting lasts for half a second while grinding
- Air boosting has the same max time as Cyber Space
- Spin dash speed is now determined by how long LT is held/spammed during a spin charge
- Sonic can be controlled slightly while spin charging in the air
- Holding LT without spin charging makes Sonic roll based on his current speed
- Sonic sticks to the ground much better while rolling
- Spin dashing is a bit less floaty in the air
- Dynamic minimum rolling time
- Disabled spin move while standing still
- Spin move now lasts for 1 second max
- Increased maximum wall running speed
- Smoother wall running brake
- Decreased minimum grinding speed
- Decreased minimum sliding speed
- Removed overspeed air drag
- Matched parry timings with the other characters' timings

#### ISSUES
Due to the way I disable the boost after half a second while rail grinding, Sonic will exit the boost state, but the boost motion blur will still remain unless you do a spin dash, an air boost, or a very quick boost while grinding

#### MANDATORY HMM CODES
##### Animation
- Bouncy Jump Ball
- Disable Running Fall
- Sonic/Homing Attack Trick Animations

##### Camera
- Disable Spin Charge Camera

##### Cheats
- Player/Infinite Boost Gauge
- Skills/Always Unlocked Spin Dash

##### Fixes
- Literally everything in this category

##### Gameplay
- Disable Hit Stop
- Skills/Allow Spin Dash on Dash Panels
- Skills/Always Trickable Spin Dash Exit
- Skills/Disable Stomp Flip

##### Physics
- Classic Jump Deceleration
- Disable Decelerate Collision
- Reduced Homing Delay
- Retain Horizontal Velocity from Jump
- Tighter Jump Rotation
- Sonic/Retain Velocity from Enemy Bounce

##### UI
- Display/Hide Boost Gauge

#### CONFLICTING HMM CODES
##### Physics
- Disable Spin Charge Air Deceleration
- Sonic/Retain Velocity When Jumping Up Slopes

#### RECOMMENDED IN-GAME PHYSICS SETTINGS
- Starting speed: 25
- Jump deceleration: 50
- Set the deceleration rate: 50

#### RECOMMENDED MODS TO USE IN CONJUNCTION
[Fixed Spin Dash Animation by Braven](https://gamebanana.com/mods/472987)

#### FAQ
##### If Sonic can't boost, how can I beat SQUID?
I set Sonic to be in his boost state during automatic quickstep sections, which basically means that he'll be fast enough to catch up with SQUID.

##### How can I run fast on wall climb/run sections?
For running along a wall, I recommend charging up a spin dash towards the wall and holding RT while doing so; once you let go of the charge, Sonic will dash and start wall running (since you're holding RT) at the speed of your spin dash. For vertical walls, air boost into them and Sonic will carry over the air boost speed. For both occasions, Sonic will eventually slow down to his minimum wall running speed.

##### Any other tips you have?
Upgrade your speed! Upgrading your speed will increase your boost speed, air boost speed, and wall running speed. I wouldn't say this mod is 100% scalable to the game's RPG elements, but it scales relatively well.
