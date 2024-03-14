# CS321_Midterm - Blogging Site
**By Orlando Quintana**

This is a blogging site that would allow the author to grow his brand. End-users would also be able to interact with the content uploaded and share them with other peers across the internet.

## - Architecture Overview -
This website will utilize Flask to handle HTTP requests, giving the site more functionality and ease for the end-user.

#### Routes:
* `GET /home`: Renders the homepage.
- `GET /blog`: Shows a specific blog post through an ID.
- `POST /blog/new`: Allows the author and registered users to upload blogs.
- `POST /blog/:id/comment/new`: Allows users to leave comments on a blog post.
- `GET /login`: Prompt users to log in their credentials.
- `POST /login`: Handles user authentication.
- `GET /register`: Help new users register new accounts.
- `POST /register`: Process user registration.

User email subscriptions would also be accomplished through back-end means such as Heroku. Blog posts would also be stored through this means as well.

Social media APIs can also be utilized to allow users to share and repost certain blogs on other platforms.

### Database Schema
- **Users**: Stores information about registered users.
- **BlogPosts**: Contains the main content of blog posts.
- **Comments**: Stores comments left by users on blog posts.

## Conclusion
This list of requirements unsures a better user experience. Through the utilization of Flask, HTML/CSS/Javascript, and SQLite, the web application can deliver a proper experience.