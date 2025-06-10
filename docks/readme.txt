Welcome to random scenario generator! This was origenally a simple test with arays of type string, but later got turned into hours of amusement.
To use this app, launch scengen.exe. After it's opened, press enter on generate scenarios in the main menu to generate Hilarious yet Nonsensical sinarios that will leav you laughing Uncontrollably.

Keyboard commands
Enter: Interacts with various menu items found in the app, if pressed.
Page up: Razes the generator music volume by 1 decibel, if pressed/held down.
Page down: Lowers the generator music volume by 1 decibel, if pressed/held down.
Home: Razes the generator ambience volume by 1 decibel, if pressed/held down.
End: Lowers the generator ambience volume by 1 decibel, if pressed/ held down.

File lists and their descriptions.
Actions.list. This file holds everything related to what the character does to you, such as if they brake something, snap something, or fracture something.
attacks.list. This file holds everything related to how the character performs something on you as a result of their actions, such as if they brake your nose with a baseball bat, stab you with a knife, or shoot your head with a gun, etc.
Bodyparts.list. This file holds everything related to where the character performs their actions resulting in an attack, such as if they shadder your jaw with a swift kick, they stranggle your neck with a rope, or they smother your face with a pizza.
Charnames.list. This file holds everything related to who's performing the action that results in an attack, such as Brad braking your neacaps with a hammer, Jack abliderating your spinal_colom with a stomp, or John crushing your nose with an uppercut.
Chartypes.list. This file holds everything related to what type of character you're facing off against, such as your Friend Raven frying your face with a fireball, your Cuzzen Jenna poaking your eye with a pencel, or your bully Deric mutilating your hands with a swift army knife.
Deaths.list. This file holds all of the messages givven to the player after there health reaches 0.
Effects.list. This file holds everything related to the bizarre, hilarious, or unfortunate status effects your character inflicted on you, without necessarily beating you up. These effects often result in embarrassing, annoying, or downright absurd consequences, such as your virtual_assistant Glen replacing your coffee with sawdust and making you nauseous and sleepy, or your vice_principal Brandon signing you up for a mime competition and leaving you legally mute for 24 hours, or your friend Mia gluing a Whoopee Cushion to your pants and turning you into the office laughing stock.
Moods.list. This file holds everything related to how the character feels after what they did to you, such as your sibling Bob braking your leg with a chain_wip because they were angry, your parent Jaimy kicking your nea with a right kick because they were upset, or your prison gard Mark slashing your face with a dagger because they were furious.
Pains.list. This file holds all of the messages givven to the player after they start to lose health.
Reasons.list. This file holds everything related to the causes of why your character attacked you in the firstplace resulting in their overall mood, such as your teacher Peater hitting your face with a book because they were disappointed that you weren't paying atencion in class, or your friend Mia punching your arm with a left_hook because they were sad that you were talking crap about them behind their back, or your child Brandon destroying your window with a baseball_bat because they were jealous that you were going to mcdonald's without them.
Templates.list. This file holds the structure of how all scenario messages are formatted. Each entry defines a category that contains a sentence template using placeholders like {pain}, {chartype}, {charname}, {action}, {bodypart}, {attack}, {mood}, {reason}, and {dmg}. These placeholders are dynamically replaced with randomized values from the other 9 scenario files during gameplay.
For example, a template might look like the folowing.
{pain} Your {chartype}, {charname}, {action} your {bodypart} with their {attack} because they were {mood} that you {reason}, causing you to lose {dmg}% of your health!
When constructed, this template generates the folowing text when used in the app. Ow ow ow! Your brother, Dan, shattered your ribs with their crowbar because they were enraged that you deleted their save file, causing you to lose 16% of your health!

Enjoy, and happy generating!
