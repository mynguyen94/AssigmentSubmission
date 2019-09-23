<h1 align="center">
    <br>
    <br>
    SeenIT  
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
  <a href="#project-overview">Project Description</a> •
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
*INSERT DRAWIO PICTURE*
#### HW/SW used:
+ ReactJS
+ NGINX
+ Spring Boot
+ Windows/macOS
+ MySQL Workbench
+ Visual Studio Code
#### RDBMS Used:
+ MySQL Version 5.6
#### Application languages…(Java, XML, SQL, GUI Builder, Designer, GTK+…etc):
+ Java (with Spring Boot framework)
+ SQL (with MySQL)
+ JavaScript (with ReactJS)

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

#### Display other users' dashboard

#### Filter

#### Sort


## Non-functional Issues
### Graphical User Interface (GUI): 
There are many design principles when it comes to web design. 
### Security
### Performance
### Scalability
### Accessibility

