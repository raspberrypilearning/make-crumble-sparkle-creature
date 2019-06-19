## Colour sequence 5 - totally random Sparkles

Our last random Sparkle adventure willmix the random wait and the random colours and add in randomising which Sparkle changes!

--- task ---

Starting with our random colour code from colour sequence 4, delete the last two blocks in the `repeat`{:class="crumblecontrol"} loop so that we are left with one `set sparkle`{:class="crumblesparkles"} RGB value block and one `wait 500 milliseconds`{:class="crumblecontrol"} block.

![Set Sparkle and wait](images/sequence5_setSparkleAndWait.png)

--- /task ---

--- task ---

Get another `random`{:class="crumbleoperators"} block and place it in the `wait`{:class="crumblecontrol"} block as the `wait value`{:class="crumblecontrol"}.

Set the minimum value to `50`{:class="crumbleoperators"} and the maximum value to `500`{:class="crumbleoperators"}

![Set random wait](images/sequence5_setRandomWait.png)

--- /task ---

That's the random colour and random wait done. Now for the random Sparkle selection. We need to select either `Sparkle 0`{:class="crumblesparkles"} or `Sparkle 1`{:class="crumblesparkles"}.

--- task ---

Grab a final `random`{:class="crumbleoperators"} block and place it in the `set sparkle`{:class="crumblesparkles"} block in place of the `0`{:class="crumblesparkles"} that specifies `Sparkle 0`{:class="crumblesparkles"}.

Set the minimum value to `0`{:class="crumbleoperators"} and the maximum value to `1`{:class="crumbleoperators"}.

![Set random Sparkle](images/sequence5_setRandomSparkle.png)

And that's it. You have set random values for the colour, the interval and which Sparkle will change!

Time to click on the green play button and see what you've done.

--- /task ---

This code runs through pretty quickly with only `10 repeats`{:class="crumblecontrol"}. We could increase the number of `repeats but`{:class="crumblecontrol"} but this seems like a good time to use the `do forever`{:class="crumblecontrol"} loop.

--- task ---

Select a `do forever`{:class="crumblecontrol"} loop from the `Control`{:class="crumblecontrol"} palette and put it in your code workspace.

Pull the code out of the existing `do 10 times`{:class="crumblecontrol"} loop and put it inside the new `do forever`{:class="crumblecontrol"} loop.

Throw the old `do 10 times`{:class="crumblecontrol"} loop away by dragging and dropping it on the block palette area, and connect the new `do forever`{:class="crumblecontrol"} loop under the `program start`{:class="crumblebasic"} block.

![Set random Sparkle forever](images/sequence5_setRandomSparkleForever.png)

As the name suggests, the `do forever`{:class="crumblecontrol"} loop makes the code run continuously until the program is stopped.

Click on the green play button again and watch the random colours go on and on!

You can stop the program at any time by clicking the red stop button in the Crumble software window.

--- /task ---

