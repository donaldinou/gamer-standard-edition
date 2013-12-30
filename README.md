Nuked Klan Gamer Standard Edition
=================================

Welcome to the Nuked Klan Gamer Standard Edition.

This document contains information on how to download, install, and start
using Nuked-Klan for gamer.
For a more detailed explanation, see the [Installation][1].

1) Checking your System Configuration
-------------------------------------

Before installing Nuked Klan Gamer Standard Edition, be sure you've got
all requirements:

* An apache server
* A MySQL database
* PHP >= 5.3.3
* Permissions to write in the installation directory

2) Installing the Standard Edition
----------------------------------

When it comes to installing the Nuked Klan Gamer Standard Edition, you have the
following options.

### Use Composer (*recommended*)

As it uses [Composer][2] to manage its dependencies, the recommended way
to create a new project is to use it.

If you don't have Composer yet, download it following the instructions on
http://getcomposer.org/ or just run the following command:

    curl -s http://getcomposer.org/installer | php

Then, use the `create-project` command to generate a new Nuked Klan application:

    php composer.phar create-project nuked-klan/gamer-standard-edition path/to/install

Composer will install Nuked Klan and all its dependencies under the
`path/to/install` directory.

### Download an Archive File

To quickly test Symfony, you can also download this [archive][3], or this [one][32]
of the Gamer Edition and unpack it somewhere under your web server root directory.


3) Browsing into the install directory
---------------------------------------

Now, you need to parameter your database.
In order to do it, just start your web browser and go to the following address:
("yoursite.com" replace your web address)

    http://www.yourwebsite.com/INSTALL/

Select the desired language and click on the submit button.
Choose the desired installation mode “installation with assistance”
(recommended for novices) or “speed installation”.
Follow the step to step procedure and that's it!

Bravo! You're now ready to use Nuked Klan.
For more information about your installation, go to the NK_support_forum

4) Which modules inside
------------------------

The Nuked Klan Gamer Edition is configured with the following modules:

  * [**404**][4] - 404 support for inexisting page

  * [**Admin**][5] - Back office for the CMS

  * [**Archives**][6] - Manage somes archives

  * [**Calendar**][7] - Schedule and events

  * [**Comment**][8] - Authorize user to add comment to your website

  * [**Contact**][9] - Manage contact

  * [**Defy**][10] - Authorize somes other teams to defy you

  * [**Download**][11] - Download files or any documents

  * [**Forum**][12] - A Forum

  * [**Gallery**][13] - A gallery images support

  * [**Guestbook**][14] - A guestbook

  * [**Irc**][15] - Display your Irc server and your website

  * [**Links**][16] - Add some links to your website

  * [**Members**][17] - Manage members

  * [**News**][18] - Manage news

  * [**Recruit**][19] - Recruit players into your teams

  * [**Search**][20] - Search on your website

  * [**Sections**][21] - Add sections and blocks to your website

  * [**Server**][22] - Display your team server on your website

  * [**Stats**][23] - Accumulate some stats

  * [**Suggest**][24] - Authorize your members to suggest some stuffs

  * [**Survey**][25] - Survey module

  * [**Team**][26] - Manage teams

  * [**Textbox**][27] - Add some textbox to yourwebsite

  * [**User**][28] - Manage users

  * [**Userbox**][29] - Userbox or chat-room

  * [**Vote**][30] - Vote module

  * [**Wars**][31] - Add wars to your website


[1]:  http://www.nuked-klan.org/index.php?file=Forum&page=viewtopic&forum_id=6&thread_id=4577
[2]:  http://getcomposer.org/
[3]:  http://www.nuked-klan.org/index.php?file=Download&op=description&dl_id=711
[4]:  https://github.com/donaldinou/nuked-module-404
[5]:  https://github.com/donaldinou/nuked-module-admin
[6]:  https://github.com/donaldinou/nuked-module-archives
[7]:  https://github.com/donaldinou/nuked-module-calendar
[8]:  https://github.com/donaldinou/nuked-module-comment
[9]:  https://github.com/donaldinou/nuked-module-contact
[10]:  https://github.com/donaldinou/nuked-module-defy
[11]:  https://github.com/donaldinou/nuked-module-download
[12]:  https://github.com/donaldinou/nuked-module-forum
[13]:  https://github.com/donaldinou/nuked-module-gallery
[14]:  https://github.com/donaldinou/nuked-module-guestbook
[15]:  https://github.com/donaldinou/nuked-module-irc
[16]:  https://github.com/donaldinou/nuked-module-links
[17]:  https://github.com/donaldinou/nuked-module-members
[18]:  https://github.com/donaldinou/nuked-module-news
[19]:  https://github.com/donaldinou/nuked-module-recruit
[20]:  https://github.com/donaldinou/nuked-module-search
[21]:  https://github.com/donaldinou/nuked-module-sections
[22]:  https://github.com/donaldinou/nuked-module-server
[23]:  https://github.com/donaldinou/nuked-module-stats
[24]:  https://github.com/donaldinou/nuked-module-suggest
[25]:  https://github.com/donaldinou/nuked-module-survey
[26]:  https://github.com/donaldinou/nuked-module-team
[27]:  https://github.com/donaldinou/nuked-module-textbox
[28]:  https://github.com/donaldinou/nuked-module-user
[29]:  https://github.com/donaldinou/nuked-module-userbox
[30]:  https://github.com/donaldinou/nuked-module-vote
[31]:  https://github.com/donaldinou/nuked-module-wars
[32]: https://github.com/donaldinou/gamer-standard-edition/archive/master.zip