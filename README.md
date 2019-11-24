This project comprises of server side programming question useful for various interview as well as project reference.



1. How to create immutable class?
Ans - 
      Below are the hard requirements of an immutable object.

			1. Make the class final
			2. make all members final, set them explicitly, in a static block, or in the constructor
			3. Make all members private
			4. No Methods that modify state
			5. Be extremely careful to limit access to mutable members(remember the field may be final but the object can still be 					 mutable. ie private final Date imStillMutable). You should make defensive copies in these cases.
					The reasoning behind making the class final is very subtle and often overlooked. If its not final people can freely 					extend your class, override public or protected behavior, add mutable properties, then supply their subclass as a 						substitute. By declaring the class final you can ensure this won't happen.
2. Difference between Callable and Runnable.
3. Difference between CountDownLatch and CyclicBarrier
