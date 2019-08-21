# immortalsARSW
---
# part 1 - before finishing class

* ***1.***   Check the operation of the program and run it. While this occurs, run jVisualVM and check the CPU consumption of the corresponding process. Why is this consumption? Which is the responsible class? 


  ![](img/cpuConsume.PNG)
  
  _This is because the class producer makes his execution every 5 seconds and it needs to calculate the new random and added in to the      queue while the consumer is asking faster than it takes the producer to make his execution._
  #
  

* ***2.***  Make the necessary adjustments so that the solution uses the CPU more efficiently, taking into account that - for now - production is slow and consumption is fast. Verify with JVisualVM that the CPU consumption is reduced.





---


 
 
