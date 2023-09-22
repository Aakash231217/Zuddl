1. **Customizing Stages for a Board**

    If a user wants to customize the stages of their task, for example, changing from "Open > InProgress > Done" to "Read > Working > Reviewing > Completed," they can do the following:
    
    - Create four lists on a board: "Read," "Work," "Review," and "Completed."
    - Utilize the implemented drag and drop functionality to move tasks from "Read" to "Work," then to "Review," and finally to "Completed."
    
    **API Endpoints:**
    
    - Create a Card:
      `POST /1/cards`
    
    - Move to a Different List:
      `PUT /1/cards/{id}/idList`

2. **Commenting on Tasks**

    Users can add comments to tasks (cards) associated with a specific card. To achieve this, the following API endpoints can be used:
    
    - Create a Comment:
      `POST /1/cards/{id}/actions/comments`
    
    - Get Comments for a Card:
      `GET /1/cards/{id}/actions`

3. **Error Handling**

    Error handling is managed by running specific test cases to identify erroneous program outputs or server failures. Additionally, Jest is utilized to comprehensively test the codebase, leveraging its well-maintained documentation and ease of use.

---

Feel free to adjust the formatting and spacing based on your preferences and the overall style of your README.md file. Markdown provides flexibility in formatting to make the content easily understandable and visually appealing.

 
 #   Z u d d l 
 
 #   Z u d d l 
 
 
