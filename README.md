# LittleSingapore
---

Page Layout Design
---

Between containers: 60px

Divisions within containers: 30px

Header size: h3

Sub-header size: h4

Text font size: p

Row settings: style="margin-left: 0, no-gutters
  


Content Structure Updates

---

### Homepage

Navbar:
Events, Attractions, Logo, Information, Book Now

Carousel:
Carousel

Section 3:
Opening hours, Getting here, Support,  Promotions

Sections 4:
Promotions
Main Attractions
Events

Section 5:
About us

Footer:

---

### Attractions page

Navbar

Events

Minimap

Attractions (Main attractions & Rides to the lesser rides)

Facilities:
Stated on minimap, brief description only

Footer

---
### CSS Content Order & Instructions

Please strictly follow the arrangement and order for the styling instructions in the css file.

From the top down:

navbar

breadcrumb

footer

homepage

what’s new

attractions

information

book now

The order of the instructions would be arranged in a top down, left to right manner just as how you would typically scroll down a webpage. The css instructions for the homepage in the css file for example, would be as follows:

carousel

section3
  op-hour3
  getting-here3
  facilities3
  promos3

section4
  promos4
  attractions4
  events4

about us

Styling instructions for the navbar, breadcrumb and footer is applied on all pages hence it will be up top in the css file so it should not be repeated in the styling instructions thereafter.

NOTE: Avoid using capital letters in the css file, and use hyphens instead. When naming classes or IDs for styling in css, try to make us of unique names specific to the page as sections such as “events” appear on more than one pages so if we have an .events class on the homepage, using .events again for another page will cause conflicts.

