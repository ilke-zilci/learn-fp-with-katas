# Before the workshop

## Choose a language

Scala, Haskell or Clojure. Please install a full development environment and an editor of your choice, and write a failing test. The failing test makes sure that your setup works properly. Alternatively you can download a template for the language of your choice from here and run a test (it should fail). https://github.com/swkBerlin/kata-bootstraps.

Clone this repository, it includes the kata descriptions. 

## Familiarize yourself with the idea of kata
A code kata strives to provide a no time pressure practice environment in which we can stretch our abilities. The target is not to complete the exercise but to focus on learning along the way. This is the perfect time to try out different solutions, take some design idea to an extreme to see the contrast with other ideas or to learn a specific technique. If it feels too easy than we need to add some constraint, if it feels too difficult than we need to break it down.

# During the workshop 
# Find your pair
One of you in the pair should be familiar with the chosen language syntax and have the setup already. If non in the above list is familiar, pick Scala and ask the facilitator in case you are stuck.

# Choose a pair programming method
## Driver - navigator
Driver focuses on tactical concerns: handles typing, navigating between files, and basic implementation.
Navigator determines the strategy and checks for mistakes.

## Ping pong
Change roles after every failing test in the TDD cycle red-green-refactor. 

## Tips
Explain what you are doing while typing it in.  
Find a good balance between discussing alternative solutions and moving forward with the implementation. This will allow you to consider some alternatives while still exploring further challenges of the problem. 

# Choose a kata and concept to learn
## Comfort zone -> Learning zone -> Panic zone
Comfort zone: things are very familiar and we don't have to take any risks.
Learning zone: some things are unknown but just outside the secure zone
Panic zone: things are totally unknown and out of control. Any learning connected with negative emotions is memorized in a part of the human brain that we can access only in similar emotional situations. So avoid this.

In this exercise, each participant should try to find their learning zone. Try to limit the unknowns to a certain set.  i.e. If you are totally new to pair programming go for a language which looks familiar and stick with the ping pong method. If you are familiar with both FP and pair programming go for a constraint. Explore unknowns gradually. 
 
## Pick a kata
You can read the kata descriptions in this repo or follow the links below:
  * [Data munging kata](http://codekata.com/kata/kata04-data-munging/)
  * [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) - Set 20 min. to do a pen and paper session experimenting with different patterns. 


## FP Topics
  1. Essentials
  * write pure functions
  * use only immutable variables
  * higher order functions
  Some short and helpful explanations are available at this link: https://alvinalexander.com/scala/fp-book/section-functional-programming-background

  2. Enablers  
  * recursion
  * tail-recursion
  Some short and helpful explanations are available at this link: http://learnyouahaskell.com/recursion

  3. Real life
  * error handling
  * state
  * handling computations sequentially vs in parallel
  Some short and helpful explanations are available at this link: https://books.underscore.io/scala-with-cats/scala-with-cats.html

## More ways to get to learning zone
  * Provide buzzword free explanations of the concepts you know 
  * Baby steps [http://kata-log.rocks/baby-steps]
  ```javascript
       let timer = new Timer(2.minutes)
       timer.start()
       timer.on(“stop”, () => {
         let result = runTests()
         if (result.passed)
           commit()
         else
           revert()
       })
   ```
   * Mute pair programming - no talking only communication via code
 




    


 

 
