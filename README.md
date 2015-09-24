![alt tag](wireframe-screenshot.png)

- This is a basic visual guide for what the app should sorta look like. It will be similar to the twitter client and Instagram apps .
- A user needs to login with Tumblr OAuth. When a user logs in we will make an API request for their likes.
- Then we can use the tags as the searchTerms to use in the mobile/search endpoint. 
- When we get data back we need to filter down to posts that are of type text. (we can probably make a bonus for other types)
- We should have all data needed for the user status on that post (has the user liked/reblogged already, but it shouldn't be)
- Finally we put the post on the tableView and save to Parse.

- The rest of the screens are basically the same as the twitter client (login, new post, and post detail).

- Because we dont have a sophisticated server we have to handle stuff on the client (the fetching of likes and piping it to search).
- When another user logs in they will see all the posts already :) .
- Data is pulled from Parse and shown when you navigate to the tableView. 
- We can store teh currentUser on the app.


