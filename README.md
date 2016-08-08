# Udacity Multi User Blog

Blog online: http://multiuserblog-1470682713100.appspot.com/
Multi User Blog Project for Udacity Full Stack Nanodegree

## Project Overview 

The goal of this project is to create a simple multi-user blog along the lines of "Medium". 

Users should be able to create an account with login/logout functionality, and create/edit/delete posts and comments.


## How To Run

1. Clone the project (git clone https://github.com/Ahmed-elsayed-mahmoud/Project-3_Multi-User-Blog.git)
2. Install google app engine
3. Import the application into the laucher.
4. Click on run button
5. Or open command prompt in project folder and run following command: $dev_appserver.py .
6. App will start running on configured port.

## Project specifications

Blog must include the following features:
- Front page that lists blog posts.
- A form to submit new entries.
- Blog posts have their own page.

Registration must include the following features:
- A registration form that validates user input, and displays the error(s) when necessary.
- After a successful registration, a user is directed to a welcome page with a greeting, “Welcome, *name*” where *name* is a name set in a cookie.
- If a user attempts to visit a restricted page without being signed in (without having a cookie), then redirect to the Signup page.

Login must include the following features:
- Have a login form that validates user input, and displays the error(s) when necessary.

Users must include the following features:
- Users should only be able to edit/delete their posts. They receive an error message if they disobey this rule.
- Users can like/unlike posts, but not their own. They receive an error message if they disobey this rule.
- Users can comment on posts. They can only edit/delete their own posts, and they should receive an error message if they disobey this rule.

Code must conform to the [Python Style Guide](https://www.python.org/dev/peps/pep-0008/)

## Setting up your computer

1. [Install Python](https://www.python.org/downloads/) if necessary.
2. [Install Google App Engine SDK](https://cloud.google.com/appengine/downloads#Google_App_Engine_SDK_for_Python).
3. Open GoogleAppEngineLauncher.
4. [Sign Up for a Google App Engine Account](https://appengine.google.com/).
5. Create a new project in [Google’s Developer Console](https://console.cloud.google.com/) using a unique name.
6. Create a new project from the file menu and choose this project's folder.
7. Deploy this project by pressing deploy in GoogleAppEngineLauncher.
8. When developing locally, click “Run” in GoogleAppEngineLauncher and visit localhost:Port in your favorite browser, where Port is the number listed in GoogleAppEngineLauncher’s table under the column Port.


## Frameworks/technologies used
- [Bootstrap](http://getbootstrap.com/)
- [jQuery](https://jquery.com/) - for Bootstrap
- [Google App Engine](https://cloud.google.com/appengine/docs)
- [WTForms](https://wtforms.readthedocs.io/en/latest/)
- [PyCrypto](https://pypi.python.org/pypi/pycrypto)

  
# License

The project is licensed under the [Apache License](LICENSE).