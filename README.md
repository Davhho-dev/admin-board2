# Admin Dashboard
Admin Dashboard based on The Odin Project (TOP) Dashboard project. 
<br>
<br>

## Goal
___

To create an admin dashboard utilizing CSS Grid. 
<br>
<br>

## Process of Creating Admin Dashboard
----
I created the first admin dashboard but was not impressed by the overall way the code was written and layout, so I remade the admin dashboard via admin-dashboard2.

The first step of creating the dashboard was creating all of the elements and setting up each of the specific containers that was going to be used for the dashboard (e.g. Top navigation bar, Side navigation bar, and the main content section - consist of the project cards, announcement and trending section).

Once the overall elements were created, CSS Grid was utilized to create the layout of the dashboard.

Flexbox was essential in creating the layout for the top and side bar navigation.

The main content section utilized nesting CSS Grid. 
<br>
<br>

## Problems
---

1. Icons
<br>
a. Material Design Icons were used during the first iteration of the creation of the admin dashboard. However, ended up utilizing Google Material Symbols for consistency sake, as Google Fonts was also utilized.
<br>

2. Color Scheme
<br>
a. Originally used the color scheme that was presented by TOP. However, chosed a different color scheme: Primary - `#6DA187` and Secondary - `#fd9698` as I preferred the feel of pastel colors. 
<br>
<br>
![TOP Admin Dashboard](https://cdn.statically.io/gh/TheOdinProject/curriculum/43cc6ab69fdfbef40d431a65677d2144668930ac/intermediate_html_css/grid/project_admin_dashboard/imgs/dashboard-project.png)

3. Profile Icons
<br>
a. Utilized Material Design Icons for the account photos but it didn't fit the overall feel of the dashboard. Used images of 3D illustrations located on Behance.net where the color palette of the illustration felt more appropriate with the color scheme of the dashboard.
<br>
<br>

4. Sidebar Content
<br>
a. Upon completing the layout of the sidebar and admin dashboard, I felt that the sidebar was plain. While the dashboard is not interactive, as the sole purpose is to recreate an admin dashboard and not create a **functionable** dashboard, I decided to add styling when the user hover's over the links. 
<br>
<br>
b. The biggest problem was resolving the issue of shifting when hovering over the link.
<br>
The shifting of the element was due to the padding of the border created when hovering over the link, thus the border padding had to be implemented on the original element but have the color be transparent
<br>
`border-left: 5px solid transparent`
<br>
Then it was possible to add the same code to the element via pseudoclass `:hover` but add color: `border-left: 5px solid var(--secondary-color)`


## Credits
---

- Typefont used - Roboto
https://fonts.google.com/specimen/Roboto

- Icons used during first iteration of dashboard creation - Material Design Icons
https://materialdesignicons.com/

- Icons used during finalization of dashboard creation - Google Material Symbols
https://fonts.google.com/icons

- 3D illustrations used for account photos - Artist: UV- 朱
https://www.behance.net/qr3125
<br>
<br>
Albums: 3D fashion-Summer shows
https://www.behance.net/gallery/100089591/3D-fashion-Summer-shows
<br>
<br>
Albums: 米兰世纺会-艺术装置
https://www.behance.net/gallery/87013707/_

