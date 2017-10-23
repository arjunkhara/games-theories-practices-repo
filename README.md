# my-first-repo
My Project Repository

This is my first games programming project, likely in Javascript or Unreal Engine, and this is some <code>code for the project</code> As this course progresses so too I am hoping will my ability to programme a really cool game. I'm currently thinking along the lines of a narrative that allows for several digressions from the main story arc, with user-driven control over story setting and narrative. The primary aim of this game will likely marry digital literacy with the humanities to establish a bridge or confluence of two worlds — a principle that has worked extremely well in the past with respect to game development. I am also aspiring to create a game that can be played offline if, for no other reason, than to increase the likelihood of actual human interaction that will reflect computer-driven engagement. In this regard, I am examining how offline and traditional games are created (Monopoly, Cops and Robbers, Cricket etc.) to understand the deeper fundamentals of gameplay and game design. Ultimately, the practice of game-development is rooted in the principles of consumer engagement and consumer entertainment, and this I am hoping will serve as a mantra — to convert passive recipients of data, into active participants of information.


---10 October 2017---
Following with this thread I now have a clearer idea of what type of game I would like to build. I am interested in building one of two games (unless time and resources permit, in which case I will builf both games). The first and more ambitious game will be a maze-like scenario built with jQuery and JavaScript. The game would involve a degree of strategy and planning — for example can a player move from one side of the maze to the other in the shortest possbile steps. An alternative scenario to this would be to create a bricks-like game where bricks from the top keep falling and moving tray / paddle at the bottom is controlled by the player to shoot left and right in order to catch the bricks and tip them into a safety bin before attempting to catch the next falling one. Variances in level design would include bricks falling faster and the safety bin getting smaller. The safety bin might also move position as the game progresses. I believe the simplicity of the game (and complexity of the code in JS / jQuery) might make this an idea console or mobile game and I will be shortly starting to build this out and sandbox it in a web browser. My index.html file here on Github will hold the commits for the code, while this readme file will continue to hold the analysis, plans, insights, learnings, and execution strategies.


So with basic setup getting underway I decided to do some organising for the team that will do this project. Some basic roles that I researched from a few games studios are: art director; graphics programmer; graphic designer; concept lead; project lead; animator; audio producer; level editor; devOps engineer. Of course having all of these positions in a small project is not feasible but nonetheless the identification of roles is the main thrust when co-ordinating a team with both designated and shared responsibilities. So while individuals for each role is out of the question, the organisation of a team of 3 to 4 will require that each team member assume a few roles from this list. For example the lead animator can also take on the responsibilities of art director and graphic designer. Likewise, the concept lead can assume the roles of project lead and devOps manager. I am starting to see that when producing a game, it is not just the hardware and software that come into play but the management of groups of professionals — each an expert at his/her job — to form a cohesive and well-functioning unit that collectively commits to the project's overall integrity. The whole is greater than the sum of its parts. I will be doing some research vis-a-vis building out the game into LEAN, AGILE, and DevOps. I feel this will be crucial to getting a more realistic feel for working in an actual games studio when the time comes.


Following up on the management aspect, I've decided to create a demo file (mobile format). I figured that when the game is produced, it will be useful to have a pre-existing framework through which to demo this to potential users. Since the index.html file contains the code of the game in HTML / JavaScript for primarily desktop consumption, I anticipate the number of users with mobile devices to access this game will be significant. I have therefore created a prototype mobile placeholder in the event I need to quickly demo this game. The name of the file is: game-demo-mobile.html. Since I currently lack any useable code at the moment, I have done a mock-up of an app-like system. I may or may not use this file at the end, but I feel it is beneficial to have it, if not for anything else than to become even more familiar and confident using Github respositories to hold multiple mini projects.


Today I managed to do something that seemed extremely difficult and dangerous for my files and content - I learned how to change my repo name. The process, as it turns out a lot when learning a new skill, was straightforward and logical. I simply clicked the settings button under the repo name. A tab opened with the option to rename the repo, together with a list of checkboxes to maintain and update all links. It worked perfectly and suddenly I am feeling a lot more confident using Github on a more regular basis. It's good to experiment at times and learning comes with risk. This exact same principle will be of immense use when designing my game. Feels good to learn and make progress.


