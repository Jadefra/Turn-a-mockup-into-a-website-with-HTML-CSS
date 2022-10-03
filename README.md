# Turn a mockup into a website with HTML & CSS

I was in charge of creating this prototype by integrating the model in HTML and CSS.

![Capture d’écran 2022-09-29 à 17 30 57](https://user-images.githubusercontent.com/91191428/193087995-474dd5e3-2fc7-4602-848d-8e311859a000.png)

The website is responsive (adapts to phone screens)

### Functional Specifications : ###
- Users will be able to search for accommodation in the city of their choice. The search field is an input field, so the text should be able to be edited by the user. This field is in a form for it to be valid with the W3C. The search part does not work at the moment.
- Each accommodation or activity card is clickable in its entirety (not just the title). For now, the links are empty. We used an attribute `href=”#”` to simulate the presence of a link.
- Filters change appearance on hover.
- The texts “Hébergements” and “Activités”, located in the header, are links. They lead respectively to the “Accommodation in Marseille” and “Activities in Marseille” sections.

### Technical specifications : ###
- The site is also suitable for tablet formats. For the tablets, I was free to make the necessary adaptations. No element is cut, and the text has a sufficient size.
- Regarding breakpoints, we agreed with the client to use 992 px and 768 px.
992px for computer screens and 768px for tablets, and anything below 768 for mobile phones.
- The use of Media Queries will allow us to realize
integration for different media.
- The icons are from the Font Awesome library. We went through a CDN to make it easier to load the icons.
- Chart colors are blue (#0065FC), a lighter version clear of this blue (#DEEBFF) and gray for the background (#F2F2F2).
- The site font is Raleway.
- Use of pixels and percentages rather than REM and EM.
- Using Flexbox rather than Grid.
- No CSS framework (BootStrap or Tailwind CSS type) or CSS preprocessor (Sass or Less type) was used.
- Use of semantic tags (type `main`,`header`, `nav`, etc.).
- The code is valid for W3C HTML and CSS validators.
- The mockup is compatible with the latest versions of Google Chrome and Mozilla Firefox.
- The code complies with W3C validators (HTML and CSS).

# Steps

### Step 1: Set up the environment development ###
- Start the project in good conditions by installing a solid and rigorous development environment, as well as the files necessary for our development.
- Added CSS box-sizing property
- Added meta charset and viewport
- Added a normalize.css file
- Import fonts from Google Font
- Added FontAwesome integration
### Step 2: Cut out the model using a paper and a pencil ###
- Before starting to code, structure the project by drawing the large sections of the Booki mockup for easy integration
### Step 3: Integrate the "Header" of the project ###
- Integrate the desktop version first before making the versions tablet then mobile
- Use Flexbox to achieve the positioning between the Booki logo and the Accommodation/Activities sections
### Step 4: Adding the search form ###
Integration of the search bar of the page using a form
- Playing with “absolute” positioning and “relative”
- Use “display: none” to show or hide HTML content
- The style of the search bar: on desktop, the button search includes the text “Search” while on mobile, it is a magnifying glass
- Some of the border radii change depending on the version, mobile or desktop
### Step 5: Adding the Filters part ###
- Use only Flexbox
- Use Flexbox both to include all the filters, and to inside each filter.
- Use flex-wrap to manage the positioning of elements.
- Use a margin property rather than padding.
- Use pixels instead of percentages for margin and padding values.
### Step 6: Make the “card” present in “Hébergements à Marseille” ###
- Realize the design of the "card" "Auberge La Cannebière”. In the next step, I took care of the one contained in the "Les plus populaires" section, before finally tackling to the layout of all these elements.
- The `object-fit` CSS property can be used to adjust the size from the image to its container.
- Give a fixed size for the cards.
- Margins and paddings, favor the percentages.
- Images are embedded via HTML with alt attributes.
### Step 7: Make the “card” present in “Les plus populaires” ###
- There are border radius on the images
### Step 8: Manage container display “Hébergements à Marseille” and “Les plus populaires” ###
- Use flex and percentages to manage display rules. The ratios are one-third and two-thirds. Turn that into percentages.
- First make the layout between the two containers before tackling the interior layout in each of the containers.
- First add each of the cards in each of the containers before doing the layout.
- The background colors are reversed between the mobile version and the desktop
### Step 9: Integrate the “Activités à Marseille” container ###
- Integrate containers of different sizes.
- Once the height and layout of each of the containers is satisfactory, I was able to add the images and the texts
### Step 10: Implement the footer ###
- Integrate the footer with its many connections.
- `ul` to make the links, I had by default a padding-left
### Step 11: Check the quality of your code ###
- Check that the code complies with W3C validators(HTML and CSS).
- Use the kebab case, for example `.main-wrapper`. It's here most common CSS convention.

# Skills
- Integrate content according to a model
- Implement a responsive interface
