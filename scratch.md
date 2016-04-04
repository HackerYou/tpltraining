![](images/torontopubliclibrarylogo.png)

# Programming with Scratch!

What is scratch?

"Scratch is a new programming language that makes it easy to create your
own interactive stories, animations, games, music, and art -- and share your
creations on the web."

Because Scratch has been designed for kids, it's easy to learn and use - but it still teaches some fundamental programming concepts that can create complex programs, games, and educational tools.

Scratch can help kids learn about:

- manipulating **variables** - chunks of computer memory - to store and retrieve data
- using **operators** including arithmatic (+ - > <), logic operators (and, or not), contcatnation operators (this joins sentences together), and even triginometry
- understanding **control flow** - the way computers move through stages of a program
- altering flow with **conditional statements** and **loops**
- **event handling** - writing code that responds to events like key presses and mouse clicks
- **multimedia programming** including drawing, animation, and sound.
Scratch programs are built using blocks in that interconnect with each other to perform tasks. There are a couple key blocks to look at, Events, Motion and Control. These blocks allow you to control the sprite, or sprites you have on the screen. The interface is broken up into a few important areas.

#### The Scratch Environment

- STAGE: the main area where information is displayed / stuff happens. Usually to start a program running, you click the green flag.
- SPRITES WINDOW: sits below the stage, and contains a list of sprites (animated images) that you're using in your current project. We can control these sprites with our program.
- BLOCK PALLETE : This section in the middle of the window contains all the programming blocks you can use. They are organized into categories, detailed below.
- SCRIPTS AREA : This section to the right of the stage contains all the programming blocks (sequences of instructions). You can drag blocks from the block pallette into the scripts area to build up your scripts.



## Block Overview

Here are a couple key block types that will help you program some great projects!

### Events blocks
Used to start a program, should the program start on the click of the green flag, or when a key is pressed?

### Motion
The Motion blocks are used to locate, orient, and move a sprite (their position on the stage).

### Control
The Control blocks give you the ability to control the flow of your program, should something loop 10 times? Should something only run if a condition is true?

### Operators
The Operators blocks let you do addition, pick a random number, or check if something greater than something else.

### Looks
The Looks blocks have instructions for setting the colour, size, visiblity of a sprite.

### Sensing
The Sensing blocks get some information from the user or some other part of the page.

### Sounds
The Sounds block let us use a sound library, you can also upload your own sounds to use in your programs.

------

### Level 1

#### Challenge: Walk the walk

**Objective:** Pick a sprite, you can use the cat that is the default, or pick a new one. Can you make the character move across the screen 10 steps 10 steps at a time?

**Where to guide learns:**

- **Events** (dark gold) - use these blocks to determine when the movement should start.
- **Motion** (dark blue) - use the move block to determine how far to move the sprite.

**Possible Solution:** https://scratch.mit.edu/projects/104065802/


#### Challenge: Click and move

**Objective:** When you click on the sprite(cat) can you make it glide to x 100 and y 0 and then say something?

**Where to guide learns:**
- **Events** (dark gold) - use these blocks to start some code, there is a click event for example
- **Motion** (dark blue) - these blocks are used to move the sprite around, you can more in steps, rotate, or maybe glide to an x/y position.
- **Looks** (royal purple) - the blocks in here allow you to change things about the sprites.

**Possible Solution:** https://scratch.mit.edu/projects/104066330/


#### Challenge: Square dancing

**Objective:** Scratch the cat wants to do dancing! Can you make them dance in a square? Have scratch move for 50 steps, wait 1 second turn 90deg and wait 1 second. Then repeat 4 times! Bonus challenge: can you make the cat draw a hexagon? What would you need to change?

**Where to guide learners:**
- **Events** (dark gold) - use these blocks to start some code, there is a click event for example
- **Motion** (dark blue) - these blocks are used to move the sprite around, you can more in steps, rotate, or maybe glide to an x/y position.
- **Controls** (gold) - controls are used to control the program, want it to repeat, wait, use some controls!
- **Pen** (green) - use the pen to actually draw your shape. You can set pen colour (numbers correspond to different colours) - can you make it choose a random colour every time around?


**Possible Solution:** https://scratch.mit.edu/projects/104066904/


### Level 2

#### Challenge: I Love Cheesy Puffs
**Objective:** You will need 2 sprites: one character to walk around the room, and a bowl of cheesy puffs! Can you make your character move around the space when you press the arrow keys (up, down, left, right) and, if they touch the bowl of cheesy puffs, say “I love cheesy puffs!” The character shouldn't say anything unless they are actually touching the bowl.

**Where to guide learners:**
- **Control** (yellow) - you’ll need to use some if statements to check if an arrow key is being pressed, and if the cheesy puffs are being touched. You’ll also need to figure out how to make these things happen all the time, not just once!
- **Sensing** (blue) - this is the section where you can detect different keyboard events and whether one thing is touching another on the screen.
- **Motion** (dark blue) - move your sprites around using the x and y axis. (hint: the y axis is up and down, and the x axis is left and right!)
- **Looks** (purple) - make your sprite say something here

