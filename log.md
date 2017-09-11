# 100 Days Of Code - Log

### Day 0: May 30, 2017 

**Today's Progress**: Did some basic algorythm tasks from FreeCodeCamp. Also one 8kata from codewars.

### Day 1: May 31, 2017 

**Today's Progress**: Built a tribute page as a challenge in FCC.

**Thoughts**: 

**Link(s) to work**: https://codepen.io/volshibenik/pen/ybmXjb

### Day 2: June 1, Thursday

**Today's Progress**: Created a repo FreeCodeCamp where i will stack my solutions for their tasks. Also, solved some of them!

**Thoughts** 

**Link(s) to work**: https://github.com/volshibenik/FreeCodeCamp

### Day 3: June 2, Friday

**Today's Progress**: Learned about Date object here -> learn.javascript.ru and completed after chapter tasks. Also, began to watch this amazing guy on Youtube -> https://www.youtube.com/watch?v=1DMolJ2FrNY

**Thoughts** 

**Link(s) to work**: https://github.com/volshibenik/FreeCodeCamp/blob/master/date_tasks.html

### Day 4: June 3, Sat

**Today's Progress**: Sorted Union and HTML entites challenges from FCC

**Thoughts** Array.reduce, damn it. Watched 2 times funfunfunction video, completed it's code. I guess now i'm closer to mastering it.

**Link(s) to work**:https://github.com/volshibenik/FreeCodeCamp/blob/master/intermediate/9.sortedUnion.js

**Important** Learned how to use string.replace with function. Found info at W3C school -> cool example  ))
            var res = str.replace(/blue|house|car/gi, function myFunction(x){return x.toUpperCase();});
            
### Day 5: June 4, Sat

**Today's Progress**: completed Sum All Primes, Smallest Common Multiple and couple other challenges from FCC

**Thoughts** 

**Link(s) to work**:https://github.com/volshibenik/FreeCodeCamp/blob/master/intermediate/

### Day 6: June 5, Mon

**Today's Progress**: today i was doing skipped challenge with regular expression to make string spinal case. After spending several hours learning regex i finally did it. Also, finished all remaining intermediate tasks

**Thoughts** 

**Link(s) to work**: https://github.com/volshibenik/FreeCodeCamp/blob/master/intermediate/11.spinalTapCase.js

### Day 7: June 6, Tue

**Today's Progress**: not much today, just watched Lea Verou's talk about regEx and did js part of drumKit from #javascript30

**Thoughts** 

**Link(s) to work**: https://github.com/volshibenik/javascript30/tree/master/01%20-%20JavaScript%20Drum%20Kit


### Day 8: June 7, Wed

**Today's Progress**: did some katas from codewars, got first rank-up to 7kyu

**Thoughts** 

**Link(s) to work**:  


### Day 9: June 8, Thu

**Today's Progress**: Also some katas from codewars, started to make portfolio

**Thoughts** did this equal sides of an array kata6 and there was awful solution with .reduce inside for cycle marked as best practices)) So i did performance tests to find out that my solution is actually 10 times faster! Gotcha!

**Link(s) to work**:  

### Day 10: June 9, Fri

**Today's Progress**: Worked with portfolio challenge 

**Thoughts**

**Link(s) to work**:  

### Day 11: June 10, Sat

**Today's Progress**: Some more katas from codewars, one particularly hard, despite it's just rank 6,  'Help Mrs. Jefferson'

**Thoughts** 

**Link(s) to work**:  https://github.com/volshibenik/codewars/blob/master/(6)helpMrsJefferson.js

### Day 12: June 11, Sun

**Today's Progress**: Missed a day((

### Still Day 12: June 12, Mon

**Today's Progress**: worked on FreeCodeCamp portfolio project

**Thoughts** 

### Day 13: June 13, Tue

**Today's Progress**: Finally finished first version of my portfolio page! 

**Thoughts** 

**Link(s) to work**:  https://codepen.io/volshibenik/pen/pwbXOr


### Day 14: June 14, Wed

**Today's Progress**: Started to make random quote machine challenge

**Thoughts** 

### Day 15: June 15, Thu

**Today's Progress**: Missed a day

**Thoughts** 

### Day 15: June 16, Fri

**Today's Progress**: Solved a codewars kata 'Multi-tap Keypad' and a couple level 7 simple katas. 

**Thoughts** 

### Day 16: June 17, Sat
### Day 16: June 18, Sun

