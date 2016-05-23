Simple One-on-One
=================

View the website in [production](https://simple-one-on-one.firebaseapp.com/).

This is very simple app to track one-on-ones as a manager. The key feature is to be able to take notes about a person who reports to me over time and then be able to view those notes either based on time or peep.

For example, typical queries are of the format "What are my plans for one-on-ones this week?" or "What has person X been up to this month?".

This was a weekend hack project / proof-of-concept and as such has no test coverage and poor code quality. I am deeply ashamed but this serves as a funtional prototype to determine if this sort of note keeping is valuable. 

The app uses Firebase for persistent storage. This should facilitate building a simple android app as well.

Deployment
----------

To deploy, install the Firebase cli and run ``firebase deploy``.
