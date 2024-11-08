# Identifying and Defining

# PMI

## Rocket League

Plus: Heavily relies on hand-eye coordination, and provides a chellenge for people trying to progress higher in the game. It also requires teamwork and communication for a better chance at progression. 

Minus: The skill ceiling may be too high and a lot of people might struggle or try too hard to be as good as they want, which may result in addiction. 

Interesting: It is a unique game which introduces a combination of soccer and driving. 


## Minecraft 

Plus: A relaxing game which develops basic motor skills like hand to eye coordination. It allows for creative outside of the box thinking to survive and progress through the game.

Minus: Addiction, and it is an online game that may lead to cyber bullying.

Interesting: It contains different game modes like creative and survival, where people can focus on achieving a goal with their own environment. 

## Tetris

Plus: Strategic game which requires a lot of thinking to succeed and progress higher. 

Minus: The game gets inreasingly difficult and is very hard to master. It can cause people to get unmotivated and bored of the game quickly. 

Interesting: Quite a simple game with easy to understand mechanics, uncluding very few controls.


Need: To improve hand to eye coordination and and patience for children which allows for creativity and problem solving skills useful in the real world. 

Problem statement: It is helpful for young children to get engaged in games which provide insight and educate them in real world situations. Using a 2d game to visualise these ideas will be effective for people to use different strategies to progress through the game

Skill development: To develop the skills to make my game, I will use learn.unity for tutorials and explanations. 

# Requirements outline:

**Inputs:**
Directional keys will control movement in basic directions. Mouse/touchpad will control the direction the character will face. Extra keys will control any additional abilities or interactions.

**Processing:** 
Game will update the score in response to a specific goal that has been reached, which will be reset if any collisions are detected. The program will also update the position of the player. 

**Outputs:** 
Game will display the character position and score, in addition to sound effects based on the user's actions.

**Transmission:** 
My project does not require any data transmissions.

**Storage:**
The game will store the user's high score locally as well as any customised settings.

# Functional Requirements
**User Interaction:** The user will interact with the game through keyboard inputs. The provided inputs will manage movement of a character, any selected options, and additional abilities. W, A, S and D will control basic movements. Moving the mouse or touchpad will change the direction the character wil face for aiming. 

**Core Gameplay or Simulation Mechanics:** The player will need to control a character that moves in basic directions in order to dodge obstacles. The game will also allow users to collect power-ups while in the game. Some power-ups like shooters will be aimed by the player to destroy incoming obstacles for a better chance of survival. Other power-ups will be activated as soon as the player picks them up.

**Scoring and Feedback:** There will be a progress tracking system which will track how long the player will survive without colliding with any obstacles. There will be a scoring system based on how many seconds the player will survive. 

**Level Progression or Simulation Stages:** The player will advance through the game by unlocking new levels. This is done by completing a specific taks like surviving a certain amount of time. 

**Saving and Loading Data:** Data will be stored locally on the device that is being used. The progress will be saved and will load everytime the game starts. Game might give an option to save to cloud.

# Non-Functional Requirements

**Performance Requirements:** Since the game is saved locally, it doesn't need internet and will load is a reasonable amount of time (3-5 seconds). There shouldn't be any latency issues, and the game graphics will not be too high quality so there will be little to no delay. 

**Usability Requirements:** The game will include instructions which the user can view any time they want, as well as an on screen prompt that flashes onto the screen for a few seconds after playing the game. 

**Compatability Requirements:** The game must be compatible with PC, using the keyboard and touchpad/mouse.

**Scalability Requirements:** The game should be able to scale to add more levels and features that may increase personalisation. 

# Consideration of Social and Ethical Issues

**Equity:** The quality of being fair to everyone by valuing their own needs, in order for an equal outcome.\
**Accessability:** Being able to be used or reached by others.

## Accessability

My project should be usable for people of all abilities. Since the game requires a lot of hand-eye coordination, some people would progress and process information quicker than others. To combat this there would be some settings which allow players to customize sensitivity, controls and visuals. Some in-game assistance will also be implemented, and this would include some form of instructions or prompts which would help the player get used to the controls. 

## Privacy and Data Protection

My project won't collect any sensitive data, but it will store high scores and achievements. To increase security, the game will autosave locally so there will be no risk of data breaches. In addition, the game gives an option to save progress to the cloud as a way to access the game in multiple places while still adding security. 

## Fairness and Representation

My project will establish no form of harmful stereotypes, and it will not connect with any violations that may affect a person's opinion on the game. It will avoid unnecessary bias due to the fact that the characters will not be human - instead it will use objects like UFOs and vehicles to represent the player. Certain characters will only be available in certain levels depending on their theme, and they are even customizable.

## Mental and Emotional Wellbeing

My game will imply difficult gameplay but it shouldn't affect the user's mental health negatively while playing. The game will require a lot of hand-eye coordination so it may be difficult to get the hang of, but it is not necessarily fast paced and it will feel rewarding when completing echievements. 

## Cultural Sensitivities

The content in this game should not be offensive to other cultures. It is very unlikely to be the case, since the game will incoorporate levels which are only reflective of the natural world. It also shouldn't be misunderstood, as certain levels will retain their specific theme like 'Outer Space' or 'The Ocean'. 


# Researching and Planning

