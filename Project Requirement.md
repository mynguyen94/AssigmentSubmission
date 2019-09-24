<h1 align="center">
    <br>
    <br>
    Seenit  
    <br>
    <br>
</h1>

<h3 align="center">
    by
    <br>
    <br>
</h3>
<h2 align="center">
    Chaz Chang
    <br>
    Viet Dinh
    <br>
    My Nguyen
    <br>
    <br>
    TEAM 24
    <br>
    CS157A
</h2>

<p align="center">
  <a href="#project-description">Project Description</a> •
  <a href="#system-enviroment">System Enviroment</a> •
  <a href="#functional-requirements">Functional Requirements</a> •
  <a href="#non-functional-issues">Non-functional Issues</a>
</p>

## Project Description

### Overview:
The goal of this application is to create social news, rating site, and discussion website. Users can be able to check daily news, search, filter, and sort through posts. Also, users can create posts, comment on them, like, and share posts. In addition, users can create channels that will function as communities. Users can view posts without logging in, but creating posts, commenting, and liking will require the user to login. This application will allow people to easily voice their opinion or share a story. People can easily ask questions and others can answer them. It will also provide a user-friendly interface and fast response time while maintaining high throughput. 

### Who would be interested in this application?
Users could be anyone who is interested in forming a community online, and interact with people with similar interests. Users can keep up to date with news, information, and ideas in their community. Companies and organizations can use Seenit to communicate with people and market products.

## System Enviroment
#### Structure of the system (graph based on 3-tiered architecture):
![alt text](https://github.com/CS157A-Team24/AssigmentSubmission/blob/master/System_Environment_Diagram.png)
#### HW/SW used:
+ ReactJS
+ NGINX
+ Spring Boot
+ Windows/macOS
+ MySQL Workbench
+ Visual Studio Code
#### RDBMS Used:
+ MySQL Version 5.6
#### Application languages:
+ Java (with Spring Boot framework)
+ SQL (with MySQL)
+ JavaScript (with ReactJS)
+ HTML/CSS

## Functional Requirements

### How users will interact with the system:
The application provides the same functionality for all the users. Internet connection is required for any activity on the system. A user shall be able to access the system for read and write. A user can access the system home page freely. They shall be able to read daily news and posts from various websites without logging in. Users can also be able to make a search based on their particular interests. However, users must log-in into the system and have their credentials checked for other activities such as make a new post, comment on a post, share a post, create a sub-channel, and follow another channel. Especially, first-time users must register for an account to perform the activities listed above under log-in. 

### Functions:

#### Log-in
+ Returning users must sign-in to perform the following activities: 
	+ create or access personal channel
	+ add a new post
	+ like or comment on someone else's posts
	+ share a post
	+ follow another subchannel
	+ delete personal posts
+ Guests or unregister users can only view posts

#### Register for an account
+ There will be only one type of user; no admin account in this application. First time user must sign up for an account to perform those activities listed in log-in function
+ There will be a redirect link. User will be asked to fill out some information such as first name, last name, email address, username, and password. 
+ No limitation. Users can set up multiple accounts and choose which one to log-in with depending on the personal channel which users want to participate in. 

#### Create a sub-channel 
+ Once users are signed in, users can create their own channels (similar to social media accounts). On their channel, users can be able to manage role of other users, make a new post, delete a post, check out subcribers, and display personal dashboard.
+ Users can create multiple sub-channels (up to 4). By creating a subchannel, a user can get followers or subscribers who are interested in his/her activities.

#### Search 
+ The users shall be able to search for daily news and posts by typing in keywords which appear in titles or headlines in search box. The users can also be able to search for a subchannel by entering the name of that channel in a search box.
+ If there is no matching results, a message will be shown to the user to indicate that what they look for was not found. Otherwise, display all the posts or news which are related to the searched terms.

#### Commenting

#### Posting

#### Share a post

#### Follow a specific user

#### Display personal dashboard
+ User can see how many posts they have opened
+ Display how many point/upvote they have
+ Notifying user if someone replies to his/her comment
+ Display their saved posts
+ Display their like/unlike posts

#### Display other users' dashboard
+ By clicking another user's profile, user can see the point/like, posts, etc of that specific user
+ User can't view other users' private information

#### Filter
+ Using to filter the post by date
+ Including now, today, week, month, year
+ User can active the function simply by clicking the filter button and selecting from a drop down menu

#### Sort
+ Using to sort the post by top, new and hot
+ User can active the function simply by clicking the sort button and selecting from a drop down menu

## Non-functional Issues
### Graphical User Interface (GUI): 
There are many design principles when it comes to web design. For our website, we will use seven most popular principles, which are Visual Hierachy, Divine Proportions, Hick's Law, Fitt's Law, Rule of Thirds, Gestalt Design Laws, and White Space and Clean Design.
+ Visual Hierachy: Certain parts of our website will be more important than others. We want to make those parts easily been seen and noticed by users. For examples the account button, the scrolling posts, the fillers, and the search box.
+ Divine Proportions: The layout, the size of each components should follow the golden ratio which is 1.618. For example, if the layout width is 1200px, the width of the content area should be 742px.
+ Hick's Law: "Hick’s Law says that with every additional choice increases the time required to take a decision." So, we plan to minimum the options for dropdown menu buttons. This will encourage new users tring new functions. 
+ Fitt't Law: Button's size needs to follow a set of rules. The size of the button is proportion to its using-frequency.
+ Rule of Thirds: Since our website will allow users to upload pictures. The size of a picture needs to follow the rule of thirds to make it more interesting. 
+ Gestalt Design Laws: Filter buttons, sorting buttons will be grouped together. Buttons will have consistent sizes. 
+ White Space and Clean Design: Website without white/blank space is hard to navigate. So, we will use white space to divine the components, boxes that have different functions. 
### Security
+ User accounts need to be highly protected. We don't want their personal information leaked or hacked. 
+ Passwords won't be store in blank text, it will be hashed. 
+ We will use https protocol for our web server to make sure the connection between users and server are encrypted. 
### Access Control
+ Anyone with internet can access the website
+ A user will be able to view posts/channels and search without logging in
+ A user must login to create posts, comments, or channels
+ A user cannot edit posts or comments that belong to a different user
### Performance
+ Fast response time while maintaining high throughput
+ The MySQL database will be optimized so queries don't take too long. The right data types and efficient SQL queries will make the database accesses faster and the database size smaller
+ ReactJS will be used to build the User Interface. ReactJS will allow the user to navigate through the application quickly by dynamically changing the current page instead of loading a whole new page from the server
+ NGINX can be used as a load balancer but it will require money for more resources like computers and databases. We won't use many resources during this semester, but this makes it  scalable for later
### Scalability
+ Able to add new functions and features while developing the app
+ NGINX will be used on the web server. NGINX can be used as a load balancer to distribute the work over many computers. Load balancing will help create high throughput and low response time by avoiding overloading a single computer. NGINX will allow more computing resources (CPU and memory) to be easily added to the existing system
