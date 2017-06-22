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