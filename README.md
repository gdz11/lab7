# Lab 7

1. Create post-list component for displaying posts. Post has following fields: id, userid, tite, body. Only title and body are displayed to user.  

2. Create service for loading post data from https://jsonplaceholder.typicode.com/posts/ using angular http client.  

3. Create post-commments component for displaying post's comments list. Comment has following fields: id, postId, name, email, body. Only name, email and body are displayed to user.  

4. Create service for loading comments using http client from  https://jsonplaceholder.typicode.com/posts/{postId}/comments, where {postId} is id of the post selected by user.  

5. When user selects post from the list by clicking on it, selected post should be highlighted with different color (background). Also comments of the selected post should be loaded into comments list component.  
