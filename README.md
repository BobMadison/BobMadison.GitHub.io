# BobMadison.GitHub.io

This portfolio is the final project for the Red Badge in the Software Development course with the Eleven Fifty Academy. It contains a Navbar, bootstrap JumboTron, three rows of three bootstrap cards, a contact section, and a copyright footer.

There is a link to a resume in the JumboTron. Following the JumboTron is the About section (also accessed from the navbar.)
After the About section there is a 3-card section with the three projects for the Gold Badge in Eleven Fifty's Web Development course.

Row 1, Card 1: CSS Creature. Clicking the button takes you to a directory (VampireKoala) on my www.robert-david-madison.com website.

Row 1, Card 2: NETFLIX Static Web page. Clicking the button takes you to a directory (NetflixStaticPage) on my site.

Row 1, Card 3: National Parks API. Clicking the button takes you to a directory (NationalParksAPI) on my site.

Row 2, Card 1: CSS Creature. Clicking the button takes you to a directory (VampireKoala) on my site.

Row 2, Card 2: Static Storefront. Clicking the button takes you to a directory (StaticStoreFront) on my site.

Row 2, Card 3: Cities of North America. Unfortunately, I wasn't able to successfully deploy this really nice project to Azure. Currently, if you click the button you go to the National Parks API on my site.
               
Row 3, Card 1: Clicking the button will take you to the Software Development Gold Badge projects on GitHub. These were solo.

Row 3, Card 2: Clicking the button will take you to the Software Development Blue Badge project on GitHub. This was a three-man effort.

Row 3, Card 3: Clicking the button will take you to the Software Development Team Game project on GitHub. This was an effort of three people.

Next is the communication section. There's a link to my LinkedIn and GitHub. You can also leave a message via Formspree.

RED BADGE PROJECT
This is the link to trello --->>> https://trello.com/b/pgRx4lBE/cities-of-north-america. I didn't really keep up with it as I knew what I wanted to do and how to do it.

This is the link to the Table Diagrams --->>> https://dbdiagram.io/d/605cd6aaecb54e10c33d491b I did keep up with them, and this table diagram is 100% accurate. This link can also be accessed through Trello.

This is the link to the wire frames --->>> https://bsyl9v.axshare.com. I used this as a very basic guide as my actual pages were, in my opinion, much better. This link can also be accessed through Trello.


The Cities of North America WVC Project

In edition to a user table, there were three other tables.

1. City table. This table included the name and the state or province of the city.
2. Restaurant table. Name, cuisine, and location information. Associated with the City ID foreign key.
3. Site table. Name, description, and location information. Associated with the City ID foreign key.

CITY CRUD
An authorized user can Create a city, Update city information, and Delete a city. This would delete (cascade delete) ALL restaurants and sites within the city.

RESTAURANT CRUD
Anyone can create a restaurant, regardless of who created the city. Only the creator of the restaurant can Update or Delete it. Any user can Get (R) the restaurant data.

SITE CRUD
Anyone can create a site, regardless of who created the city. Only the creator of the site can Update or Delete it. Any user can Get (R) the site data.

DISPLAY
When a user clicks Details for a city, the city map of the city displays at the top of the page. Below there are two columns.
The column on the left lists all the restaurants associated with the specific city, and the sites are listed in the column on the right. Each restaurant and site display in a bootstrap card with a mini-map, name, etc. There is a button on each which links the user to the restaurant or site's web site.

GOOGLE MAPS
With Andrew and Trevor's help, I was able to quite nicely implement using Google Maps.

I thoroughly enjoyed this class. I am disappointed I wasn't able to deploy to Azure.