Today Pedro (Andy Thomason's T.A.) introduced the concepts of coding within the frameworks of Unity and Unreal Engine 4. There was also an introduction to Blueprints. The session was incredibly useful, especially given its relevance to the game being designed. With greater knowledge of these platforms comes more ideas and — more importantly — greater ability to execute the idea. Therefore the ambition to create and design a more interesting game rises. Unity is great for smaller games while Unreal Engine is more towards console and PC. However the choice is determined not so much by the technology but by the ambition of the game and the technology stack the game creator is most comfortable with. The game concept comes first and the technology stack will come second. So in the case of the Snake Game, the concept of the growing snake (++ boxes for each stage of growth) it is important to understand how the gameplay will develop before choosing the programming language. That makes perfect sense from a games developer point of view.


The basic setup of snake is coming together in my index.html file. Using jQuery and HTML5 canvas I have setup the basic game structure and playground (canvas) within which the game will be played. In the next stage I will setup the necessary function to make the snake's body and its movement along the direction keypad. The variables and basic attributes of each have been defined but have not been linked by any functions as yet. I am assuming I will have to write a function to make these discrete components come together. To understand functions better I am consulting the book 'You Don't Know JS' by Kyle Simpson. Once I understand the concept better I will write up the function — and hopefully it works the first time.


Committing from this point on will be done via Sourcetree (whenever feasible and efficient). It was explained that while working on JavaScript and HTML-based games, the outdated (but still works) mode would be to test the game on an editor, like Atom, ensure everything works and then copy-paste the source code to the index.html file here on Github. However, when compiling gameplay on Unity or Unreal, every variable change will need to be recorded, which makes this method of commits obsolete and inefficient. Sourcetree solves this problem by running/recording these changes in the background so that there is commit entry at both ends — development and respository. This is extremely useful and I understand now the value of this practice and method within gaming studios and high-level co-ordination projects.


How to add a local repository to Sourcetree (Pedro's Recommendation to Research)
The process of adding a local repository to Sourcetree on Mac, as it turned out, was relatively simple, and after some searching online and experimenting with the app, I figured out how to do it. The steps are as follows:
1. Open Finder and locate the folder that you want to add
2. Open Sourcetree and locate the Bookmarks Window
3. Drag and drop the folder into Sourcetree's Bookmarks Window
4. On the pop-up prompt dialog box click 'Add Repository'
5. Navigate to the tab which says 'Add Working Copy'
6. Your local repository will be available
The process is useful when moving a repository from a local machine to Github (Sourcetree interface). However, it is better to create the repository (where feasible) from scratch on Github via Sourcetree to avoid any prior versions that may have been altered on the local machine but have not yet been uploaded. In this case, when a local repository is added to Sourcetree, Sourcetree will only receive the most up-to-date folder contents from the local machine.


---17-OCTOBER-2017---
Today, through a lot of Googling and online tutorials I have managed to write the first three functions for my snake game. I am trying to learn coding by building a game and this requires more patience and thoroughness than anticipated. I have referred to numerous books and online tutorials, and have found a useful library to refer to (NOT TO COPY, STRICTLY TO REFER TO FOR ACADEMIC AND PERSONAL INTEGRITY) on Codepen. The URL is here: https://codepen.io/tag/snake/ Studying these various code bases has given me some guidance on writing my game in Javascript. I have a few more functions to go before I am ready to test. I have learned the importance of IMBRICATING in coding. By arranging by code, management, and learning development in an overlapping context (or imbricating) I am able to draw on multiple understandings of all three areas. This cross-disciplinary approach to coding feels more like the real world systems employed in games studios and I believe this approach to be an important quality for games studio recruitment and career success.

Also today was my first major error in the code base, and also my first genuine appreciation of commits. To quote Andy Thomason: don't break the build. Unfortunately, I broke the build. I did not keep track of my variable names. For consistency-sake I began each variable name with 'my'. However, I did not follow through on this self-imposed rule and ended up leaving this prefix out of the variable name in later instances. When I ran the test, whatever was working stopped and I was faced with an empty canvas. I first spent a few hours looking through the codebase to see what the error was, then remembered this repo contained the most recent rollback before the changes. I copied out the old code (which worked) and thankfully my progress to-date was saved. The importance of committing cannot be overstated. I should have documented this sooner when the error occurred earlier today. I will be taking commits a lot more seriously, since today's event and corresponding prior commits saved me from going back to square one and starting all over again. Thank you Andy and Pedro for teaching us repositories, commits, Github and Sourcetree. Whew!


The build broke again today and the game failed to initialise properly. The error is suspected to be in a few areas, namely the functions I learned over the last few days, and the way I have been building them. I also think the errors in my variable naming convention are carrying through this and recent builds. Basically, the script generates the snake and the snake can be seen to move across the screen from left to right but as one discrete unit and cannot be controlled. Keyboard commands are not working nor are mouse interactions. The one good thing that has come out of all of this is the idea for a new speed-controlled game of snake in which the snake moves across the canvas and at random varying speeds and lengths. The objective of the game is to click on the snake and register the hit. Depending on the speed and length of the snake the more accurate the hit the higher the points. But before I go into this concept the initital build needs fixing. I will be rolling back to the build from yesterday, which up to that point was working fine.


Today Andy taught us about how to download / clone a project from his GitHub repository and fork it to our repositories for analysis. We were also exposed to the GitHub command line, which was useful. Andy made a point not to commit an Library and/or Temp folders from Unity to GitHub, and to only commit assets. In addition those looking at your GitHub profile for progress will not take kindly to unnecessary bloat files. Andy also showed us a Poing demo, which is the GitHub repository I have downloaded / cloned to my local machine. GitHub command line has a very easy method to pull / push / commit. On GitHub commandline type: git pull --rebase. Remember that when working with multiple people / teams on the same project, always pull before pushing. However, check with the house rules. Rebase undoes your changes, works on other people's changes, then reworks on your changes. When using version control in most games studio, Perforce will be the tool of choice. Although most new studios use Git and GitHub to host their projects. Since everything is in a public resource, it makes it easier to fit into the company culture for working from home, for example.


Based on the need to keep consistency across team usage for GitHub, I have learned how to rename existing files in GitHub. The file that contained my code for the snake game was named index.html. It has now been renamed snakeJStrial.html. Naming convention is important for keeping not only consistency but clarity in version control. The practice of committing requires more than just continuously saving and monitoring your changes; it is also a collaborative tool, which means other team members need to know what I am working on. Adding to this, Andy covered the basics of C# which was very handy. I am documenting some of the code explanations here and then will try to extrapolate these to JavaScript when I attempt to build the Pong game in JS. One great way to understand the code and its execution and changes, use 'public' namespace to show these updates in real time as gameplay progresses. It is also important to understand 'vector' namespace since this controls the vector (speed, position, direction) which in 3D space would also include movement along the z-axis in 3D space. While C# is very similiar to C++, as I progress with programming, it is good to develop C++ since "C# is a type of halfway house between JavaScript and the high-end C++". (Andy Thomason). Note also that with C# everything is done in the class.


My team for introduction to programming has been created and each of the four members has been assigned a duty roster and task to accomplish. The game concept we have in mind is a space invaders and rhythm hybrid, where ships still attack yours but in formations that come about from identifiable / predictable music patterns. It is important for the team to balance ambition with resources - in our case time. I have therefore setup a kanban board on Trello and we are aiming for an ambition level that matches what we can realistically accomplish by week 8. The team has also setup a joint commits repository with collaborators. The URL is /CADS-ProjectTeam (the name being the first initials of the team members arranged in an acronym that is easy to pronounce and remember, and more importantly to find on GitHub. We have decided to use Unity as our games development environment. I have also created a backup game on JavaScript, just in case this one fails, and will be maintaining this game on the side as well.


Through the introduction of Kanban boards to the games project I am beginning to understand the value of team projects and accountability. With the Kanban board setup I am now beginning to understand the need for project resource allocation and committing. A Kanban board not only provides a visual display of the tasks that need doing, but also provides a useful prediction of the project's outcome, especially nearer to the project's deadline. With the ability to assign each person's profile to a task on Trello, the Kanban board also affords a high degree of accountability for the project. Game-design and game building has much more to it than simply typing code and clicking buttons. The idea of narrative, concept development, story and mood boarding, and the all-integral aspect of teamwork would be at worst absent, at best sidelined without an effective team management system. The Kanban board also shows the degrees of engagement and rate of progress for each team member as the project proceeds. I will be using this system to experiment when building my side project game of pong to see if Kanban or similar management tools can work for one person (eg a freelancer or a researcher). I am quite confident, given what I've learned, that there are applications to single-person / individual game developers.

Today I was able to write my first simple program in C#. I am learning from a book called 'Learn C# in One Day and Learn it Well' by Jamie Chan. Based on the explanations in the book and in the C# tutorials I am attending online, I was able to make the compiler spit out the words 'Welcome to Space Invaders'. I have shared this codebase with my team on our team respository, and have placed the code snippet in here as well.<br/>
/---BEGIN CODE---/ <br/>
`using System; //using is a directive that tells the compiler the program is using a namespace called system`<br/>
`using Systems.Collections.Generic;`<br/>
`using System.Ling;`<br/>
`using System.Text;`<br/>
`using System.Threading.Tasks;`<br/>
`namespace WelcomeGreeting {`<br/>
`class Program{`<br/>
`static void Main(string[] args){`<br/>
`Console.WriteLine("Welcome to Space Invaders Meets Bit Runner");`<br/>
`Console.Read();`<br/>
`}`<br/>
`}`<br/>
`}`<br/>
/---END CODE---/<br/>
I am also learning how to markup my GitHub repo entries through HTML and basic GitHub text syntax, which I will be sharing with my team on our repo.


This cheatsheet published by GitHub is extremely useful for marking up and marking down code and comments to share with teams. There are other sources as well but I have found that marking up code in this manner (as prescribed by GitHub) is almost an industry-standard for games studio. I would like to get used to this method and process as quickly as possible. Here is the URL: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
