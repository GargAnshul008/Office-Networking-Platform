
# Big Apple: An Office Networking Platform

## Project Description: 

For the class project you will have to design and implement a backend of a web based application that
will use a database system to manage all the application data. Your application should include elements of social networks
(users have friends, relationships, posts to other users, etc), multimedia content (photos, videos, etc) and location services
(maps). 

More specifically, your system should support the following three aspects:

### First
Users who have signed up for a service should be able to post content, such as a profile, post entries (also called notes or postings), and some multi-media
items such as photos, audio or video, which will be made accessible via a page on the site that is created for that user.

### Second
The users should be able to define relationships with other users that they know or that they consider their friends.
Users should then be able to restrict content so that only they, or their direct friends, or friends of these friends, or everybody,
can access their content. 

### Third
Other users or visitors should be able to browse and search for content, subject to the access
restrictions selected by the users who posted the content. Users who visit another user’s page on the site should also be
able to leave greetings, comments, and tips about other places for similar items, and to ask recommendations for services
and tools (e.g. best security conference), etc. 

Thus, the most important concepts in this project are users, posts, comments, activities, locations, and their various relationships.

## PART 1
In this first part of the project, you are asked to design a database backend for such a system, that is, a suitable relational
schema with appropriate keys, constraints (and maybe views), plus a set of useful queries that should be created as stored
procedures. You may use either your own database installation on your laptop (based on Windows, Linux or Mac), or on the
internet, but no MS Access. Make sure to use a database system that supports text operators, such as “like” and “contains”,
since you should allow users to search the site and textual content by keywords.

## PART 2
In the second project, you have to create a web-based user interface for the database designed in the first project. In
particular, users should be able to register, create a profile, log in, create posts, add pictures or video to posts, maintain
friendships or relationships with other users, like pictures, like activities, pin locations on maps, send and answer
friend requests, etc., as described.

### MORE DETAILS:
Following are more details about the problem domain you are dealing with. Obviously, we will have to make some simplifying assumptions to the
scenario to keep the project reasonable.

You are free to choose your own application scenario, below you will find a list of possible applications for users of specific
social network application that you may decide to choose, or you can create your own application scenario. To learn
about social networking sites, you may want to look at a few existing systems such as Facebook, LinkedIn, FourSquare, or
Pinterest. 
