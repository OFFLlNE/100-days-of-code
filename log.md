# 100 Days Of Code - Log

### Day 30: March 4 2021

**Today's Progress**:

Working on my own website in Preact

**Thoughts**
I want to try to create a very ligthweight website for myself with Preact. Sounds like a fun challenge to try - will see how it goes.

### Day 29: March 3 2021

**Today's Progress**:

Trying to setup stuff to code on Windows

**Thoughts**
I was thinking of coding on Minecraft plugins and also was trying to finish my own portfolio website first. So I went with classic coding first and wanted to install the tools on my Windows computer and it was a hassle. Big pain :D
In the end I was just looking into Preact.

### Day 28: February 23 2021

**Today's Progress**:

Bought my domain and started building my portfolio

**Thoughts**
Will try to host my website on github pages and see if I can keep it very light-weight and fast loading portfolio

### Day 27: February 21 2021

**Today's Progress**:

Added game ticks

**Thoughts**
For some reason after each tick movement the health regens - feels like some part of the state is reseting for some reason. Need to investigate that next time.

### Day 26: February 17 2021

**Today's Progress**:

Fixed shooting animation bug
Read up on some expressJS docs

**Thoughts**
Spent quite a bit of time to figure out how to solve the animation bug I had from last time. Solution was much simpler than I first thought.
Rest of the time I spent on reading some expressJS docs.

### Day 25: February 16 2021

**Today's Progress**:

Shooting animation for the game

**Thoughts**
Got the shooting animation added to the turrets in the Game. Only bug is that after the wave ends the killing turret keeps on spinning - need to figure that out.
Otherwise I can not make the game to work on game-ticks and slowly finish the main functionality and think what to do next

### Day 24: February 15 2021

**Today's Progress**:

Played around with Memoization

**Thoughts**
This is pretty insane how much faster memoization is to the classic recursion fibonacci function. Good to know how this might come in handy when I need to greate a fibonacci function hehe :D

### Day 23: February 13 2021

**Today's Progress**:

Just learning about some hooks and new things to me

**Thoughts**
Memoization is pretty cool thing. I will try to throw something about it into my 100-days repo as well about it to show the performance increase compared to classic way of solving the fibonacci that was thought to me in uni

### Day 22: February 12 2021

**Today's Progress**:

Add enemy health in the Tower Defense and start killing the enemy when they are near the turrets

**Thoughts**
I am starting to have too many states I feel like. One day after I have the animation done and some proper monster and money scalability done, then I would love to refactor the code a bit as well

### Day 21: February 11 2021

**Today's Progress**:

Detect how many turrets there are around the enemy

**Thoughts**
I successfully managed to create a function that checks how many turrets there currently are around the enemy. With that I can understand how much damage the turrets can make per game tick.

Feeling pretty good and I am pretty confident I can make this game work. My only worry so far is that I can make it work with 1 enemy only :D But we will see what the future will bring!

### Day 20: February 10 2021

**Today's Progress**:

Steps towards turret detection

**Thoughts**
This felt like quite a tricky thing to do. So I was thinking a bit how can a turret detect the enemy. Then I decided it is easier to detect if there is a turret in the range of the enemy and how many of those if there are multiple. So I created a function that gets the surrounding coordinates of the enemy - now need to figure out how to start checking for turrets on those coords

### Day 19: February 9 2021

**Today's Progress**:

Turret creation in Tower Defense

**Thoughts**
First I was worried that the turret creation system is quite complex and I postponed that for some time by doing codewars etc. instead. Today my friend wanted to see my twitted updates on the game, so I decided to spend some time on it again.
In the end the turret creation went quite smooth and simple. Next big chunk of work will be the enemy detection

### Day 18: February 8 2021

**Today's Progress**:

CodeWars

**Thoughts**
Did 4 Katas in Codewars. Some of them I figured out the best practise method, but some solutions were so clever that I definitely learned a lot.

