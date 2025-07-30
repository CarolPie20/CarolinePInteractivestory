# CarolinePInteractivestory
READ ME – Caroline Piesco
Word count- 520
My story is based on the copyright free version of "Alice's Adventures in Wonderland" by Lewis Carroll.

List of four different decision points-
(Lines 11-15) You are Alice, After falling down a peculiar rabbit hole, you land softly in a narrow, dim hallway with many doors and a single key resting on a pedestal.
You see that the hallway stretches endlessly. The ceiling glows faintly, and behind you, the rabbit hole is gone.
(Decision 1)* [Open the nearest door] -> hallway_door
(Decision 2)* [Examine the key] -> examine_key

(Lines 23-26) You step through a round wooden door and into a circular chamber with two twisting paths:
(Decision 1)* [Take the garden path with blooming vines] -> garden_path
(Decision 2)* [Take the shadowy forest path] -> forest_path

(Lines 29-34)You find the **Cheshire Cat**, hovering with his wide mysterious grin.
"Would you help me untangle a riddle, dear Alice?" he asks, tail flicking lazily.
(Decision 1)* [Help him solve the riddle] -> help_cat
(Decision 2)* [Ignore the Cat and keep walking] -> ignore_cat

(Lines 49-52) A field opens before you. A glowing pedestal stands in the center with a locked box.
(Decision 1)* [Use the key to open the box] -> open_box
(Decision 2)* [Ignore it and follow the garden trail] -> final_crossroad
In my story I have 3 different possible endings that players can choose from. The list of these are below:

=== ending_wonder ===
You step through the golden portal and float upward like a dandelion seed on a breeze. You awaken beneath a tree in the real world—but the world feels brighter, more curious. Children listen closer to your stories now, and sometimes, rabbits pause as if they almost recognize you. Wonder never quite leaves you.
To achieve this ending, you must help the Chesire cat with the riddle and take the key  to open the box, eventually, this will lead you to a glowing portal or a quiet portal. If you enter the glowing portal you will escape.

=== ending_stay ===
You refuse both portals. Instead, you stroll into the whispering woods beyond the gate. No ending finds you—only more paths, more characters, more nonsense and possibility. You are not lost. You are *becoming*. In Wonderland, some stories never end.
To achieve this ending players will have to ignore the portals and keep wandering through wonderland.

=== ending_neutral/madness===
You step into the quiet portal. No laughter. No golden glow. Just fog. You wander through an in-between space—neither madness nor clarity.  Eventually, even Wonderland forgets you're there. Or maybe you're dreaming still.

To achieve this ending, you can either help the Cheshire cat and have a choice of fate, ignore him and the key, join the Mad hatter at the tea party or ignore him and walk away . ( This is the unlucky fate as players will have no choice but to enter.)



You can find the variables and conditionals on: 
Variables (lines 1–2):
Wonder and Madness track the player’s choices.
Conditionals:
Conditional 1 (line 92): Wonder >= 2 → determines if the gold portal unlocks.
Conditional 2 (line 99): Madness >= 2 → determines if the strange portal unlocks.

My two HTML/CSS changes include: 

Theme changes, including colors, shadow effects, box layouts shown in the style.css.
(Players can choose between two different color modes)
(Lines 5-143)- Light theme 
(Lines 147-211)- Dark theme

