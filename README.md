# What the heck is that? 

This is for the Greasemonkey test. 
The Chai compiled with the typescript compiler. That made the Chai not work with karma-chai, which needs karma to work with Chai. Without chai, the mocha has no assert kit. One possible solution is to remove chai. Even if that's possible, it's just too much work to rewrite all the tests in one shot.  
Making a new npm package is one of the solutions, but maybe some idiot is starting to use it. That's not good because the karma itself decrapted as well.  So, to change the karma to puppeteer is the best option when I have time for it. 
But temporarily, I use this for testing as an easy option.



