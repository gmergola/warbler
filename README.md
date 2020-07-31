## Getting started with Warbler
1. Clone this repository and cd into it
2. Create a Virtual Environment `python3 -m venv venv`
3. Activate your virtual environment`source venv/bin/activate`
4. install all depencies to run this application `pip install -r requirements.txt`

## Warbler
A Twitter clone application!

* Warbler was built with Flask and Jinja templates on the frontend paired with Flask and PostgreSQL on the backend.
* Warbler uses Flask's WTForms to validate information going in and out of the database.
* Warbler also uses Flask's Session to store if a user is logged in and the correct user. By correct user I mean, when the user is trying to edit their profile they can only edit their own and no one else's, a user can only delete their profile and no other, a user can only like other's posts and not their own.
* While using Warbler, a user can: write posts, like other's posts, edit their profile, follow other user's, and delete their profile.

[Live App Demo](https://genna-k-warbler.herokuapp.com/)


