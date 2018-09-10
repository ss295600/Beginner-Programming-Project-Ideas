# Beginner Programming Project Ideas
List of programming ideas for beginners. Please read the credit file, I did not come up with any of these ideas nor their descriptions, these are all project ideas I got from websites. 

# Text Based Adventure Game 
### Suggested Language – Python, Ruby, or most any other that can easily be run and output text in a console window.
Here’s a classic throw-back project that won’t “wow” anyone, but it’s a perfect first project. Create a game/script that will ask the user for input. You can ask their name and store it in a variable to use throughout the rest of the text.

Also, add some conditional, branching events. For example, you can have a user choose to go through one of two doors and give them different events as a result. Be sure to handle for when a user gives invalid input!

# Sports Simulator Project
### Suggested Language – Python, Ruby, or most any other that can easily be run and output text in a console window.

Pick a favorite sport of yours, and create a text-based “simulator” for matches. If you have any interest in sports, this is a really great choice because you can start extremely simple and then implement more and more logic, making it more in-depth and interesting.

For example, start out by having the program output the final score of the game. Maybe your logic says the scores should be randomly generated to be between 90 and 105.

Test the output and see how it looks. Maybe you get something like the following –

Game 1: 90 to 99, Game 2: 100 to 93, Game 3: 98 to 98
Oh no, we forgot about ties! Now implement some changes to handle for ties, since a game can’t end in a tie. You can designate this game as an “Overtime” game, and randomly add 6-14 points to both sides. The output could then be –

Game 3 (OT): - 106 to 110
What if the game ends in a tie after 1 period of OT? You can add another quarter by iterating the same scores through the previous “Overtime” function!

Also, instead of randomly picking a score from 90 to 105, try modeling the scores to a normal distribution curve so that outlier scores will appear once in awhile, but most scores will remain around the average. Here’s a Stackoverflow topic that could guide you towards doing such with Ruby.

Once you feel like you have a good function created for generating realistic final scores, you could take the simulation to the next level by creating some team-specific attributes.

For example, let’s say Team 1 has an offensive rating of 100 out of 100, whereas Team 2 has an offensive rating of 80 out of  100. Factor the offensive rating into your score generator so that more times than not, Team 1 will score more points.

Then you could assign defensive ratings to teams and have that factor into the opponents scores! The possibilities are really endless at this point – you get the idea.

# Calculator App
### Suggested Language – Android, Java, or Swift.

If you want to get some practice with a simple GUI, a calculator app is a basic programming project that many people do.

You will learn how to set up a GUI and map buttons to function behind the scenes. You’ll also learn a lot about storing and modifying variables which never stops important to programmers.

Once you get the basics of the calculator down, you can try to take things to the next level by adding some “Scientific” functions, or by adding some hotkey button to the interface that save the current number to a variable that they can summon any time they press that hotkey again.

# Web Scraping
### Suggested Language – php
Web scrapers are always in demand and are frequently built in php, so this is a great and challenging project to undertake – possibly too challenging for beginners. If you don’t have a server to run php on, you can always build a web scraper in a different language to run from your local computer.

Building a web scraper requires some basic networking knowledge, and typically a lot of XML, json, or Regular Expression knowledge in order to grab the right elements of the page reliably.

Start out with really basic websites that don’t require authentication. For example, scraping the titles of all of the submissions on the front page of Hacker News and displaying them as a list. You could then scrape more data points like the number of comments, points, etc.
