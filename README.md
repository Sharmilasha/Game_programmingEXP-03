# Game_programmingEXP-03
EXP 03 - THIRD PERSON CHARACTER MESH
~~~
NAME: SHARMILA A
REG NO: 212221230094
~~~
AIM:
~~~
1.Import the animation assets: Obtain the animation files for jump, walk, and idle in a compatible format such as FBX or BVH. To import the animations, go to the Content Browser panel in Unreal Engine, right-click in the desired folder, and select Import

2.Create a Separate folder and Import the Animations to avoid any chaos

3.Create an animation blueprint: In Unreal Engine, animation blueprints are used to control character animations. To create a new animation blueprint, follow these steps: a. Right-click in the folder where you imported the mesh and select Create > Animation > Animation Blueprint.

b. In the Animation Blueprint Editor, click on the Event Graph tab.

c. Drag the new character mesh from the Content Browser and drop it onto the graph.

d. Connect the Output Pose pin of the mesh node to the Final Animation Pose pin of the Final Animation Pose node.

e. Save the animation blueprint.

4.Open the animation blueprint: Open the animation blueprint you created for your character in the Animation Blueprint Editor.

5.Create animation slots: Animation slots help organize different animations and control their blending. To create animation slots, follow these steps: a. In the AnimGraph tab of the Animation Blueprint Editor, right-click in the graph and select Add State Machine > Animation Layer.

b. Double-click the newly created animation layer to open it.

c. Right-click in the graph of the animation layer and select Add State Machine. d. Double-click the newly created state machine to open it.

e. Right-click in the graph of the state machine and select Add State.

f. Rename the state to "Jump" and repeat steps e and f to create states for "Walk" and "Idle".

6.Add animation assets to states: In each state, you will assign the corresponding animation assets. To add animation assets to the states, follow these steps: a. Double-click the "Jump" state to open it.

b. Right-click in the graph and select Add State Result.

c. Drag and drop the jump animation asset onto the graph.

d. Connect the Result node to the jump animation asset.

e. Repeat steps a to d for the "Walk" and "Idle" states, assigning the appropriate animation assets.

7.Create required Variables for the state’s like “ISJUMP”, “SPEED”.

8.Set up transition rules: Transition rules determine when the character transitions between different animations. To set up transition rules, follow these steps: a. Double-click the "Jump" state to open it.

b. Right-click in the graph and select Add Transition Rule.

c. Drag the transition rule from the "Jump" state to the "Idle" state.

d. Repeat steps a to c for the "Walk" state, creating transitions from "Idle" to "Walk" and from "Walk" to "Idle".

e. Configure the transition rules based on your desired conditions. For example, you might want to trigger the transition from "Idle" to "Jump" when the character jumps, and from "Jump" to "Idle" when the jump animation is finished.

9.Create a Anim Montage in Animation Folder To Manage the montages of the animations.

10.Connect the animation blueprint to the character blueprint: To connect the animation blueprint to the character blueprint and enable the animations in the game, follow these steps: a. Open the character blueprint associated with the third person character.

b. In the Viewport tab of the Blueprint Editor, select the mesh component of the character.

c. In the Details panel, under the Animation category, find the Animation Blueprint property.

d. Click on the dropdown menu and select the animation blueprint you created.

11.Test the character: Compile and save all the changes in the blueprints and animations. Now, you can test the character's jump, walk, and idle animations by clicking the Play button in the Unreal Editor.
~~~
## OUTPUT:
![SM](https://github.com/Sharmilasha/Game_programm![jw](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/00f7394c-2048-4ingEXP-03/assets/94506182/816f3ac6-3330-4217-9a5f-5eb77b150942)
![SD](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/895102b0-3134-48c8-a2c2-d1ead015f2cf)
![ID](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/b88946c4-ff4b-4a7f-bc19-d7268729795e)
![jw](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/801546f9-975d-4917-9605-26faf6c83a54)
![Am](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/e052716b-6815-4f38-b53e-a3de08fee117)
![Tp](https://github.com/Sharmilasha/Game_programmingEXP-03/assets/94506182/dce3d77b-81f9-4a21-b723-d918ab1079e2)
## RESULT
The third person character mesh has been successfully changed using animations.

