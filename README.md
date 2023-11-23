# FinalProject

This is my final project for my online CSC 150 class.
I am currently writting this at the beginning and I am very excited to start!
I plan on using this as my diary so to speak and will post updates
of my progress here!

11/7/2023
I have decided that I will try my hand at coding Connect 4! I played online
against a bot to kind of get a feel for how it should play and what the board
size needed to be. the 'original' is 6 rows by 7 columns so I will start with that
but it would be fun to ask the user what dimension of board they would like to play.
Im going to start with the basics first.

11/8/2023
My brain has already melted about 3 times so far. I got the board to print how I wanted it 
Letters on the left side in and numbers at the top. I figured the letters on the left would be
a good visual representation for the user even though Im going to only have them imput the
column number and then have their piece 'fall' to the bottom like normal connect 4. I expect the
'falling' part to be the most difficult.

11/16/2023
It has been a while since I posted anything. I have been a groomsmen at a wedding from wed-sun of
last week and it took me sometime of working hard to get where I am. SO status update. I think
I am right on schedule. I have a function for initializing the board and one for printing it. 
In my main I have a print statement that states Lets Connect 4! My next problem is going to be 
trying to sort out my win condition which I am absolutely going to make at least 1 function out of
and also I need to start figuring out how I am going to tackle the gravity thing. But so far my board
prints and I am very happy about that!

11/19/2023
I feel like melty brain is just going to be my life from now on as a programmer. So last I left off I
was able to get the board to print along with a little printf statement that I mentioned last time. So
basically where I am at now is I have an idea of how I need to structure the checkwin func but I need to
be able to input and actually win. so I made another print statement prompting the user to pick
a column and have their piece 'drop' down (still working on the dropping part). I then put the scanf in an
if statement which im sure we went over in class but I had to do some syntax research in order to fully 
understand it and my god is it useful! So basically if the user doesnt input into the appropriate column 
it will spit out an error and have them retry. An interesting thing I discovered however is that if the user
inputs a letter all Hell breaks loose. So from the research I have been doing it seems I need to clear the 
input buffer. So I will be figuring this out while I also try to figure out gravity and my checkwin conditions

11/22/2023
I think I have a pretty solid checkwin function made. So far the game only inputs on 1 row but it switches 
between X and O well. It also over rides what ever input is already there so I need to work on that as 
well but if there are 4 in a straight line it outputs Congrats Player (who ever won) You Win! So thats
a plus. Now I need to figure out how to get the 'gravity' to work so I can stack pieces and make sure 
winning diagonally and vertically also work. I plan on working on that today I will update you If I get 
it to work. Honestly I'm not too sure what else there is to do after that. Other than debugging im sure. 
The debugging part is where I'm going to work on the whole Hell break loose when a letter is input thing.