Missed these two days((

### Day 16: June 19, Mon

**Today's Progress**: Almost finished Random quote machine challenge. 

**Thoughts** Got struck really hard with twitter button. Couldn't imagine it would be that hard to insert div content there

### Day 17: June 20, Tue

**Today's Progress**: Finished Random quote machine challenge. Yay!! 

**Thoughts** Found this jQuery solution for twitter button and remake it to native JS
http://jsfiddle.net/chris27/DQw5b/4/ 

### Day 18: June 21, Wed

**Today's Progress**: Started Weathe app, spent almost entire day trying to overcome an error: No 'Access-Control-Allow-Origin' header is present, that pops when i try to load JSON from weather API. Found out that this error happens when script in your site tries to load resource from other origin and browser prevents for with security reasons. And i read about the CORS solution, which requires to be implemented on both your and source site (if i understood right). To be continued...


### Day 19: June 22, Thu

**Today's Progress**: Today i continued to search for a method to load API. SO, except for CORS there is a hack that everyone use and it's usage of JSONP instead of JSON. It's not very secure, but for sake of this exercise i will gladly use it. IT WORKS! So, all i had to do is add query string 'callback=?' to the end of my API url. Now JSON loads and i am building interface of the app.

### Day 20: June 23, Fri

**Today's Progress**: Spent some time to understand why my navigator.geolocation.getCurrentPosition(success, error, options) can't change my external variables and found answer at stackoverflow that this is caused by AJAX async behaviour. So i was trying to access vars before navigator function could change them;

### Day 21: June 25, Sun

**Today's Progress**: Was going through mozilla MDN lesson and example of JSON usage. https://developer.mozilla.org/en/docs/Learn/JavaScript/Objects/JSON
After learning it did similar stuff in my weather app.


########################


### Day 1: July 17, Mon

**Today's Progress**: Lost my win streak month ago and after that was doing things here and there, but not constantly. So i decided to start over. Today will be day1 N2)). I already finished my weather app and today doing to finish wiki app, so let's say it will be my daily progress.

### Day 2: July 18, Tue

**Today's Progress**: Started doing my twitch challenge, took me a while to understand, how to get JSON from this workaround site(to avoid creating twitch account), but finally i get my JSON: https://wind-bow.glitch.me/twitch-api/channels/thijshs

### Day 3: July 19, Wed

**Today's Progress**: Continue doing twitch, found a pure JS JSONp implementation on YouMightNotNeedJQuery, which works fine for twitch, but strangely doesn't for weather app.

### Day 4: July 20, Thu

**Today's Progress**: Finished doing JS for twitch challenge

### Day 5: July 21, Fri

**Today's Progress**: Finished twitch challenge, did tabs with pure CSS radio selectors, not sure if it's good practice, but at least i remembered how it's done!

### Day 5: July 22, Sat

**Today's Progress**: Started doing JS calculator challenge.


### Day 6: July 24, Mon

**Today's Progress**: Decided to do it more windows-like, with additional functions like repeat last op when press equal etc.


### Day 7: July 26, Wed

**Today's Progress**: Doing JS part, i'm adding different classes to output to memorise what button was clicked last
 

### Day 8: July 27, Thu

**Today's Progress**: Wrote common functions "Math" and "Type" for math operators and numbers, now certain number or operation just passes argument its argument


### Day 9: July 30, Sun

**Today's Progress**: Swithed a little to CSS part, decided to make little blobs(qty = num) around each number that will light when you click it.


### Day 10: July 31, Mon

**Today's Progress**: Also did some animation to math buttons, like scale for multiply, shrink for minus etc


### Day 11: August 1, Tue

**Today's Progress**: Added SVG icons to math buttons, it broke my layout(probably bc i don't know how to SVG). Will switch to Flexbox.


### Day 12: August 2, Wed

**Today's Progress**: Discovered some bugs with JS math part, like possibility to type several zeros or dots in a row. 

### Day 13: August 3, Thu

**Today's Progress**: Finishing my calculator: picking colors for layout, applying flex, doing some minor stuff.


### Day 1: August 23, Wed

**Today's Progress**: Doing my tic-tac-toe project.


### Day 2: August 24, Thu

**Today's Progress**: Reading about strategies of game, making simple moves in reaction to click event

### Day 3: August 25, Fri

**Today's Progress**: Trying to hardcode best behavior with if's and it seems that it won't do any good...

### Day 4: August 26, Sat

**Today's Progress**: Ok, i'm switching to minimax algorythm, like everyone. Was reading about how to implement it. 

### Day 5: August 27, Sun

**Today's Progress**: Copied minimax function from this article https://medium.freecodecamp.org/how-to-make-your-tic-tac-toe-game-unbeatable-by-using-the-minimax-algorithm-9d690bad4b37. Currently, it finds solution on near end game board. 

### Day 6: August 28, Mon

**Today's Progress**: Finished tic-tac-toe, somehow this minimax prefers moves that guarantee win but not winning immediately, also i hardcoded some random behavior on turn 1;

### Day 7: August 29, Tue

**Today's Progress**: Started doin' Simon Game. Already have some ideas to take from 1st project from javascript30 - drum kit

### Day 8: August 30, Wed

**Today's Progress**: copied this function with clojure from stackoverflow 
function runIteration(fn, numTimes, delay) {
			var cnt = 0;
			function next() {
				fn(cnt);
				cnt++;
				if (cnt < numTimes) {
					setTimeout(next, delay);
				} else { 
					console.log('end sequence!');
					activateCubes(true); //unblock
				}
			}
			// start first iteration
			setTimeout(next, 1000);
		}		
		
	and so i have consequent clicks within an array;
	
### Day 9: August 31, Thu

**Today's Progress**: Added audio and that's it for Simon and ... for Front-end certificate tasks!! Gonna claim my certificate now!

### Day 10: Sep 1, Fri

**Today's Progress**: I have a certificate! Deciding what to do next, meanwhile started CS 50 edX course for admission to Rolling Scopes School!

### Day 11: Sep 2, Sat

**Today's Progress**: Doing Array Cardio, 4th exercise in Javascript30. Learning more about array methods, also about arrow function

**IMPORTANT STUFF** "console.table" is great! Much better than console.log, at least for arrays
