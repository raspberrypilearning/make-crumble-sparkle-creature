## Challenge: make the Sparkles pulse

Can you create code to make your Sparkle creature's eyes pulse from off to bright red, back to nothing and so on forever?

That means you should make the Sparkles get gradually getting brighter and brighter and then gradually dimmer and dimmer. To do this, use variables to control the RGB values, like you did in the program to gradually change the Sparkles' colours.

--- no-print ---

![Pulsing red eyes sequence](images/step13challengeSequence.gif)

--- /no-print ---

--- print-only ---

![Pulsing red eyes sequence](images/step13challengeSequence.png)

--- /print-only ---

--- hints ---

--- hint ---

Create your program so that:
1. When the `program starts`{:class="crumblebasic"}
1. A `red value`{:class="crumblevariables"} variable is set to `0`{:class="crumblevariables"}
1. Then `forever`{:class="crumblecontrol"}
1. Use the variable to keep on `increasing`{:class="crumblevariables"} the `red`{:class="block3myblocks"} RGB value of the `Sparkles`{:class="crumblesparkles"} by 5 `until`{:class="crumblecontrol"} it `equals 255`{:class="crumbleoperators"}
1. Then `decrease`{:class="crumblevariables"} the `red`{:class="block3myblocks"} RGB value of the `Sparkles`{:class="crumblesparkles"} by 5 `until`{:class="crumblecontrol"} it `equals 0`{:class="crumbleoperators"}.

--- /hint ---

--- hint ---

You need to use the blocks below to create the pulsing colour sequence code.
To create the program to make the creatures eyes pulse red, use the blocks below in the right order:

![Sparkle pulsing red eyes sequence code parsons problem](images/step13challengeSequence_parsons.png)

There are **two** `do until`{:class="crumblecontrol"} loops, and both belong **inside** the `do forever`{:class="crumblecontrol"} loop.

--- /hint ---

--- hint ---

Your program should look like this:

![Sparkle pulsing red eyes sequence code solution](images/step13challengeSequence_solution.png)

Click on the green triangle **play** button and check that your creature's eyes pulse as you expect.

--- /hint ---

--- /hints ---


