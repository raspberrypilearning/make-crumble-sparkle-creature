## Colour sequence 3 - random Sparkles intervals

You are going to make your creature's eyes change at random intervals by using random numbers in the wait blocks.

--- task ---

Let's begin with the `program start`{:class="crumblebasic"} block and add a `do 10 times`{:class="crumblecontrol"} loop block from the `control`{:class="crumblecontrol"} block palette.

![Program start and repeat ten times blocks](images/sequence3_programStartAndLoop.png)

--- /task ---

--- task ---

Inside the `do 10 times`{:class="crumblecontrol"} loop, add two `set sparkle 0 to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} RGB value blocks. 

Change the second from `Sparkle 0`{:class="crumblesparkles"} to `Sparkle 1`{:class="crumblesparkles"}.

![Add set Sparkle blocks](images/sequence3_addSetSparkleBlocks.png)

--- /task ---

--- task ---

Set the `set sparkle 0 to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} RGB value blocks to values of your choice and add a `wait`{:class="crumblecontrol"} block under them.

![Set RGB values and add wait](images/sequence3_setRGBVauluesAndAddWait.png)

--- /task ---

Now you need another set of `set sparkle`{:class="crumblesparkles"} blocks and another wait block. You could pick them out from the block palettes as normal but the quickest way is to duplicate the ones that you already have.

When you duplicate blocks in Crumble, you always copy the block you are on and all the blocks below it.

--- task ---

Right-click on the first `set sparkle`{:class="crumblesparkles"} block and click 'duplicate'.

Drag the duplicated blocks inside the `repeat`{:class="crumblecontrol"} loop underneath your existing `wait`{:class="crumblecontrol"} block.

--- no-print ---

![Duplicate a set of blocks](images/sequence3_duplicateBlocks.gif)

--- /no-print ---

--- print-only ---

![Duplicate a set of blocks](images/sequence3_duplicateBlocks.png)

--- /print-only ---

--- /task ---

--- task ---

Change the values in the second pair of `set sparkle to`{:class="crumblesparkles"}`0`{:class="block3myblocks"}`0`{:class="block3operators"}`0`{:class="block3motion"} RGB value blocks to different values of your choice.

![Set second RGB values](images/sequence3_set2ndRGBVaulues.png)

--- /task ---

Now you're going to code the random wait between colour changes.

--- task ---

From the `Operators`{:class="crumbleoperators"} block palette, grab a `random 0 to 10`{:class="crumbleoperators"} block and place one inside each of your two `wait`{:class="crumblecontrol"} blocks.

If you had a `wait 1.0 seconds`{:class="crumblecontrol"} block, it will now wait a random amount between `0 to 10`{:class="crumbleoperators"} `seconds`{:class="crumblecontrol"}.

Change the random values to 1 and 3 to make a `wait`{:class="crumblecontrol"} `1 to 3`{:class="crumbleoperators"} `seconds`{:class="crumblecontrol"} block.

![Add random number blocks to the wait block](images/sequence3_addRandomNumberBlocks.png)

Click the green play button and see what your code does and what colours you have created.

--- /task ---

--- task ---

Try replacing the `wait 1.0 seconds`{:class="crumblecontrol"} blocks with `wait 100 milliseconds`{:class="crumblecontrol"} blocks.

Of course, `1 to 3`{:class="crumbleoperators"} `milliseconds`{:class="crumblecontrol"} is a tiny amount of time, so change the `random`{:class="crumbleoperators"} block values to something more suitable such as `300 to 2100`{:class="crumbleoperators"}. That would be the same as `0.3 to 2.1`{:class="crumbleoperators"} `seconds`{:class="crumblecontrol"}.

![Replace the wait blocks](images/sequence3_replaceWaitBlocks.png)

Click the green play button and see how the intervals have changed.

--- /task ---

Finally, let's try a simple variation to make the two eyes change at different times. In the example, I have reduced the random wait times to make the sequence run faster.

--- task ---

Duplicate one of the `random`{:class="crumbleoperators"} `wait`{:class="crumblecontrol"} blocks twice and place them so that there is a `wait`{:class="crumblecontrol"} block after each `set sparkle to`{:class="crumblesparkles"} block. 

![Add more wait blocks](images/sequence3_moreWaitBlocks.png)

Now the Sparkle eyes will take it in turns to change colour.

Click the green play button, observe the change and decide which sequence you like best.

--- /task ---

--- no-print ---

![random interval Sparkles](images/sequence3_finalSequence.gif)

--- /no-print ---

--- print-only ---

![random interval Sparkles](images/sequence3_finalSequence.png)

--- /print-only ---





