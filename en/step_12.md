## Colour sequence 6 - gradual colour changes

Enough with the random changes. Now you are going to make a controlled gradual change from one colour to another.

To do this, you'll make a variable to represent the RGB blue value. You'll then set the blue RGB values of all Sparkles to that variable. As you change the value of the variable, the amount of blue in the Sparkle's colour will change too. 

You'll be seeing many blocks that we've not used before. Let's give it a try.

--- task ---

Begin with the `program start`{:class="crumblebasic"} block.

Now go to the `Variables`{:class="crumblevariables"} palette and click `Add New Variable`{:class="crumblevariables"}.

Type the name blue value and as you click RETURN the new variable `blue value`{:class="crumblevariables"} appears in the list.

![Adding a new variable](images/sequence6_addVariable.png)

--- /task ---

Now that you have created a variable to use, you need to set a starting value for it.

--- task ---

From the `Variables`{:class="crumblevariables"} palette grab a `let # = 0`{:class="crumblevariables"} block and connect it underneath your `program start`{:class="crumblebasic"} block.

From the very bottom of the `Variables`{:class="crumblevariables"} palette, take a rounded edge `blue value`{:class="crumblevariables"} block and slot it into the blackspace in the `let # = 0`{:class="crumblevariables"} block.

Leave the `blue value`{:class="crumblevariables"} set to 0.

![Setting the blue value variable](images/sequence6_setBlueVariable.png)

--- /task ---

To create a code that will turn the eyes gradually from red to purple, we want the RGB `red`{:class="block3myblocks"} value to always be `255`{:class="block3myblocks"}, the RGB `green`{:class="block3operators"} value to always be `0`{:class="block3operators"} but have the RGB `blue`{:class="block3motion"} value to move incrementally from `0`{:class="block3motion"} to `255`{:class="block3motion"}.

We are going to use code to `increase the blue value`{:class="crumblevariables"} `until`{:class="crumblecontrol"} it `equals 255`{:class="crumbleoperators"}.

--- task ---

From the `Control`{:class="crumblecontrol"} palette find the `do until`{:class="crumblecontrol"} loop and connect this to you code.

![Do until loop](images/sequence6_doUntil.png)

--- /task ---

--- task ---

From `Operators`{:class="crumbleoperators"}, find the hexagonal `0 = 0`{:class="crumbleoperators"} block and insert it into the `do until`{:class="crumblecontrol"} loop right after `until`{:class="crumblecontrol"}.

![Add a 0 = 0 block](images/sequence6_0equals0.png)

--- /task ---

--- task ---

From the `Variables`{:class="crumblevariables"} palette, take another rounded edge `blue value`{:class="crumblevariables"} block and place it into the first `0`{:class="crumbleoperators"} of the `0 = 0`{:class="crumbleoperators"} block.

Change the second `0`{:class="crumbleoperators"} to `255`{:class="crumbleoperators"}.

![Until blue value equals 255](images/sequence6_blueValueEquals255.png)

--- /task ---

The condition has been set and so the loop will `repeat until`{:class="crumblecontrol"} the `blue value`{:class="crumblevariables"} variable `equals 255`{:class="crumbleoperators"}.

Now we need to say what happens until that condition is met - until the `blue value`{:class="crumblevariables"} variable `equals 255`{:class="crumbleoperators"}.

--- task ---



![Set all Sparkles](images/sequence6_setAllSparkles.png)

--- /task ---



