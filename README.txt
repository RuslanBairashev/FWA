FWA
Java Servlet API

Exercice 00 : Welcome To Servlets
You need to develop a web application prototype using Java Servlet API stack. The
application will automate the booking business process of a movie theater later on.
Now you will develop an MVP application to partially implement registration and authentication
mechanisms.
Thus, your web application should provide HTML registration and authentication pages
in response to /signIn and /signUp URL requests, respectively.

Exercice 01 : Authentication
Let us expand the functionality of our application by providing an authorization
mechanism. You know from the previous task that for authenticated users there is
a session that has user attribute with the specified value. You shall provide profile
page access (the one with a single <h1>Profile</h1> tag) only to authenticated
users.

Exercice 02 : JSP
Now you need to implement your profile page as a JSP file.
Information about the date / time / IP address of all user authentications as a list shall
also be displayed on this page.
In addition, the page shall have a user’s "avatar" loading functionality. To implement
that, you shall provide for processing a POST request to /images URL. The uploaded
image shall be saved to disk.
