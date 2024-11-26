## Warbler 
To get this application running, make sure you do the following in the Terminal:

1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `createdb playlist-app`
5. `flask run`

Warbler is a python based application which utilizes flask as its framework.

It is a social media platform similar to `X or Twitter` it allows users to signup, login, logout, modify location, biography and header image.
The homepage will show the last 100 `tweets` from the users following list only.
Similarly there is a following, followers as well as a users list which each have a user card displaying information on a user.
Users are able to edit their own profile to their liking changing: `username`, `email`, `image_url`, `header_image_url`, `bio` and `password`.
Passwords are validated for criteria and if not will display an error.

Users are able to like other `warbles`, this was implimented into the project without the use of JS/AJAX whcih will leave a star beside it whcih can be pressed again to unlike it. A user's profile will display how many `warbles` they have liked and a link showing their liked warbles.


