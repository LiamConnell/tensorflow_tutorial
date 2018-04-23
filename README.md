# tensorflow_tutorial

This is a series of notebooks that I used when giving some somewhat impromptu presentations to my team at Auth0. 

It is intended as an introduction to Tensorflow and the essential mathematical concepts that work behind neural networks and gradient descent.

I also tried to explain some basic concepts using base tensorflow before showing the common ways to implement them. For instance, I implement gradient descent first using basic tensorflow before using the `tf.train.*` implementation. This allows the student to see under the hood before using convenient functions, and is important when moving from boilerplate implementations to more complicated deep learning structures. 

Some key takaways are:
  * The modules of a typical supervized learning problem in Tensorflow are Model (prediction), Loss, Optimize, and Evaluate
  * The relation between a forward feed network and a linear model. What is the difference? What takes us from "linear regression" to "universal approximator"?
  * Basic ideas in organizing tensorflow projects (This section is a bit outdated according to my current methodology...)
  
Like slides of any presentation, the information here might be incomplete. There are scattered Spanish phrases and jokes (I work in Buenos Aires). If this way of teaching useful or you have some followup questions let me know. 