**Potential Solution:** https://scratch.mit.edu/projects/104067543/



#### Challenge: Sneezing Cat
**Objective** Scratch the cat has to sneeze! When the S key is pressed, Make the cat say "ahhh" and grow 5 bigger 20 times. then, have the cat say "chew" and shrink the cat by 5 (repeat that 20 times too!)

**Where to guide learners**
- **Events** (Dark Gold) - tie the action to the 's' key using an event in this panel
- **Control** (yellow) - to have your block repeat, find a repeat loop here
-**Looks** (purple) - change what your sprite says and looks like here!

**Potential Solution** https://scratch.mit.edu/projects/104067955/

#### Challenge: Decorate The Rom!
**Objective** Scratch wants to decorate the room for you, but first he wants to find out how old you are! Can you make Scratch the cat ask you how old you are, and depending on what you answer - decorate the room differently? Decorate one room for kids that are younger than 5, one for kids that are between 5 and 10, and one for kids that are older than 10! Use whatever backdrop and other sprites you like - and have some fun with what happens in the room!

**Where to guide learners**
- **Sensing** (blue) - this is where you can get a sprite to ask a question. There is also an answer button that creates something called a variable - a place to store information that we can use in whatever way we want later. The answer will be equal to whatever the user types into the box when the question is asked!
- **Control** (gold) - we'll need to use some if statements here in combination with some operators (green, below) to check what the answer is, and if it fits our criteria. inside of these blocks, you can change the background, add more sprites, and do whatever you like inside!
- **Operators** (green) - this section contains math operations that will enable you to check whether the answer (age) meets certain criteria.

**Potential Solution** https://scratch.mit.edu/projects/104068102/

### Level 3


#### Challenge: Devin and the ghoul
**Objective:** Devin does not like ghouls! However this is one flying above them! Can you make a little game with two sprites, Devin and a Ghoul or ghost! Make Devin be able to move left and right with the arrow keys, and have the ghoul forever move 10 steps, but when they hit the edge they should bounce! Hint, rotate the ghoul at first to get them moving all over the screen. And if you have multiple sprites, clicking on one in the sprites panel will show you the scripts area for that sprite.

**Where to guide learners:**
- **Events** (dark gold) - use these blocks to determine when the movement should start.
- **Control** (yellow) - you’ll need to use forever and if statements to check for key events and things like that!
- **Sensing** (blue) - this is the section where you can detect different keyboard events and whether one thing is touching another on the screen.
- **Motion** (dark blue) - move your sprites around using the x and y axis. (hint: the y axis is up and down, and the x axis is left and right!)

**Possible Solution:** https://scratch.mit.edu/projects/104068927/

**Devin:**

**Ghoul/Ghost:**

#### Challenge: Spirograph
**Objective:** Use a sprite to draw a square (like in square dancing). This time, can you get your sprite to shift slightly and continue to draw more squares in a circular pattern like a spirograph? Bonus points if you can get the pen to change colours each square.

**Where to guide learners:**
- **Events** (dark gold) - use these blocks to start some code, there is a click event for example
- **Motion** (dark blue) - these blocks are used to move the sprite around, you can more in steps, rotate, or maybe glide to an x/y position.
- **Controls** (gold) - controls are used to control the program, want it to repeat, wait, use some controls!
- **Pen** (green) - use the pen to actually draw your shape. You can set pen colour (numbers correspond to different colours) - can you make it choose a random colour every time around?

**Possible Solution:** https://scratch.mit.edu/projects/104070096/

#### Challenge: Pong!
**Objective** Make a classic pong game. You have a paddle that can be controlled by the arrow keys, and a ball bouncing around the screen. Make sure you don't miss the ball! If the ball is lost, you lose! You will need to make your own paddle in the sprites menu by clicking on the paintbrush and drawing it! You'll also need a ball - you can either make your own or find one from the availabel sprites. Finally, edit the background of your game to have a red line at the bottom of the page, under your paddle - if the ball hits the red line, the game is over.

**Where to guide learners**
- **Events** (orange) Let's kick off the game and all the scripts when the green flag is pressed here.
- **Motion** (dark blue) This is where the code to control the motion of the ball and the motion of the paddle is. We will want to start the ball off somehwere each time, make it bounce off the edge if it hits the edge, and if it hits the paddle, bounce off that too and go in an unexpected (random) direction. For the paddle - set the paddle to follow the mouse in the x direciton to have it glide horizontally across the screen.
- **Control** (gold) we will want our game scripts to run indefinitely until the ball touches the red line, at which point we stop everything.
- **Sensing** (light blue) - detect whether the ball is touching the red line or the paddle sprite here.
**Possibile Solution:** https://scratch.mit.edu/projects/104070269/
