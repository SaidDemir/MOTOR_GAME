# MOTOR_GAME
CS223 Bilkent Motor Game

About this project: In this project, the player will follow the movements of the motor and try to copy it through keyboard.
The game actually contains multiple modules which includes the ready modules that teachers gave us, so I don’t write detailed information about them.
First, I had to use a random generator in order to get 4 bits random number. In this part, I got help from several websites, but in the final plan, I created 16 bits random number but only used the last 4 bits for simplicity.
Then, I’m using this 4 bits random number to generate the motor movement with implementing the ready modules. 2 actions, which corresponds to 2 bits each.
After that, I get a value from the user through keyboard with using ready modules. And with that in mind, I compare it to the number that had been created by random generator.
If they are the same, then I increment the total score of the player which I’m displaying with using ready seven_segment module. If not, decrease it. Our points can be only between 9 and 0. User can also reset the score with a switch.