### Day 17: February 7 2021

**Today's Progress**:

CodeWars and CodeClash

**Thoughts**
Decided to check out code clash copetition stuff. Quite fun, but some problems are soo difficult to understand that I paused that for now.
Doing some Codewars Katas to get the feeling of some quick problem solving and to see what are some clever ways people have used so I can learn some docs around stuff to be more efficient in the future.

### Day 16: February 6 2021

**Today's Progress**:

Game turrets

**Thoughts**
Spent some time trying to figure out how to create the turrets. It did add that, but there is some state changing I need to involve now which might turn out to be tricker than I thought.

### Day 15: February 5 2021

**Today's Progress**:

Game turret creation

**Thoughts**
Spent some time to do a little codewars. After that I ended up playing more around my Game. Added the initial logic for the turret creation.

### Day 14: February 4 2021

**Today's Progress**:

Tests on Calculator

**Thoughts**
Focused purely on trying to get those tests working on Calculator. Finally managed to do so.
Then added all the tests to cover all main functionalities. Cleaned up some deps I added while I was debugging.

### Day 13: February 3 2021

**Today's Progress**:

Game movement fixed + refactoring

**Thoughts**
Figured out the Game movement bug. Since it was mapping the rows, what happenes was that it moved down and then the map went on to the next row and saw there character is there and then moved again. So basically whenever it was moving down it did it until it stopped moving down. The fix was to take out the movement function from the map function and we were cruising!
Cleaned up the Game code a bit and tried to make it short.
Also added some playerHealth, money and wave states.

### Day 12: February 2 2021

**Today's Progress**:

Trying to add Tests for Calculator
Working on Game movement

**Thoughts**
Most time spent on trying to get the Game moving. Almost works perfectly, but for some reason does 3 movement actions in a row when moving down. Need to figure out why this is happening. Quite difficult

### Day 11: February 1 2021

**Today's Progress**:

Trying to add Tests for Calculator
Adding unique key to element mapping in Game

**Thoughts**
Most time was spent on trying to get the tests running. I wrote a basic addition test, but couldn't get the yarn test to run. Need to read up on how to setup jest tests properly.
Quite happy that I found a way to get the index for a map in the Game, just quick documentation check and I was done with something I thought will be difficult to figure out

### Day 10: January 31 2021

**Today's Progress**:

Movement function in Game
Started reading about tests for Calc

**Thoughts**
In the console log I got the whole path movement done for the Game I am building. But I cannot get the game field UI to update - I guess I got to deal with state here, need to read up more on it. Also facing the issue where my React mapping key value is repeating all over the place.
Calculator did not get too much attention today, just started reading the jest docs on how to get started with the tests.

### Day 9: January 30 2021

**Today's Progress**:

Working on the Tower Defense JS Project
Some styling to the Calculator

**Thoughts**
Calculator starting to look pretty sleep - quite happy about that. I am starting to put more time towards the game (80-20) but would love to have a very nice calculator component finished at some point.
Game is quite interesting project, I would be very happy if I can finish it by the end of 100 days, we shall see! Today I was mostly working on trying to find pathfinding algorithms and tried to understand how can I implement them in my JS grid. But then it sparked that I do not need pathfinder alorithm with a fixed game path. So I just hardcoded the coordinates of all moves you can take on the path.

### Day 8: January 29 2021

**Today's Progress**:

Got Calculator fully functional with my buttons
Later in the day started small Game project

**Thoughts**
Finally, on the last second I figured out how to fix one of the last bugs I managed to find. Otherwise this is now fully functional. At some point I went out to see how there are some other React Hooks calculators done, but they had a bug as well so I just tried and continued brainstorming on my own Calculator. Pretty happy with it.
Next up Styles, Tests and proper TypeScript return types

Wanted to see if I will be able to create a tower defense game in JS. A little scared of the pathfinding and collision detection, but I will give it a try!

