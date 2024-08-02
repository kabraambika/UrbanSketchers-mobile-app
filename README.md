[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9981748&assignment_repo_type=AssignmentRepo)
# Final Project

## Project name: UrbanSketchers

## Team name
Team titans

## Contributors
    Ambika Kabra
    Liang Huang
    Sifan Wei
    Vishal Pugazhendhi
 
# Team Titans Software Requirements Specification 
## App Name: Urban Sketchers

## Purpose
    This app will be used by art lovers and upcoming artists who like to draw scenery of surroundings and can share by pinning their sketches on Map.

    This app will also be providing inspiring ideas, other people's perspectives, drawing styles, and learning sessions.

## Definitions
    Tagline: "City is under your pencil".

## Background
### Why do we think this app is important?
    1. …find good arts/artists?
        It is hard to find artists on social media that take personal commissions for family portraits or for special events.

    2. …share your art on a specific platform?
        Social media apps like Instagram or Facebook contain a mixture of news feeds but are not specific to artists. For designers, using social media to share sketches may not get the expected response. They need to put many hashtags to catch the attention of other people. And it is hard to receive specific comments or instructions regarding drawing quality. For amateurs, it is hard to find a platform to share daily doodles or sketches that are not professionally done. They need a platform that accepts non-professional submissions, just to share their art mood. Learners also need a space to find local art events and find offline interest groups.
    
    This app provides a platform for artist/sketch lovers to share their immediate sketching ideas through the city. Its core idea is "urban sketch", that wherever/whenever you are in the city, you can upload your wild thoughts/impressions of a certain scenery to the platform, and share/communicate ideas worldwide. The arts have no limitation of proficiency, whether you are a professional or amateur, you can always use this app to share and learn.

## Overall Description
### User Characteristics
    Target audience for this app is:
            People who love sketching or want to try sketching.
            Established or upcoming artists 
            Tourists - This app will provide them with a unique way of exploring the city and give them a chance to jot down their impressions of the city.

    Any user with an age of 10+ years old can use this app.
    Location setting of the device should be active or manual location needs to be added for using this app.
    Any artist can share their scribble or any type of art and pin them on location. 
    Any art lover can login and according to location, users will be able to see pinned arts in nearby locations. 
    There is no gender or nationality restriction for this app.
    Any user can register to verify as an art event holder
    Any user can be verified to open to commission 

### User Stories
#### Critical Features - MVP 1
    1.  As a user, I should be able to sign up through email.
    2.  As a user, I should be able to sign in via email and password.
    3.  As a user, I should be able to share my location or enter any location.
    4.  As a user, I should be able to create a new post and choose location, tag drawing style and publicly available to everyone. 
    5.  As a user, I should be able to like the post and comment on it.
    6.  As a user, I should be able to delete the post.
    7.  As a user, I should be able to edit my profile details which is full name, bio.
    8.  As a user, I should be able to set general settings under user profile which includes Help center page, about us, terms and conditions, privacy settings page(static text).
    9.	As a user, I should be able to log out of this app.
    10.	As a user, I should be able to change any location and pin a new sketch.
    11.	As a user, I should get notifications when someone likes, comments.

#### Good-to-have Features - MVP 2
    1.  As a user, I should have the option to set my uploaded post’s privacy to public, or only me. 
    2.  Make a new post with privacy option, switch to hide/show comments and likes, also post on Facebook.
    3.  As a user, I should be able to edit the post, features that can change in existing post will be privacy settings or delete the post.
    4.  As a user, I should be able to change username and password inside app.
    5.	As a user, I should be able to share my profile.
    6.	As a user, Under general settings, option to change personal information, enable/disable commenting and notifications.
    7.	As a user, I should be able to see trending posts worldwide and locally.
    8.	As a user, I should be able to message privately to another user.
    9.	As a user, I should be able to reset my password
    10.	As a user, I should be able to message in group or send invitations
    11.	As a user, I should be able to create a group
    12.	As a user, I should be able to report an inappropriate post.
    13.	As a user, I should be able to verify to open to commissions
    14.	As a user, I should be able to hold an art event.
    15.	As a user, I should be able to follow or unfollow other users.
    16.	As a user, I should be able to apply filters on posts.
    17.	As a user, I should have the option to set my uploaded post’s privacy to only followers as well.
    18.	As a user, I should be able to save my pending post as a draft.
    19.	As a user, I should be able to get notifications when someone follows me
    20. As a user, I should be able to turn off comments or likes on my posts in general settings
    21. As a user, I should be able to pin a location on a map and upload my drawing with a brief description via long press gesture on map. 

### App Workflow (Flowchart)
Refer file: [flowchart-diagram.md](/flowchart-diagram.md)

## Requirements
### Functional
#### Welcome Page
    1.  App images with slider describing app main features and two buttons, one for sign in and another for sign up
    2.  Alert asking for permission to use location and album.

#### Sign in Page - General
    1.	Users should be able to see the welcome page while opening the app for the first time. 
    2.	On the welcome page, Users should have the option to either sign in by providing username and password. Also, if a user wants to register an account, then they should be able to sign up as well.

#### Sign in Page - Username&Passwords
    1.	User can enter registered email or username and password
    2.	By clicking the sign in button, if either of them is wrong, then pop up will appear showing message like “Username/password is incorrect.”
    3.	If everything is correct, User will successfully login.

#### Register Page - General
    1.	On the Register page, Users need to provide the following details:
        1.1.	User email
        1.2.	Photo (optional)
        1.3.	Full name
        1.4.	Bio
        1.5.	Password
    2.	After successful verification, the user should be able to see the homepage of the app.

