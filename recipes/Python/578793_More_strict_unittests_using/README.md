## More strict unittests using a validator 
Originally published: 2013-12-20 10:35:15 
Last updated: 2014-03-01 12:37:47 
Author: Thomas Lehmann 
 
The main point is that **there was no binding between a unit tests and the concrete class**. It did happend often that you are indirectly testing a class using it also the concrete test class has missed some concrete test methods. I found this fact sometimes very irritating seeing 100% coverage.