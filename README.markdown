I solved this one right after solving problem 13 (Chess Move Validator) which I found much more difficult. For that problem, I really tried to come up with a nice and extensible design (which I'll share as soon as the Mendicant University exam deadline has passed). 

So after spending a few walks thinking this problem over, I decided to attack it in a completely different way: 

- This puzzle naturallly lends itself to visualization, so instead of doing TDD I'll simply print out the cave for each iteration and verify my algorithm manually

- The model of the problem domain does not have to be more complicated than the rendering of the cave itself: A two dimentional array of tiles. Each tile can be air (" "), rock ("#") or water ("~")

If this was a real project, I would definitely have created a handful of classes to lump together related functionality. However, before starting I knew exactly how I wanted to implement this, so I wrote most of the implementation without even running it first. There is not a lot of code here so it wouldn't take future me (or any other reader) many minutes to figure out what is going on even though it is pretty quick'n'dirty. 