#### Register/Sign in Page - Good to have
        1.	Reset password
        2.	OTP verification via email or phone

#### Home page - General
    1.	On the homepage, the current location should be visible on the map and pinned posts as well.
    2.	Users should be able to click on pinned posts and be able to see the post by clicking on it.
    3.	Users should be able to edit location on map and enter location manually.
    4.	There is notification icon available along with location.
    5.	Main navigation menu includes Trending, Home, New post, Chat, My profile

#### Home page - Good to have: 
    1.  Users should be able to apply filters on the Map to see desired posts.
    2.	Via microphone add location or edit.
    3.	Verification to eligible for commissions and buying or selling work, currently can be discussed in chat only.
    4.	After the sign-in process, Users would be able to pick their preferred artist style. And the app will recommend similar posts based on the chosen style. (Tags)

#### Post Page - Create new posts
    1.	Users should be able to pin a new post with a privacy setting and add a brief description with emoticons and add different tags to the post.
    2.	Users should be able to edit the post or delete as well.
    3.	By default, the comments feature will be active on post.
    4.	Users should be able to disable comments for post.
    5.	This link can be copied by users and others to share the post. A unique link should be created for the post.
    6.	After successful post, we can see successfully posted message on homepage and map will be focus on that pinned post.
    7.	Multiple pictures can be chosen for post and chosen ones will be ticked

#### Post Page - Edit post
    1.	Change visibility of sketch (public, only me)
    2	Delete this sketch
    3.	Turn off commenting 

#### Post Page - Delete post
    1.	Showing an overlay with alert for confirmation, if clicks on yes then navigated to grandparent page 

#### Post Page - Good to have
    1.	Enabling to post automatically on Facebook, twitter on create a new post page
    2.	Hide likes and views on create a new post page
    3.	Followers option in change visibility for follow feature
    4.	Turn off comments – toggle on create a new post page
    5.	Draft posts: Users should be able to save posts and investigate them collectively

#### Trending Posts Page
    1.	There should be a section on the homepage that highlights popular posts.
    2.	Most liked posts will be visible first.
    3.	Sub sections like world-wide trending and local trending.
    4.	Top 10 posts only if more than 10 are available else all are visible

#### Notification Page - General
    1.	There should be a notification section showing people who liked the user's post or new comment given on any post. On clicking these two notifications, the person is navigated to related post.
    2.	A new group chat invite should be also visible here.

#### Notification Page - Good to have
    1.	New followers should be notified as well (follow feature)
    2.	Quick reply on any comment notification

#### User profile Page - General
    1.	Users should be able to see their own profile, by clicking menu “My profile”
    2.	User’s photo will be visible along with their username and full name and default profile background if no image available.
    3.	The user should be able to see all the posts they have uploaded.
    4.	Users should be able to make changes to their profile picture.
    5.	New post should be visible on top of the user profile
    6.	User should be able to share profile
    7.	Profile’s settings should be available here as well.
    8.  User can edit profile pic, name, bio.
    9.  Via link only they can share profile.

#### User profile Page - Good to have
    1.	The user should have the option of being verified to open to commission.
    2.	Filter for posts
    3.	Follow feature
    4.  QR code scanning and generator

#### Settings Page - General
    1.	Privacy settings
    2.	Terms and conditions
    3.	Sign out option
    4.	Personal information: edit email and phone number
    5.	Help 
    6.	About

#### Settings Page - Good to have
    1.	Comment Settings page will have option to turn off commenting on all posts
    2.	Notification settings: Turn off notifications

### Non-functional
#### General
    1.	If the location setting is not active on device, then prompt should be visible on the app asking the location setting to be on.
    2.	If a user is not allowed to access photos/album, Post will not be able to upload.
    3.	Multi-platform: All features available on all type of platforms , ios, android and web
    4.	Accessibility: Semantics will be implemented in app
    5.	Internationalization: generic icons are used 
    6.	Simplification: App is easy to use and no complex features for users
    7.	Security: taking permission from the user about location usage and camera access. Also, the app will handle data storage, data transmission, and data protection
    8.	Performance: Live updation on user profile if new post created without delay and in case of more than 20 posts in user profile, Lazy loading will happen
    9.	Improving search functionality: Make sure that the search functionality is robust, allowing users to find what they are looking for easily.

#### Technology Stack
    1.	Firebase and RESTAPI for storing data and support some features chat feature, login via google, map API, Album access and location	
    2.	Testing and Debugging: Unit testing, Widget testing, Accessibility testing will be done for all features. The app will be thoroughly tested on different devices and platforms to catch bugs and ensure compatibility.

#### Good to Have
    1.  Adding gamification elements: Consider adding gamification elements like challenges or contests to keep users engaged and motivated. Just have a try over this point.	 
    2.  Integration with APIs: To provide a seamless experience, the app may need to connect to various APIs, such as location services or social media.

## Wireframes
External link: [Figma Link](https://www.figma.com/file/e4q3HUYpwsNcOIBUt968MS/HIFI_Draft?node-id=0-1&t=YytOHd8NhAo4n0Xn-0)

## UML Class Diagram
Refer file: [model-class-diagram.md](/model-class-diagram.md)

## Gantt Diagram
Refer file: [gantt-diagram.md](/gantt-diagram.md)

## Traceability Matrix
Refer file: [traceability-matrix.md](/traceability-matrix.md)
