###################################
Tutorial 5 Starter Webapp - Caboose
###################################

This is the starter webapp for CodeIgniter Tutorial #5.

Unlike an earlier version, this version is fully functional, just feature incomplete.

The project uses a "quotes" database, setup through quotes-setup.sql in the project root.

The homepage displays the most recently added quote, with drill-down to see a 
specific quote in detail.

The Viewer controller displays all the quotes on file, by default.
Each mugshot links to a viewer/quote method call, to display that author's quote.


**************
Intended Usage
**************

Fork this project.
Clone it locally.
Enhance it per the tutorial

*****
Setup
*****

If you want to run this webapp locally, create a database (for instance
"quotes") and import the quotes-setup.sql into it.

Tailor application/config/database.php appropriately.

***************
Project Folders
***************

/application    the obvious
/assets         CSS, javascript & media
/data           Author mugshot images

Assumed: CI system folder is in ../system3

*******
License
*******

Please see the `license
agreement <http://codeigniter.com/userguide3/license.html>`_

*********
Resources
*********

-  `Informational website <https://codeigniter.com/>`_
-  `Source code repo <https://github.com/bcit-ci/CodeIgniter/>`_
-  `User Guide <https://codeigniter.com/userguide3/>`_
-  `Community Forums <https://forum.codeigniter.com/>`_
-  `Community Wiki <https://github.com/bcit-ci/CodeIgniter/wiki/>`_
-  `Community IRC <https://codeigniter.com/irc>`_

***************
Acknowledgement
***************

This webapp was written by James Parry, Instructor in Computer Systems
Technology at the British Columbia Institute of Technology,
and Project Lead for CodeIgniter.

CodeIgniter is a project of B.C.I.T.