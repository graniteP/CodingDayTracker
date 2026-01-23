# CodingDayTracker
I'm going to document the features I implement on a semi-daily schedule. Only one feature at a time (I don't have the patience for a full game :()

Day 0: January 21, 2026 
Today's Progress: Set up my tracking document in Github. 

Thoughts: Github is very interesting. It hosts my documents on their servers, and can be viewed by anyone. The gist of what I've learned so far, is that it's best practice to make changes in a branch (not main) via commits, then merge the changes I made in the branch to main via a pull request.

Link to work:

Day 1: January 22, 2026 
Today's Progress: Made a vec2 class. Represents the x and y of a point in a 2d space. 
  I made a character follow my cursor, by making a vec2 class to store the x and y of a few things. Then I made an object to store the cursor location, and the character location, I then subtracted the two x's and y's to get the magnitude(length). And to get amount to add and subtract each frame, and to make sure it would follow the cursor, I divided the difference by the magnitude to get a length of 1 (normalization), then added that vx and vy to x and y of the character.
  
Thoughts: The implementation was interesting. It was the first time I used the operator keyword, making it so that we could perform operations on our very own objects. In the past, I've made classes to represent primarily characters, enemies, bullets etc, but now I can use the operator keyword, assign what goes on the left and right side of the expression, and manipulate my very own datatypes. I think of objects as cookies made from the cookie cutter that determines the shape (class), and now with this operator stuff we can now determine how our cookies interact with the other cookies. One thing to note, is that when creating a special constructor, the default is no longer called, and you can't do something like vec2 v;, cause that's calling the default constructor. So you can do vec2() = default; or something like this, which is basically saying that if vec2 is instantiated without any params, use the default constructor. 

Link to work:

Day 0: January 23, 2026 
Goal - Make a 2d cube rotate.
Today's Progress: 

Thoughts: 

Link to work:
