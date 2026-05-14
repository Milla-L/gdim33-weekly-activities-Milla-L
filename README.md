# GDIM 33 In-Class Activities
## W1
### Activity 1

[Vertical Slice Brainstorm](https://github.com/user-attachments/files/26424569/GDIM.33.Brainstorm.pdf)

1. A lot of 2D themes are emerging from my brainstorm. I definitely want to do a visual novel rooted in the kind of Alice in Wonderland type fantasy. I want there to be some kind of watching or watcher mechanic as shown by the eyes. As varied as they are, I have a lot of roots in a horror or psychological horror environment. My friendship/relationship bar takes inspiration from the Sims 4 where there might be another menu to display relationships. I want there to be some sort of animal aspect, though I am unsure of where I want to incorporate.  
2. We are both doing horror games. She is making a sort of Back Room chaser. A run around with a stabbing feature to attack. She is going to use chasing and hiding as the main mechanics. Her aesthetics are creepy, distorted, and 3D with a lot of inspiration on body horror. 
3. The TA, Eric, I talked to enjoys FPS and multiplayer games that are not very horror. He likes GTFO but can not do pure horror games.

### Activity 2
<img width="3300" height="2550" alt="Vertical Slice Breakdown" src="https://github.com/user-attachments/assets/e490f5e5-d92b-4596-ad54-24856b0cca94" />


## W2
None


## W3
### Activity 1
<img width="3300" height="2550" alt="Updated Vertical Slice Breakdown" src="https://github.com/user-attachments/assets/f956b59d-6e48-4567-90e9-8427661a682c" />

### Activity 2
1. It is advantageous to make the event name "clickNpcEventName" because it tells you that the transition to the event is going to happen by clicking on the NPC very clearly. 

2. A Debug.Log() that I used was in the state machine transitions to check if the transitions were actually switching. When the Debug.Log() didn't show up, I knew it didn't work and as a result, immediately was able to find the source of the problem to fix. 

3. The Set Cursor Lock State is very relevant to my Vertical Slice because I am doing the visual novel and so I will need the cursor to be set and manueverable. 

4. The concept of a "game stste" is also very relevant to my Vertical Slice because it may be a really good means of tracking NPC relationship states with the Player based on the dialogue chosen by the player. 


## W4
### Activity 1
Playtesting Team: Eli, Minjoo, Ruth

Playtesting Goals: Test if dialogue runs properly

Playtesting Notes: Make sure UI actually is active in build, add tree textures

### Activity 2
1. A writer could absolutely write in more dialogue without touching any code. The only things the writer would have to touch are the ScriptableObjects and then dragging them between eachother. Because all of the dialogue is stored in the ScriptableObjects and all the coding does is refer back to the Scriptable Objects. 
2. The limit in many dialogue nodes the writer can write is that there can only be up to four buttons at a time. The dialogue could be endless, but there can only be four at a time.
3. The purpose of the Regenerate Nodes button is to put code written in a script into a new node, finding nodes that are not attached to any parents, and to update the nodes after the codes attached have been changes.


## W5
### Activity 1: Task Breakdown
1. Build Scriptable Object
	- Make scriptable object Dialogue Node
	- Build visual script to advance
	- Debug by putting in random button and testing they progress
2. Input Dialogue
	- Write out player dialogue
	- Write out NPC dialogue
	- Connect the nodes as needed
	- Debug by putting in the nodes and testing to see if the branching dialogue progresses as meant to
3. Attach Friendship variable to Scriptable Object 
	- Make Scene Variable Friendship
	- Set relationship value to Scriptable object
	- Make the Friendship variable go up or down based on the value in the scriptable object
	- Debug by adding Debug log to show the Friendship variable to check if it changes

### Activity 2: Class work
In class, I wrote out more dialogue and edited the nodes so that they connected properly. I made sure that all parts of the dialogue progression worked along the progression of the advancer. As well as this, I made the Friendship variable, set it to 50, and made sure it updated when the button clicked. I had to add and subtract based on the if statement that I wrote and made sure it updated properly. 


## W6
### Activity 1
In this playtest, I have added new dialogue options along each pathway and background music that should change based on the state machine. I also fixed the trees to have color. 
The itch link is https://milla-l.itch.io/vs-pt-2. My playtesting goals are to see how the dialogue flows and if it works as well as if the music does actually change. 

Notes:
1. Need to scale UI much better.
2. Make sure text fits in buttons and in the NPC text slot.
3. The audio did not switch properly, so need to fix that.
4. The aesthetic buttons are nice.
5. Add more dialogue.

### Activity 2
1. The multiply setting makes the resulting nodes less saturated because the multiplied values are decimals so they decrease as they are multiplied. As they decrease, the values darken, thus making the colors darken.
2. If the alpha is multiplied by the multiply setting, then the resulting value would be more transparent because the alpha value would decrease to the lower transparencies.
3. The shader gets the UV values from the texture map that is put in through the 2D texture map sample. The UV values come from just that it is a texture map and needs the vector values so it takes the UV0 node.
4. I love math so it is very exciting that I can change colors with math. 

## W7
1. The data from the vertex color comes from the shiba mesh vertices.
2. The blending happens at the vertices because the information is being calculated at the vertices points from the color stored in the vertices being shaded over by the shader.
3. The shiba is colored in less detail because the color being called is that of the vertices in the shiba mesh rather than a seperate texture that is able to have more detail because it is an image.
4. The shiba's colors make it look like the normal has no real texture to it which is why the mesh colors are so smooth. 
