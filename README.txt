----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------

				   Discussit PHPBB API  
			              Documentation


----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------


Contents:

1. Introduction

2. Install

3. Uninstall

4. updating your filters.txt

5. Adding filters to the moderator

6. Support


----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------

1. Introduction

PHPBB API allows you to connect your PHPBB forums to the DiscussIt moderator. 
this allows you to moderate and gather statistics on your forum. This API was 
designed for version 3.0.10 of PHPBB.

----------------------------------------------------------------------------------------------

2. Install
It is recommended to backup your website/forum before you begin.

1:  Download The Latest PHPBB API From the DiscussIt website. 

2: Unzip the files. You will end up with a folder called api with php files in and a folder 
called includes.

3. Place the api folder into the main folder of your PHPBB forum. This is where your 
search.php and viewforum.php are located. 
You should now have a folder called api in your main phpbb forum. make sure you have 
uploaded this to your web host if you haven’t already.

4: Find your Site Key and Site Secret from the settings page of your discussit sconsole. 
also make sure your default site filter is set to your website with a /* at the end aka: 
http://www.yourwebsite.com/* 

If you don’t already have a discussit account you’ll need to contact us at: 
http://www.discussit.com/contact-us/

5. Now that you have your Site Key and Site Secret and uploaded the API to your host you 
need to run the install.php file located in the API. for example:
www.yourwebsite.com/yourforum/api/install.php

It will ask you for your username and password. the username is the Site Key, and the 
password is the Site Secret. enter them and press submit.
	
“Successfully created tables - please delete this file (install.php)” will be displayed 
once the install is successful.

Make sure you remove the install.php from your website once installed.

6. check your website is configured by visiting the moderator for your web site aka:
https://account.discussit.com/WebGUI

*Please note if you change your Site Key or Site Secret you will need to place the 
install.php file back into your api folder and run it with your new Site Key and Site Secret. 

----------------------------------------------------------------------------------------------

3. Uninstall

1. Run the configphpbb.php file on your web site.

2. Click the uninstall button. - this will bring up a box to place in your 
username and password.

3. Enter your Site Key into the username box and your Site secret into the 
password box. then click submit.

4. Once uninstalled you should get a message saying “Tables uninstalled”.

5. Delete the API folder from your PHPBB board folder.

*If you would like to reinstall just follow the installation guide again.

----------------------------------------------------------------------------------------------

4. Updating your filters.txt
1. Run the configphpbb.php file on your website.

2. Click the update filters button. This will populate your filters.txt 
with your current forums.

----------------------------------------------------------------------------------------------

5. Adding filters to the moderator
1. Go to the sconsol at http://account.discussit.com/SConsole and login.

2. Click on the website you wish to add a filter to. You must be an administrator of the 
website to add a filter.

3. Click Site Filters on the top bar.

4. Type in a name for the filter in the box and click add.

5.The title is what you want the filter to be called, it is recommended to use a short name 
i.e. Tech support  instead of technical support.

The filter string is the address of your forum you want associated with this filter. It 
should look something like this:
http://yourwebsite.com/viewtopic.php?f=6 or http://yourwebsite.com/viewforum.php?f=6

The easiest way to get this url is to go to the forum you wish to associate the filter with 
and copy the address from the address bar. The address should always end in ?f= followed by 
a number. 

Now click add filter.

6. When you refresh your moderator page you should see the filters you have created in the 
dropdown filters box in the top left corner of the screen, just below the comments and 
statistics tabs. 

----------------------------------------------------------------------------------------------

6. Support

If you need any help or encounter any bugs and faults please check out our support page at:
http://www.discussit.com/  or contact us at http://www.discussit.com/contact-us/ 

----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------