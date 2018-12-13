# Tic-Tac-Toe-README-Essay
Project 1 README Essay

Approaching Game Logic:

Tic-Tac-Toe was a bit of a traumatic experience for me. My original game-plan (ha!) was something simple and not very descriptive:

-Create basic HTML for the game including login/sign-up/password
-Build logic in JS to store needed information
-CSS styling

It seems so easy from that three line description. It was not (and my project showed it.) Below I have outlined a much more detailed planning process and ways that I could have kept my project on track to meet the requirements

Planning -

Before even starting to code, I need to step back and think about what exactly I'm trying to accomplish. The main components of Tic-Tac-Toe are:

1) Create 2 players and a game Board
2) Logic to switch turns/not click the same square twice
3) Logic to loop through possible wins and declare a winner (or tie)
4) Create a New Game button that clears the board and allows a second game to start
5) Keep track of the score for each individual user
6) Sign Up/Sign In/Change Pass/Sign Out buttons and hide/show/clear functionality

While I did create a wire-frame and user stories, they were not as clear or broken down as much as they should have been in order to be useful to me during the process. I did not reference either of those two planning tools while working on my project, which seems like a waste since it may have helped me break the project down into manageable chunks or at least could have directed me along, especially when I got stuck. In the future, I will use these tools throughout the entire project to keep myself on track and not falling down rabbit holes. I will also use project management tools, like Trello, which I also did not use for this assignment.

Writing Consistent Code -

To be perfectly honest, I had no idea what I was doing during this project. I'm sure a good chunk of the class was right there with me, but I was lost and just trying to find my way back. My code was inconsistent throughout, I very readily admit that. I wacthed a lot of videos, looked at a lot of examples, and tried to pull information from many different sources. I was just trying to interpret what I could on my JS reading level - and it showed. Looking at what I knew while trying to create that project, I don't think my code was going to be anything but long and wet and awful to read.

However, looking back on the project and after what I've learned since, here are some ideas on code 'consistency' that would help me in the future for other projects like this:

Keep consistent style and naming conventions - I was pulling ideas from many different places and there was NO consistency from section to section. This made it difficult to read and to go back and figure out where my problems were.

Refactor all the code if you find a better way to write - I did not go back and fix my code to match as I moved along. If I found something better, I just incorporated it and kept going. If it worked, I didn't want to break it, so I left it as is - no matter how un-pretty it was.

Separate your code into smaller chunks - This was part of the project and the teachers encouraged us to do this. This was eventually going to be soomething I'd do to make it pretty AFTER I hit requirements. So most of my code was in one large file. It made finding bugs and fixing problems difficult. Splitting it up may have seemed scary in the moment but would probably have saved me many headaches.

Refactoring Code -

I did not do this. I didn't even get to this part. What I should have done was refactor as I went - as I found new, better ways to do something, changing all of my code to reflect the changes so it matched from section to section. This would have helped find issues and keep it organized. Looking back, I thought refactoring meant changing my code in big ways and would be done once, as a way to 'clean it up' afterwards. I've learned that refactoring should be done as a series of small changes, which makes the existing code slightly better while still leaving the program in working order.

Strategies to avoid bugs/quality control -

- Avoid fancy code
- Use available libraries/don't reinvent the wheel
- Learn how to refactor to make the code more readable without changing the behavior
- Don't do anything too quickly. Taking a little time up front to do things right, to check what you've done, and to think about what you're doing.
- Get somebody else to look at the code

My un-met Requirements:

User-facing bugs - I had many bugs in my code. Mostly because the game itself didn't work and I couldn't get my logic to run correctly. I didn't take the time I should have to plan what needed to happen, step-by-step, I just sort of jumped in and hoped for the best. I'd like to beleive that when I go back and re-work this project for my portfolio, I'll be able to have a better game-plan in mind for fixing the bugs in my code. The first step will be to go after consistency and breaking things into smaller chunks. My game logic was one long, tangled ball of crazy. It's no wonder that there were bugs. Breaking each part down and isolating it, instead of things being nested inside other things, etc will make it easier to figure out where the issues lay.

Click same box twice a player will win - This goes back to my broken logic. When I submitted the project, this had been the piece I had been working on. I beleive the issue lies in the GameWinner loop I wrote to determine a winner. After a certain number of moves, the logic should start trying to figure out of there was a winner. The logic I wrote got stuck on the number of moves rather than comparing what was in each cell. I believe with a little re-working, I will be able to fix that loop and get the winner function up and running.

Play Again button (can't click cells) - My logic also got stuck on the "New Game" functionality. The board cleared but a second game never started. The "New Game" button didn't start a new game, just stopped the ability to play. I need to re-work my logic to actually say the game has ended which will allow the boxes to be clicked for a second game. This will happen AFTER I fix my Game Winner logic.

Game logic not consistent (a player will win and the game will not end and on the next turn the other player will be given the win) - This goes back to my Game Winner logic which does not work. I need to fix my Game Winner function to loop correctly and specify a winner. Towards the end, I was trying everything I could find to get it to work. There was no consistency - I just wanted it to run correctly (which was the wrong way to look at the problem.)

Synopsis:

I had MANY issues with my Tic-Tac-Toe project, most of which started with my lack of planning which led into a lack of consistency. By mapping out a strong and detailed step-by-step plan and breaking my logic into small chunks, I think I will be able to have my game up and running for my portfolio.
