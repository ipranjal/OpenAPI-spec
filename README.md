# OpenAPI-spec
Open API 3.0 spec for creating social networking API

This specification was created as part of **The Postman API Hack** and provides a **OpenAPI 3.0** specification for creating Social Networking API, using these API's you can create a social networking website like Facebook, Twitter

You can goto https://osssocial.postman.co to find the workspace with API collection , Tests and Mock Server for developing using this API specification. 

You can get more details about the hackathon and project at https://physcocode.com/category/postman/

### This specification defines implementaion of following API:
1) **User API collection** - Collection of API's to manage users
2) **Posts API collection** - Collection of API to manage posts that can range from small tweets to a full image post or even a slide of images
3) **Like and Comment API collection** - API to manage likes and comments attached to posts
4) **User Relation API collection** - Collection of api to mange relation between users (friends,follow,cirecles etc)
5) **Messaging API collection** - Collection of api for building 1-1 or group

### This specification defines following model:
1) **User** - to store and retrieve user data
2) **Post** - this is the basic backbone of social feature, a post can be anything from short tweets, to image based post 
3) **Feed** - this is used to store interaction between users , user and post and other activity of users. Eg : X likes a post , X is now friends with Y etc. These activities can then be displayed on feed
4) **UserRelation** - this stores relation between two users , this can be used to implement relations like 'friends', 'follow' or something as complex as 'circles' that was introduced by Google +
5) **Message** - this stores messeges sent in groups or 1-1 interaction
6) **MessageRoom** - this stores the messaging rooms , rooms can be 1-1 messaging rooms or group message rooms. Message rooms are where messages are exchanged
