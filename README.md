Project Link : https://youtu.be/yvBZxxpnUk0




1. If a user can create and edit stages for a particular board. For example instead of Open> InProgress > Done if they 
want the stages of their task to be Read > Working > Reviewing > Completed.
 
Ans.   Create four lists on a board: "Read", "Work," "Review," and "Completed."
       As we have implemented the drag and drop functionality we can move the tasks from Read->Work->Review -> Completed.
       API endpoints would be look like this : POST /1/cards
       If you are moving to a different list:  PUT /1/cards/{id}/idList







....................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................
2. If Users can comment on tasks
Ans. To add a comment we can make a post request for a specific card and that can be associated and later can be 
     retrieved. But we have to implement authentication as well for the users to be authorised. 
     API endpoints would look like this: Create a comment : POST /1/cards/{id}/actions/comments
     Get Comments for a Card:   GET /1/cards/{id}/actions. 


.......................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................



3. How will you do Error handling ?

Ans. For most of the cases I run certain test cases for error handling that where can my program generates a wrong output or server fails
     then it gives me clarity otherwise I use Jest for testing out my codebase since it's document is well maintained thus
     it's easy to use and handle
 
 
