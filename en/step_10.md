## Create a random colour sequence

Now make your creature's eyes switch to random colours by randomly changing the RGB values.

--- task ---

To begin, take the `program start`{:class="crumblebasic"} block.

From the `control`{:class="crumblecontrol"} menu, add a `do 10 times`{:class="crumblecontrol"} loop block.

![Program start and repeat ten times blocks](images/sequence3_programStartAndLoop.png)

--- /task ---

--- task ---

**Inside** the `repeat`{:class="crumblecontrol"} loop, add a `set sparkle 0 to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} RGB value block and a `wait 100 milliseconds`{:class="crumblecontrol"} block.

Duplicate both these blocks, and then attach the duplicates to the originals.

In the **second** `set sparkle 0 to`{:class="crumblesparkles"} block, change from `Sparkle 0`{:class="crumblesparkles"} to `Sparkle 1`{:class="crumblesparkles"}.

In the **second** `wait`{:class="crumblecontrol"} block, change the value to `500 milliseconds`{:class="crumblecontrol"} (which is `half a second`{:class="crumblecontrol"}).

![Set Sparkle and wait blocks](images/sequence4_setSparkleAndWaitBlocks.png)

--- /task ---

For `Sparkle 0`{:class="crumblesparkles"}, create code to allow the Sparkle the full range of colours.

--- task ---

From the `Operators`{:class="crumbleoperators"} menu, get a `random 0 to 10`{:class="crumbleoperators"} block and place it in the coding workspace **unattached** to the rest of the code blocks.

In the `random 0 to 10`{:class="crumbleoperators"} block, change the maximum value to `255`{:class="crumbleoperators"}. Now you have a `random 0 to 255`{:class="crumbleoperators"} block.

Duplicate this `random 0 to 255`{:class="crumbleoperators"} block **twice**.

![Random number blocks](images/sequence4_setRandomNumberBlocks.png)

--- /task ---

--- task ---

Now place one `random 0 to 255`{:class="crumbleoperators"} block in **each** of the RGB value boxes of the `set sparkle 0 to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} block.

![Random RGB values for Sparkle 0](images/sequence4_Sparkle0RandomRGBValues.png)

Click on the green triangle **play** button and watch Sparkle 0 switch to completely random colours.

--- /task ---

For the other eye, `Sparkle 1`{:class="crumblesparkles"}, you're going to limit the random colour range. In this example, I use the colour range between red and purple, but you can try other ranges too.

--- task ---

Duplicate one of the `random 0 to 255`{:class="crumbleoperators"} blocks.

Place the duplicated block inside the `blue`{:class="block3motion"} value box of the `set sparkle 1 to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} block.

In the the `set sparkle 1 to`{:class="crumblesparkles"} block, set the `red`{:class="block3myblocks"} value to `255`{:class="block3myblocks"}. Leave the `green`{:class="block3operators"} value at `0`{:class="block3operators"}.

* `255`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} is red.
* `255`{:class="block3myblocks"}`0`{:class="block3operators"}`255`{:class="block3motion"} is purple.
* That means your `set sparkle 1 to`{:class="crumblesparkles"}`255`{:class="block3myblocks"}`0`{:class="block3operators"}`0 to 255`{:class="block3motion"} block changes the Sparkle's colour between red and purple.

![Random RGB values for Sparkle 0 and 1](images/sequence4_Sparkle1RandomBlueValues.png)

Click on the green triangle **play** button and watch Sparkle 1's colour change within its limited colur range.

--- /task ---

--- no-print ---

![random colour Sparkles](images/sequence4_finalSequence.gif)

--- /no-print ---

--- print-only ---

![random colour Sparkles](images/sequence4_finalSequence.png)

--- /print-only ---

