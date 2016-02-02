This is the webpage for the Geeks and Gadgets Club
This text file is to establish protocols to be used throughout the website.
Using these protocols will make multiperson developement easier and keep things organized.
If you have any questions or comments about these protocols, please email Patrick Shinn
at shinn16@marshall.edu


Site Organization
------------------------------------------------------------------------------
The site is organized in a way that each page gets it's own folder for contents.
Doing this will keep the site organized and fast. Only pages with additional content
should get a folder such as images, text documents, applications, etc. This is not true for
the home page however, the home page will always remain in the root directory of the site as
well as its contents. If a page has no additonal content, it may remain in the same directory
as the page that it is linked to.

Examples:
The about page needs pictures to attach for each officer. Because it needs space for more content
it gets its own folder to seperate its content from the rest of the website and for easy access to
this content for developement and page speed.

A page to suppliment the officer portion of about such as a page dedicated to the treasurer would not need
its own directory. It would use the same resources as the about page and would be related to the about page,
thus it would be in the same folder as the about page.


Page Formating
-------------------------------------------------------------------------------
All page Formating will be done with a single CSS file. This file will reside in the root
directory of the site. All pages will be styled the same with the exception of key element
that seperate that page from the rest of the site. All additional contents needed for page styling
should be placed in the contents folder of the root directory.

stylesheet.css will be the formating file. The file is commented for organization purposes and for
ease of use. Please be sure to follow along with the sections.

If your page needs a special class that the rest of the site will not use, place it in the html document.
Internal style sheets should be used if it style only affects one page.


Web Apps
-------------------------------------------------------------------------------
There is no protocol for apps at the moment. This will change in the future when we can support them.


Closing
-------------------------------------------------------------------------------
This is a living document and will evolve with the site over time. Please be sure to follow the directions
entailed so that the site is well organized and easy to develope for people who have never seen the code before.
Commenting is heavily suggested.