### Day 7: January 28 2021

**Today's Progress**:

Rewrote most of the functions to be better organized in Calculator

**Thoughts**
Again, I am almost there. It seems to work fine when I end up my math with the =. But if I chain multiple operations together as in 2*2*2 then it breaks somewhere. Really hoping to figure it out tomorrow so I can get on with styling + adding tests

### Day 6: January 27 2021

**Today's Progress**:

Continued on calculation logic in the Calculator

**Thoughts**
There are some edge cases coming in which are sometimes hard to understand why they appear. Code is starting to feel more like spaghetti code :(. Got to try to clean it up tomorrow or at least get it fully functional first

### Day 5: January 26 2021

**Today's Progress**:

Tried adding the math logic to Calculator.

**Thoughts**
It was a struggle. I think I tried to complete too big of a chunk of logic. So in the end I started going bit by bit. First just adding numbers together and clearing the input field when symbol is clicked.
From there I now need to add the logic again when a symbol is being clicked

### Day 4: January 25 2021

**Today's Progress**:

Read the React Hooks documentation
Added first hook into Calculator

**Thoughts**
Hooks turn out to be pretty easy to understand, I am surprised I couldn't understand them before.
Also added my first hook to the calculator which just changes the input based on which button I click. From there I now need to actually create a logic to store that input for longer etc.

### Day 3: January 24 2021

**Today's Progress**:

- Calculator:
  -- Added Sass
  -- Created CalculatorButton component
  -- Mapping all buttons with the button component
- Reading about React Hooks

**Thoughts** Hooks been a around for quite some time now, but I am finally taking the time to actually read the documentation about them and to properly understand it. So far the useState one seems pretty straightforward. After that I believe I can finally add some button functionalities to my calculator

### Day 2: January 23 2021

**Today's Progress**: Starting to build a Calculator

**Thoughts** I was stuck trying to figure out why my arrow function requires a return after adding JSX.Element as return type in Calculator. As it was very late at night when I found the time to do that daily coding hour I was a little exhausted and just wrote the base for the Calculator and the action plan what needs to come next.
Also I believe I need to read up on TypeScript itself and finally understand how Hooks work. So might dedicate some time for that

### Day 1: January 22 2021

**Today's Progress**: Trying to set up React app from scratch which would use TypeScript

**Thoughts** A little more difficult that I imagined. I tried to use the tutorials only without reading any documatation.
I also wanted to avoid CRA, so I could try it all myself. Next time I might try to invest more time into documatations

**Link(s) to work**

1. [100 Days](https://github.com/OFFLlNE/100-days)

---

### Attempt at it in 2017!

### Day 1: January 3, Tuesday

**Today's Progress**: Started doing the FCC JavaScript Calculator. Did make simple HTML/CSS calculator. Started implementing some JS and found a great
extension which makes writing that JS app alot simplier.

**Thoughts** Initial idea is to make a calculator look-a-like thing in HTML/CSS .When it kind-of looks fairly decent, I will start implementing JS.

**Link(s) to work**

1. [JavaScript Calculator](http://codepen.io/OFFLlNE/full/ggOmMy)

### Day 2: January 4, Wednesday

**Today's Progress**: Added Google analytics to my webpage.After that trying to work on my
JS calculator. I was wondering why I couldn't save my pen. Guessed that it saved automatically and no changes made then...
Closed my codepen and when I came back all the progress was lost... I realized that I was not logged in. So yeah, a bit
work lost today :/

**Thoughts** Thought adding analytics would be harder.. :D
Stuck on adding Math.eval() into my html element (".valueScreen").html(math.eval("1+2")) does not return me that, will keep trying to solve that

**Link(s) to work**

1. [JS Calculator](https://codepen.io/OFFLlNE/full/ggOmMy)

### Day 3: January 5, Thursday

**Today's Progress**: Pretty much finished my javaScript calculator. Needs some minor tweaks

**Thoughts** math.eval() extension made my project alot easier than it would've been w/o it

**Link(s) to work**

1. [JS Calculator](https://codepen.io/OFFLlNE/full/ggOmMy)

### Day 4: January 6, Friday

**Today's Progress**: Finished my JS Calculator. Also created a FB Messenger bot

**Thoughts** Thought I should make it look a little more like a calculator and did it.. And now it
actually does look pretty cute.
Making the messenger bot is really cool experience. Only problem currently is to get it public

**Link(s) to work**

1. [JS Calculator](https://codepen.io/OFFLlNE/full/ggOmMy)

### Day 5: January 7, Saturday

**Today's Progress**: Was looking for some cool css-tricks for my pomodoro timer

**Thoughts** Most coding done, was at night by arraging Particles.js

**Link(s) to work**

1. [Particles JS](http://codepen.io/OFFLlNE/full/JEdegK)

### Day 6: January 8, Sunday

**Today's Progress**: Fixed codepen bug on my particles.js. Also created sliders for Pomodoro timer

**Thoughts** Particles.js did not work properly on codepen, so had a bugfix

**Link(s) to work**

1. [Particles JS](http://codepen.io/OFFLlNE/full/JEdegK)
2. [Pomodoro timer](https://codepen.io/OFFLlNE/pen/egNMKa)

### Day 7: January 9, Monday

**Today's Progress**: Finished my pomodoro timer.

**Thoughts** Took longer than I expected, but not it is ready and awesome!

**Link(s) to work**

1. [Pomodoro timer](https://codepen.io/OFFLlNE/full/egNMKa)

### Day 8: January 10, Tuesday

**Today's Progress**: Algorithm programming and helping people on FCC/help

**Thoughts** Learned some regex and some JS programming which is much needed

**Link(s) to work**

### Day 9: January 11, Wednesday

**Today's Progress**: Algorithm programming and helping people on FCC/help

**Thoughts** Learned that JS does not like decimal numbers. And some sneaky programming
**Link(s) to work**

### Day 10: January 12, Thursday

**Today's Progress**: Some CSS for tic-tac-toe. Helping people on FCC/Help

**Thoughts** Started my tic-tac-toe project. Seems to be the most difficult challenge I have faced so far.
**Link(s) to work**

1. [Tic-Tac-Toe](https://codepen.io/OFFLlNE/pen/zNqaoB)

### Day 11: January 13, Friday

**Today's Progress**: FCC/HELP and working on my tic-tac-toe project

**Thoughts** Creating a board was damn difficult but finally figured out a working one
**Link(s) to work**

1. [Tic-Tac-Toe](https://codepen.io/OFFLlNE/pen/zNqaoB)

### Day 12: January 14, Saturday

**Today's Progress**: FCC/HELP and working on my tic-tac-toe project

**Thoughts** I managed to create and endless loop which resulted me losing my 7 hours of progress since I did not save once and autosaved
did not seem to install anything either..
**Link(s) to work**

1. [Tic-Tac-Toe](https://codepen.io/OFFLlNE/pen/zNqaoB)

### Day 13: January 15, Sunday

**Today's Progress**: FCC/HELP and working on my tic-tac-toe project

**Thoughts** Finished my tic-tac-toe with dumb AI(random moves) which I might fix in the future
**Link(s) to work**

1. [Tic-Tac-Toe](https://codepen.io/OFFLlNE/pen/zNqaoB)

### Day 14: January 16, Monday

**Today's Progress**: FCC/HELP and finishing 1 algorithm on FCC

**Thoughts** God damn difficult algoritm
**Link(s) to work**

### Day 15: January 17, Tuesday

**Today's Progress**: FCC/HELP and completing some Advanced Algorithms on FCC

**Thoughts** Feeling good being so close to my Front-end cert
**Link(s) to work**

### Day 16: January 18, Wednesday

**Today's Progress**: FCC/HELP and Trying to make my own webpage responsive

**Thoughts** Many hours on working some responsiveness
**Link(s) to work**

### Day 17: January 19, Thursday

**Today's Progress**: FCC/HELP and Trying to make my own webpage responsive

**Thoughts** Many hours on working some responsiveness
**Link(s) to work**

1. [Portfolio](offllne.github.io/Portfolio/Portfolio)

### Day 18: January 20, Friday

**Today's Progress**: Added all my FCC projects to Github

**Thoughts** Some work to get everything to work locally
**Link(s) to work**

1. [Projects](https://github.com/OFFLlNE/Projects)

### Day 19: January 21, Saturday

**Today's Progress**: Beta testing beta.FCC

**Thoughts** Nothing new on coding, but adleast finding some bugs
**Link(s) to work**

### Day 20: January 22, Sunday

**Today's Progress**: Did complete my last Front-end algoritm on FCC, Simon game left!

**Thoughts** Feeling great. about to get my FE cert on FCC
**Link(s) to work**

### Day 21: January 23, Monday

**Today's Progress**: Started my Simon's game. Also checked a bit of my udemy web dev course

**Thoughts** Feeling great. about to get my FE cert on FCC
**Link(s) to work**

### Day 22: January 24, Tuesday

**Today's Progress**: Finished my initial webpage structure

**Thoughts** Hoping to get as much as possible feedback, what I should be doing differently
**Link(s) to work**

1. [My portfolio](offllne.github.io/Portfolio/Portfolio)

### Day 23: January 25, Wednesday

**Today's Progress**: Changed from sliders to ul grid on my webpage

**Thoughts** Still have 17 issues to fix
**Link(s) to work**

1. [My portfolio](offllne.github.io/Portfolio/Portfolio)

### Day 24: January 26, Thursday

**Today's Progress**: Continued my work on my Simon game

**Thoughts** Slight progress made, but today have been a busy day, so not able to do as much coding as I would like to
**Link(s) to work**

1. [Simon Game](https://codepen.io/OFFLlNE/pen/XpgrZE)

### Day 25: January 27, Friday

**Today's Progress**: Continued my work on my Simon game. Did some regex addition to FCC Camperbot

**Thoughts** Slight progress made. Timeout function sometimes works sometimes it does not work..
**Link(s) to work**

1. [Simon Game](https://codepen.io/OFFLlNE/pen/XpgrZE)

### Day 26: January 28, Saturday

**Today's Progress**: Continued my work on my Simon game, Helped some people on FCC Chat

**Thoughts** Most coding will be done at night after I get home
**Link(s) to work**

1. [Simon Game](https://codepen.io/OFFLlNE/pen/XpgrZE)

### Day 27: January 29, Sunday

**Today's Progress**: Continued my work on my Simon game, Helped some people on FCC Chat, Also solved 5 issues on my porfolio

**Thoughts** Good day, tho I solved 5 issues, I found 2 new ones
**Link(s) to work**

1. [Simon Game](https://codepen.io/OFFLlNE/pen/XpgrZE)
2. [Portfolio](https://offllne.github.io/Portfolio/Portfolio)

### Day 28: January 30, Monday

**Today's Progress**: Continued my work on my Simon game. Might do some issue solving later today

**Thoughts** Very close to finishing that Simon Game.
**Link(s) to work**

1. [Simon Game](https://codepen.io/OFFLlNE/pen/XpgrZE)

### Day 29: January 31, Tuesday

**Today's Progress**: Did some beta.FCC ES6 challenges. for QA and to learn to do them myself

**Thoughts** managed to get Front-End Cert yesterday, still stoked about that
**Link(s) to work**

1. [FCC Front-End Certificate](https://www.freecodecamp.com/offllne/front-end-certification)

### Day 30: February 1, Wednesday

**Today's Progress**: Did some beta.FCC QA and solving the challenges.

**Thoughts** Getting close to web-responsiveness cert :p
**Link(s) to work**

1. [BETA fCC](beta.freecodecamp.com)

### Day 31: February 2, Thursday

**Today's Progress**: Did some beta.FCC QA and solving the challenges. Did solve all of the Responsive web-dev ones.

**Thoughts** Responsive Web-Dev cert :tada:
**Link(s) to work**

1. [BETA fCC](beta.freecodecamp.com)

### Day 32: February 3, Friday

**Today's Progress**: Helping people on fCC Help. And looking into new fcc beta (QA)

**Thoughts**
**Link(s) to work**

1. [BETA fCC](beta.freecodecamp.com)

### Day 33: February 6, Monday

**Today's Progress**: Helping people on fCC Help. Also started setting up my java programming tools

**Thoughts**
**Link(s) to work**

1. [BETA fCC](beta.freecodecamp.com)

### Day 34: February 8, Wednesday

**Today's Progress**: Did some offline HTML programming.

**Thoughts** Interesting to try to figure out the code w/o being able to google for help
**Link(s) to work**

### Day 35: February 10, Friday

**Today's Progress**: Did some offline HTML programming on my own project.

**Thoughts** Interesting to try to figure out the code w/o being able to google for help. Also came home after TechChill Conference which was awesome
**Link(s) to work**

### Day 36: February 12, Sunday

**Today's Progress**: Java programming
**Thoughts** Soooo difficult and boring :D
**Link(s) to work**

### Day 37: February 13, Monday

**Today's Progress**: Java programming and did learn some regex basics
**Thoughts** Good olf regex which nobody understands
**Link(s) to work**

### Day 38: February 15, Wednesday

**Today's Progress**: Did some programming here and there. Some java, Some js, some html
**Thoughts** Read some articles - got some motivation back :D
**Link(s) to work**

### Day 39: February 16, Thursday

**Today's Progress**: Java Programming - mostly regex stuff
**Thoughts** Really annoyed with some parts that do not work as I intend them to work
**Link(s) to work**

### Day 40: February 14, Friday

**Today's Progress**: Hackathon FB messenger bot implementing
**Thoughts** 2 sleepless nights and 1 product
**Link(s) to work**

### Day 41: February 15, Saturday

**Today's Progress**: Hackathon FB messenger bot implementing
**Thoughts** 2 sleepless nights and 1 product
**Link(s) to work**

### Day 42: February 19, Sunday

**Today's Progress**: Hackathon FB messenger bot implementing
**Thoughts** 2 sleepless nights and 1 product
**Link(s) to work**

### Day 43: February 20, Monday

**Today's Progress**: Java programming
**Thoughts**
**Link(s) to work**

### Day 44: February 21, Tuesday

**Today's Progress**: Trying to create my own simple game
**Thoughts** A game that I used to play with friends in a textbook
**Link(s) to work**

### Day 45: February 22, Wednesday

**Today's Progress**: Created a xkcd messenger bot
**Thoughts** Bot which will post a random xkcd joke with a title + image
**Link(s) to work**

1. [xkcd messenger BOT](https://www.facebook.com/Bot-xkcd-1360945160643152/)

### Day 46: February 23, Thursday

**Today's Progress**: Was working on my previous bot
**Thoughts** Had to make some little changes before pushing it live
**Link(s) to work**

### Day 47: February 24, Friday

**Today's Progress**: Doing some Java and later web-project
**Thoughts** Today is the day when I really have to learn how to do back-end. Need to hide my DB touching :/ :O
**Link(s) to work**

### Day 48: February 25, Saturday

**Today's Progress**: Python coding and learning some back-end
**Thoughts** Don't like python.
**Link(s) to work**

### Day 49: February 26, Sunday

**Today's Progress**: Python coding and learning some back-end
**Thoughts** Have to learn how to set up a server and then connect DB to it and FE and stuff
**Link(s) to work**
