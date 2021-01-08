# Foods

A responsive website that uses HTML, CSS, and JavaScript.  The site is made up of off 5 sections. 
A navbar, a header, a popular meals card section, a gallery, and a footer with a simple form.

## Demo

A demo of the site can be found at:  https://tod619.github.io/Foods/

## Sections

A brief description of each section starting from the header and ending at the footer.

### Navbar

The Navbar section icons are positioned with flexbox. The Navbar itself is positioned at the top of the site and it stays at the top as the user scrolls down the page. The Navbar is initially hidden from the user, but with a click of an icon it appears. The forEach method is used along with the toggle method to show/hide the navigation.  Each icon has a hover effect on it and css transiton is used to make sure that the animation appears smooth to the user.

### Section Heading

The heading section contains a heading and animated icons using css and javascript.  A set interval method is used to cycle through an array of icons and displays them one after the other.  Css tranistions are used to create smooth animation effects.

### Section Cards

The cards section has three cards that are displayed using flexbox. The section is fully responsive using flex-wrap which causes the cards to wrap on smaller screens.  A 3d effect is applied to the cards using the before and after pseudo selectors, the cards are also skewed on the X axis.  A hover effect is used along with a box shadow effect.

### Section Gallery

The gallery section is responsive with flexbox and contains six images.  A hover effect is applied to each image, when hovered on each image gets blury and scales up, also a heading and text description is display and the border increases.

### Section Footer

The Footer contains a simple form with an icon and information on who designed the site.

## Responsive

The site is responsive and displays on multiple different screen sizes.  The site was developed with a desktop first approach.  The site works on screens as small as 550px and bigger than 1400px.