|Existing Ideas|Plus|Minus|Implications|
|---|---|---|---|
|Rocket League![Alt text](rl_image.jpg)|Heavily relies on hand-eye coordination, and provides a chellenge for people trying to progress higher in the game. It also requires teamwork and communication for a better chance at progression|The skill ceiling may be too high and a lot of people might struggle or try too hard to be as good as they want, which may result in addiction|It is a unique game which introduces a combination of soccer and driving. Implications I would use is the progression system. This will be applied as levels that get increasingly harder, to keep the player engaged in the game for a longer period of time.|
|Minecraft![Alt text](minecraft.webp)|A relaxing game which develops basic motor skills like hand to eye coordination. It allows for creative outside of the box thinking to survive and progress through the game|Addiction, and it is an online game that may lead to cyber bullying|It contains different game modes like creative and survival, where people can focus on achieving a goal with their own environment. In my own game, I could add an easy and hard mode to cater to more people's tastes and have a wider range of skill.|
|Tetris![Alt text](tetris.webp)|Strategic game which requires a lot of thinking to succeed and progress higher|The game gets inreasingly difficult and is very hard to master. It can cause people to get unmotivated and bored of the game quickly|Quite a simple game with easy to understand mechanics, uncluding very few controls. This will be similar to my game, as there will only be a few controls but will still require a lot of concentration to survive.|

## Flowcharts
![Alt text](Movement.png)

BEGIN Movement\
&nbsp; &nbsp; INPUT userinput\
&nbsp; &nbsp; IF 'A' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Move player left\
&nbsp; &nbsp; ELSE IF 'D' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Move player right\
&nbsp; &nbsp; ELSE IF 'W' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Move player up\
&nbsp; &nbsp; ELSE IF 'S' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Move player down\
&nbsp; &nbsp; ENDIF\
END Movement

![Alt text](Splashscreen.png)

BEGIN\
&nbsp; &nbsp; INPUT userinput\
&nbsp; &nbsp; IF 'Play' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Start game\
&nbsp; &nbsp; ELSE IF 'Quit' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; End game\
&nbsp; &nbsp; ELSE IF 'Instructions' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Show instructions\
&nbsp; &nbsp; ENDIF\
END

![Alt text](Ability.png)

BEGIN\
&nbsp; &nbsp; INPUT userinput\
&nbsp; &nbsp; IF player has ability THEN\
&nbsp; &nbsp; &nbsp; &nbsp; IF 'Right click' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Toggle ability\
&nbsp; &nbsp; ELSE IF 'Left click' pressed THEN\
&nbsp; &nbsp; &nbsp; &nbsp; Use ability\
&nbsp; &nbsp; ENDIF\
END

# Storyboard
![alt text](GameMenuFlow.png)

![alt text](SplashscreenScene.png)
|Assets|Code|Animations|
|---|---|---|
|There is a 'PLAY', 'SETTINGS' and 'QUIT' button. The background will contain an image of the earth. There is a spiral in the background to fill up empty space. Everything in the splashscreen is also monochrome.|'PLAY' will send the user to the level scene. 'SETTINGS' will send the user to the settings screen. 'QUIT' will close the program.|The picture of the earth in the background will be slowly rotating, and the details in the background will probably have some flashing or moving effects to keep it from looking static.|

![alt text](<Level 1.png>)
|Assets|Code|Animations|
|---|---|---|
|There is text in the corner that states the current level being played, and on the other corner there is a goal displayed which the player would follow. There will be a character sprite in each level, which will follow a different theme. There will be different obstacles each level. The dotted lines are also obstacles.|The inputs from the user include W, A, S, D. The user can either use a mouse or a touchpad to drag and aim.|The bullets will be constantly moving across the screen, and the player will have small animations when moving any direction.|

![alt text](<Level 3.png>)
|Assets|Code|Animations|
|---|---|---|
|There is text in the corner that states the current level being played, and on the other corner there is a goal displayed which the player would follow. There will be a character sprite in each level, which will follow a different theme. There will be different obstacles each level.The red marking on the ground is also an obstacle.|The inputs from the user include W, A, S, D. The user can either use a mouse or a touchpad to drag and aim.|The bullets will be constantly moving across the screen, and the player will have small animations when moving any direction.|

![alt text](SettingsScene.png)
|Assets|Code|Animations|
|---|---|---|
|There is a 'LOAD', 'ACCOUNT', 'PERSONALISATION' and 'HIGH SCORES' button. The background will contain an image of the earth. There is a spiral in the background. Everything in the scene is monochrome.|'ACCOUNT' will prompt the user to create an account. 'LOAD' will load all the data of the game. 'PERSONALISATION' will give the user options on how they want their game to look.|The picture of the earth in the background will be slowly rotating, and the details in the background will probably have some flashing or moving effects to keep it from looking static.|

![alt text](CharacterSelect.png)
|Assets|Code|Animations|
|---|---|---|
|There is a 'SELECT' button. The background will contain an image of the planet that reflects the theme of the level. There is a spiral in the background.|'SELECT' will make the user equip the current character and save it when they exit the scene. |The picture of the planet in the background will be slowly rotating, and the details in the background will probably have some flashing or moving effects to keep it from looking static.|

# Gantt Chart
![alt text](GanttChart.png)