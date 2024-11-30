Project-Content Management System
Website that you have to build that two aera, Public Aera and Admin aera.

Figure 1-Public & Admin Aera

Public aera (fig-1) is simple having similar page structure. An aera for navigation like a menu
and content and aera for the content using pick an item which will show pages contents. Pick a
navigation item, get new items. Site will have sets of pages called subject so picking a subject
and page.
For the admin aera (fig-1), there will be login page where you will be asked the user to login
using username and password to gain access and if login fails then try again. If the login is
successful though then it will lead to Admin Menu page. That is simple landing page having
options like manage content, manage admins and logout. Those options are just links that will
bring to different pages. In manage contents, there will be navigation area to navigate between
subject and pages which will allow the admin to do subject CRUD and Page CRUD i.e. Create,
Read, Update and Delete. There will be another CRUD section in admin menu i.e. Manage
admins for admin CRUD which will able to do the add admin using username and password,
delete and edit them. And in final menu option, there will be logout which will be able to logout
from the admin section and take you back from login section again.

Figure 2-index.php

This is widget corp site. This is index.php (shown in fig-2), the default page of the public side of
the site. There is a header widget corp at the top and have a navigation bar on left side with links
in it and on the right side, there is page content has simple welcome message.

Figure 3 Our History

The navigation bar contains about Widget Corp products and services as links. On clicking the
About Widget Corp, there will be some pages beneath it like our mission and our history(fig-3).
Similarly, for products and services as shown in given pic (fig-4, 5).

Figure 4 Products

Figure 5 Services

For the admin side, you have to go public/login.php (shown in fig-6) in the address bar where
widget corp admin page should be seen for admin to login using username and password by
clicking on submit button. After login, the page will redirect to public/admin.php which will
have menu page and have welcome message for the username along with other links like manage
website contents, manage admin users and logouts.

Figure 6 Admin Page

Once you will click manage website contents, there will be similar page like public side except it
is not collapsing down i.e. all the things all the down with few extra things like add a subject,
certification and today’s Widget Trivia, those are the things which public will not able to
see(visible =no) them but admin(shown in fig-7, 8 & 9).

Figure 7 Manage Website Contents

Figure 8 Certification

Figure 9 Today’s Widget Trivia

Inside edit subjects or add a subject link (shown in fig-10), admin will allow to control Menu
name, position, visible and add new contents and cancel will off course bring out of this page.
There is also delete page at the bottom to delete the pages as well (shown in fig-11).

Figure 10 About Widget Corp

Figure 11 Edit Page

Inside manage admin, there will be list of usernames (shown in fig-12) where admin will be able
to edit and delete control for these users. Edit option can change password given a username.
Also there will be add new admin link too (shown in fig-12).

Figure 12 Edit and delete Admin

In the last of all there will be logout option link. And once you logout, it should redirect to
public/login.php page.

Figure 13 Logout

To setup database table, consult fig-14.

Figure 14-CMS Database
