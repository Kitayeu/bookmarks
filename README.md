bookmarks
================================

### This is social application, which means that users are able to join an online platform and interact with each other by image sharing. Users will be able to bookmark any image on the Internet and share it with others. They will also be able to see activity on the platform from the users they follow and like/unlike the images shared by them


### Implemented:
* Using the Django authentication framework
* Extending the user model with a custom profile model
* Adding social authentication with Python Social Auth so that users can use their existing Facebook or Google account to log in
* Created a custom authentication backend to let users log in to your site using their email address
* Creating many-to-many relationships
* Customizing behavior for forms
* Using jQuery with Django
* Building a jQuery bookmarklet
* Generating image thumbnails using easy-thumbnails
* Implementing AJAX views and integrating them with jQuery
* Creating custom decorators for views
* Building AJAX pagination
* Building a follow system
* Creating many-to-many relationships with an intermediary model
* Creating an activity stream application
* Adding generic relations to models
* Optimizing Query Sets for related objects
* Using signals for denormalizing counts
* Storing item views in Redis
* Used Redis to store item views, and image ranking with Redis


### Getting Started:
1. use yourself data for email, facebook, google from settings.py
2. enable access of insecure applications in mail
3. in terminal to run server: python manage.py runserver_plus --cert-file cert.crt
4. use address to connect: https://mysite.com:8000/account/
5. start the Redis server: sudo service redis-server start
6. to stop your Redis server: sudo service redis-server stop


### Additional Programs:
for Windows
- Windows 10 with WSL
- Ubuntu 18.04 
- redis-cli 4.0.9


## Required packages:

* Python 3.9
* virtualenv + pip
* Git