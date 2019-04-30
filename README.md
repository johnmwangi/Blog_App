# Blog

## Built By [John Mwangi](link)

## Description
Blog is an application that allows user to view blog, posts, submitted and comment on them and leave any feedback.


## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like to:
* View the blog posts submitted.
* Comment on blog posts.
* View the most recent posts
* Alerted when a new post is made by joining a subscription.
* comment on the different pitches and leave feedback.

## User Abilities
These are the behaviours that the application implements for use by the user.

Users would like to:
* Sign in to the blog
* Create a blog from the application
* Delete comments that I find insulting or degrading
* Update or delete blogs I have created.


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Writer/Blogger Authentication | **On demand** | Access Admin dashboard |
| Display blogs by most recent | **Home page** | Clickable links to open all blogs |
| Display profile | **Click profile page** | Redirected to a page with your profile |
| Display single blogs | **On link click** | Blog is displayed with comment ready function plus any comments already stored |
| To add a blog  | **Through Admin dashboard** | Redirected to the new blog form collection form|
| To edit a blog  | **Through Admin dashboard** | Redirected to the  blog form collection form and editing happens|
| To delete a blog/comments  | **Through Admin dashboard and on displays** | Bad comments and posts can be deleted|
| To subscribe  | **On button click** | Users can subscribe on click|


## SetUp / Installation Requirements
### Prerequisites
* python3.6
* virtualenv
* Requirements.txt

### Cloning
* In your terminal:

       *  git clone (link)


## Running the Application
* Creating the virtual environment

       *  python3.6 -m venv --without-pip virtual
       *  source virtual/bin/env
       *  curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Flask and other Modules

       * see Requirements.txt

* To run the application, in your terminal:

       *  chmod +x start.sh
       * ./start.sh

## Testing the Application
* To run the tests for the class files:

       * python3.6 manage.py test

## Technologies Used
* Python3.6
* Flask

## License

Copyright (c) 2019 John Mwangi.
