# La Boulangerie

[View the live website here](https://michellegri.github.io/la-boulangerie/)

[GitHub Repo](https://github.com/MichelleGri/la-boulangerie)

![About image](README-files/about-image.JPG)

***

## About

The La Boulangerie website is based on a fictional bakery business in London. The website’s overall goal is to attract customers to the bakery and to make sales through online ordering. It aims to highlight the unique selling points of the bakery, make ordering easy and convenient, attract new customers, and encourage loyalty among existing customers. 

La Boulangerie began operating in 1998 and is an independent family-run bakery. It sells breads, sweet and savoury baked goods, desserts, cakes, and cold and hot drinks. The bakery prides in providing distinctly tasty food and beverages made from secret family recipes.

The target customers for the bakery are people looking for a wide variety of delicious freshly baked food in a single bakery, made from quality ingredients. Customers have the option to either ‘take away’ their order or there is seating available for customers who want to enjoy their food and/or beverages in the tranquil environment of the bakery. There is also an option to place orders online through popular delivery services – UberEats, Deliveroo, and Just Eat. To add convenience, a ‘click and collect’ service is also available, where customers are able to place orders online and collect it at the bakery.

The website provides a brief introduction to the bakery; information regarding the wide range of products available and prices; ways to order online; social media links; the bakery’s location, contact information (phone number, email address, and a form to send messages), and the business opening and closing days and times.

***

## Index - Table of Contents

* [User Experience (UX)](#user-experience)
* [Designs](#designs)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Known Bugs](#known-bugs)
* [Acknowledgements](#credit)

***

## User Experience (UX)

## Strategy
### User Stories

#### Reasons to visit the website

* A user looking for information regarding products sold by the bakery and their prices.
* A user wanting to place an order online for delivery or collection.
* A user looking to find out more about the bakery’s ambience and environment.
* A user looking for the bakery’s location.
* A user looking for the opening and closing days and times of the bakery. 
* A user wanting to send a message or provide feedback relevant to the bakery.

#### Aims of the website

* Increase customers
* Inform customers 
* Maintain loyalty among existing customers through encouraging repeat purchase
* Provide information regarding the products sold at the bakery and their prices
* Provide information for bakery location
* Provide information for bakery operating days and hours 
* Provide information to contact the bakery
* Provide information for the bakery’s social media pages

## Scope

#### User expectations
* Being able to easily navigate through the website
* Being able to easily place orders online
* Being able to easily find the menu and price list
* Visually appealing on different screen sizes
* Functions and links to be working as expected
* Find information about La Boulangerie bakery
* Find contact information, location, and business operating days and times
* Find links to social media pages
* Find special promotional offers and discounts

#### First Time Visitor Goals
* To be able to understand the primary purpose of the website and learn about the business
* To be able to easily place an order for delivery or collection
* To be able to easily navigate through the website and find content
* To be able to easily find a list of all products offered at the bakery and their prices
* To be able to find the location and operating days and times of the bakery

#### Returning Visitor Goals
* To be able to find and view the menu easily and quickly
* To be able to easily place orders online for delivery or collection
* To be able to find business operating days and hours
* To be able to contact the bakery through the contact us form and provide feedback and/or ask questions

#### Frequent User Goals
* Sign up for special promotional offers and discounts
* Create customer account to easily place orders online

#### As a developer / business, I want to provide
* A simple and easy to navigate website with all functions and links working as expected
* A comprehensive menu with prices
* A method to place orders online for delivery or collection
* Information regarding the bakery
* Photos of the bakery and the products sold
* An easy way to contact the bakery
* Information regarding the bakery location and business operating days and hours
* Links to social media pages


## Structure
The website consists of 4 separate pages:
* A Homepage with a hero-image, a brief about-us section, and a menu section
* A Menu page with a list of products and their prices, and links to online ordering options
* A Gallery page with photos of the bakery and its products
* A Contact Us page with a form, a map, address, phone number, and email address for the bakery


***

## Designs

## Surface

### Colour Scheme
The site was created with a very simple colour scheme of shades of blues and greys. It was important to use subtle colours on the site as the images are bright and vibrant. This ensures that the user is not overwhelmed by many and contrasting colours. A colour picker was used on this specific part of the hero image to select the colours:

![Colour image](README-files/design/colours-image.jpg)

Four colours were chosen for the colour palette using the website [Canva](http://canva.com/colors). The image below displays the four colours with their HEX, RGB, and CMYK values. HEX values have been used in style.css file. RGB value has been used for white to add opacity. 

![Colour scheme](README-files/design/colour-scheme.jpg)

* Midnight blue (#191970) – this colour is used for the logo and to highlight certain phrases on the about-us section. It is also used for the box-shadow effect on the ‘Order Online’ button. 

* Grape (#494454) – this colour is used for text on the site. 

* Light blue-grey (#CDDEEE) – this colour is used for the footer background, and the ‘Order Online’ button background. 

* White Smoke (#F0F0F0) – this colour is used for background of the whole site. 

The suitability of these colours for accessibility and readability purposes was checked using the contrast checker tool on the [WebAim](https://webaim.org/resources/contrastchecker/) website. 

The main background colour (#F0F0F0) was checked against the main text colour (#494454). The check was passed.

![Colour scheme](README-files/design/contrast-checker1.JPG)

The main background colour (#F0F0F0) was checked against the logo and emphasised text colour (#494454). The check was passed.

![Colour scheme](README-files/design/contrast-checker2.JPG)

The footer and 'Order Online' button background colour (#CDDEEE) was checked against the main text colour (#494454). The check was passed.

![Colour scheme](README-files/design/contrast-checker3.JPG)



### Typography

Three fonts were imported from [Google Fonts](https://fonts.google.com/) into the style.css file. These include 'Shadows Into Light', 'Poppins', and 'Manrope'.

[Shadows Into Light](https://fonts.google.com/specimen/Shadows+Into+Light?query=shadows+in) – this font was used for the bakery Logo only, which aims to add style and distinctiveness to the logo. 

![Font](README-files/design/shadows-into-light.JPG)

[Poppins](https://fonts.google.com/specimen/Poppins?query=poppins) – this font has been used for all headings.

![Font](README-files/design/poppins.JPG)

[Manrope](https://fonts.google.com/specimen/Manrope?query=manrope) – this font has been used for all other text.

![Font](README-files/design/manrope.jpg)

* Manrope and Poppins were chosen for headings and other text as they compliment each other and are easily readable. 

* Letter spacing has been included to almost all text to increase readability. 

* All fonts have been set to default to Sans-Serif font in case they are unable to load or be applied to the text. 

* A variety of font sizes have been used throughout the website to ensure text is in proportion to other elements on the page, such as images. 


### Imagery

The main hero-image on the homepage provides a simple combination to the bakery’s unique selling points – fresh, unique, prestige and quality. The brightly coloured fruits provide a vibrant energy, while the grey background adds depth to the overall site. The remaining images are of paintings and drawings to provide character to the bakery. This also provides consistency of images throughout the site. 

Since La Boulangerie is a fictional bakery, images on the Gallery page were taken from free images websites. However, the idea is for the Gallery page to display images of the bakery’s outside and inside environment, its products, and its customers. These images will inform the user of the bakery’s ambience, environment, quality and tasty products, and satisfied customers. 

Border of all images have been rounded to add style and subtlety. All images have “alt” attributes to ensure accessibility and enhance ‘search engine optimisation’. It also ensures there is a description of the image if it fails to load, and screen readers can describe images to user. 

#### Image Links

##### Homepage

* [Hero](https://pixabay.com/photos/cupcakes-fruits-dessert-food-1283821/)

* [Bakery](https://pixabay.com/illustrations/watercolor-paris-shops-bakery-5212789/)

* [Bread](https://pixabay.com/illustrations/bread-bakery-food-loaf-sandwich-6713845/)

* [Macarons](https://pixabay.com/illustrations/macarons-dessert-food-nutrition-7059669/)

* [Cake](https://pixabay.com/illustrations/cake-dessert-food-bakery-products-7070335/)

* [Coffee](https://pixabay.com/illustrations/coffee-cup-drink-art-abstract-2368790/)

##### Gallery page

* [Bakery-Woman](https://unsplash.com/photos/_Gd1biLbIU0)

* [Biscuits](https://unsplash.com/photos/upY7FPFfMNo)

* [Bread](https://unsplash.com/photos/IUk1S6n2s0o)

* [Cakes-Display](https://unsplash.com/photos/1WmlAiYgnoI)

* [Cakes](https://unsplash.com/photos/0uBlylsBuWk)

* [Cinnamon-rolls](https://pixabay.com/photos/to-bake-cakes-nut-wreath-pastries-5022110/)

* [Croissants](https://unsplash.com/photos/m9pzwmxm2rk)

* [Cupcakes](https://unsplash.com/photos/FIxdY7jOBus)

* [Donuts-box](https://unsplash.com/photos/c8ovzYe3z0s)

* [Eating-cake](https://unsplash.com/photos/n3Y2_Ohql28)

* [Kitchen](https://unsplash.com/photos/oWtV-CQcs1o)

* [Raisin-cake](https://unsplash.com/photos/29D6U5sZfjk)

* [Savouries-display](https://unsplash.com/photos/R3iAcQxylmE)

* [Shop-inside](https://unsplash.com/photos/RndRFJ1v1kk)

##### Menu

* [Uber-Eats-logo](https://images.app.goo.gl/YGU18qPjAAH8A9nF8)

* [Deliveroo-logo](https://images.app.goo.gl/SdtfqY78zQWdpyNt6)

* [Just-Eat-logo](https://images.app.goo.gl/eCh6si9yZTsrBagK6)

##### Contact Us

* [Pancakes](https://pixabay.com/illustrations/pancakes-strawberry-blueberry-7054658/)

### Logo

The logo was designed using the ‘Shadows Into Light’ font, imported from [Google Fonts](https://fonts.google.com/). This font gives a style and character to the logo to make it distinctive. The colour ‘midnight blue’ (#191970) was selected for the logo using the colour picker on the hero image. 

![Logo](README-files/design/logo.JPG)

### Call to Action

The main call to action on the website is the ‘Order Online’ button on header of every page. This leads user to Menu page which gives further details on how to make a purchase. The button is designed using the light blue-grey (#CDDEEE) colour as its background, which is the same colour used for the footer background. The corners have been rounded to match with all images on the site. The button outline colour is midnight-blue (#191970), which is the same colour as the Logo. There is a subtle box-shadow created that further emphasises the button. The text is all uppercase, in the colour grape (#494454), and the font is Manrope. There is a hover effect that makes the background colour white on hover. The hover effect enables the user to clearly see that this is a link.

![order-Online-button](README-files/design/order-online-button.JPG)

The ‘Send Message’ button on the contact us page is styled differently to the order online button. This is to ensure there are distinct differences between the two buttons so that they do not cause confusion. The background colour on the ‘Send Message’ button is grey, with white text. There is a hover effect that changes the background colour to white and the text to grey. The corners have been rounded to match with all images on the site.

![send-message-button](README-files/design/send-message-button.JPG)

## Skeleton

### Layout

* Layout of the site was designed with careful consideration to symmetry and spacing between all elements. The site follows symmetrical values of between 1 to 4 columns, depending on the device it is being viewed on. 

* The max-width for the entire site is set to 1500 pixels. This is to ensure the it displays well on larger screen sizes. 

* Media queries have been applied at different screen-width break-points to ensure responsiveness. DevTools has been used to determine the break-points, which are set at points where the layout begins to distort.  Elements on each page are stacked on top of each other as the screen width decreases. 

#### Wireframes

##### Homepage Wireframes

![Homepage Wireframes](README-files/wireframes/homepage-wireframes.JPG)

##### Menu Wireframes

![Menu Wireframes](README-files/wireframes/menu-wireframes.JPG)

##### Gallery Wireframes

![Gallery Wireframes](README-files/wireframes/gallery-wireframes.JPG)

##### Contact Us Wireframes

![Contact Us Wireframes](README-files/wireframes/contact-us-wireframes.JPG)

***

## Features

### Features on all pages

### Header 
The header appears on all four pages of the site and includes the company logo, an 'order online' button and the navigation bar. The bakery logo is on the left side of the header, which returns user to the homepage when clicked. There is an ‘order online’ button in the center which enables user to easily find out how to place an online order. This button is linked to the Menu page. The website navigation bar is on the right side of the header, which enables user to easily move between pages without having to use the ‘back’ function. It includes links to all four pages of the site: Home, Menu, Gallery, and Contact Us. The header is responsive on multiple screen sizes. The 'order online' button and the navigation bar move to under the logo on small screens, such as tablets and mobile devices. 

![header](README-files/features/header.JPG)

### Footer
The footer is featured on all four pages of the site. It is identical on all pages and appears at the bottom of the page. There are three sections included within the footer:

* Opening Times – this section gives information regarding the business opening and closing days and times. This is important as customers need to be aware of when to visit or order online from the bakery. 

* Contact Us – this section lists the bakery phone number and address. 

* Social Media – this part of the footer provides links to the bakery’s social media platforms – Facebook, Twitter, and Instagram. This encourages users to stay connected and interact with the bakery. These pages enable the business to advertise the bakery and announce promotional offers, discounts, and events. The social media icons are clickable links to the relevant page which opens in a new tab.  As La Boulangerie is a fictional business, the links currently lead to the social media website homepage.

![footer](README-files/features/footer.JPG)

### Specific Features

### Homepage

#### Image 
The landing page image is a photo of four cupcakes lined up horizontally. It aims to capture the visitors attention and encourage them to investigate further. The vibrant yet subtle colours on the main image, set against a light grey background colour, intend to entice the user to visit or order from the bakery. The fruits on the main image give the impression of freshness and well-being. 

![Homepage Image](README-files/features/homepage-image.JPG)

#### About Us
Set in the middle of the page, this section aims to provide a little information about the bakery. It informs the user that the bakery is based in London and began operating in 1998. The ‘cakes and croissants’ and ‘sweet and savoury’ words have been highlighted in blue (the company logo colour) to place emphasis that the bakery is able to cater for the needs of people wanting to consume either sweet or salty baked goods. The image on the right is a watercolour painting of the bakery from the outside. This aims to give the bakery a character and sense of ‘old-fashioned’ heritage. 

![About Us Section](README-files/features/about-us-section.JPG)

#### Bakery Menu
The bakery menu is located at the bottom of the landing page. It presents four images of different types of products sold at La Boulangerie: Breads and Savouries, Sweets and Desserts, Cakes, and Drinks. Each of the images and product categories link to the relevant part of the section on the main bakery Menu page. There is a hover effect on the bakery category images which aims to add interest in the website. The effect includes the names of the categories set on a white background with an opacity so that the image below is slightly visible on hover. 

![Menu Section](README-files/features/menu-section.JPG)

### Menu Page

The Menu page includes a list of products sold at the bakery and their prices. As La Boulaungerie is a fictional business, the products and prices are invented. The products are presented in four categories: breads and savouries, sweets and desserts, cakes, and beverages. This page has a very simple design layout without any images or colours. This is to ensure the user is able to clearly see the products and price list, without being overwhelmed by images or colours. 

Each product category has two horizontal panels with a list of 10 products on each panel. The category heading is placed on top of the left panel, and options for online ordering are placed on top of the right panel. The online ordering options include icons to popular food delivery services – UberEats, Deliveroo, and Just Eat. These appear next to each product category heading. They are clickable links that open in a new tab. As La Boulangerie is a fictional bakery, the links currently open on the delivery service website homepage. There is also a ‘click & collect’ option included next to the delivery options. This is also a clickable link that directs the user to the Contact Us page.  

![Menu Page](README-files/features/menu-page.JPG)


![Menu Page](README-files/features/menu-page1.JPG)


![Menu Page](README-files/features/menu-page2.JPG)


![Menu Page](README-files/features/menu-page3.JPG)

### Gallery Page

The gallery page includes 14 photos relevant to the bakery, presented in a masonry style. This pages aims to give the user an idea of the bakery’s environment and the products sold. Its purpose is to convince the user to visit or order online from the bakery and have an enjoyable experience. The user is able to visualise the bakery and therefore set their expectations accordingly. 

![Gallery Page](README-files/features/gallery-page.JPG)

### Contact Us Page

The contact us page includes two panels. There is a background image of pancakes in watercolours. This gives the page a nice touch and adds interest. 

#### Contact Us

The left panel enables user to complete a short and simple form with their name and contact details, and to send a message to the company. There is also a question that allows user to either opt-in or opt-out to the mailing list to receive email newsletters, offers and vouchers. The name, phone number, and email address inputs are set to required so that user is unable to send a message unless these fields have been completed. The message/feedback input field is set to optional. By default, the option to opt-in or opt-out of the mailing list is set to ‘No’. This is to avoid anyone being accidently added to the mailing list if they do not wish to do so. Sending a message will result in the user being informed that their message has been sent and someone will be in contact with them shortly. However, as this website is for educational purposes only, submitting a message currently leads to the formdump.codeinstitute.net page. 

![Contact Us Page](README-files/features/contact-us-left.JPG)

#### How To Find Us

The ‘How to Find Us’ panel is on the right side of the page and includes a google map of the bakery’s location, the bakery address, phone number, and email address. The map includes a ‘View larger map’ and 'directions' links. These open the Google map wesbite in a new tab where the user can input their own postcode to receive travel instructions to the bakery.

![Contact Us Page](README-files/features/contact-us-right.JPG)

### Future pages and features 

#### Company History

A ‘Company History’ page can be included to provide more information about the company’s history – how it all began and its evolution. This may include a section about the company values, its involvement in the community, and sourcing of its ingredients. 

#### Cake Orders

A page can be created that enables customers to order cakes for birthdays, weddings, and other special occasions. This may provide the user with an option to choose from a variety of cakes and include a personalised message on the cake. Another option can be included for the user to send a message or call the bakery to discuss any specific needs. 

#### Customer Account

A ‘Customer Account’ page can be added that will enable the customers to login to their account while making purchases online. The ‘Click & Collect’ option can direct the customer to their personal account where they can place orders easily. This may be accompanied with an account card that can be used at the bakery to accumulate points and receive special offers and discounts. 

#### Gallery Page

The Gallery page can be further developed to add captions and descriptions of the images. It can be updated regularly with images of new products, and any events taking place at the bakery. 

#### Menu Page

The Menu page can be further developed to include images and descriptions of products.

#### Special offers / promotions / events page or feature

A page or feature can be created that includes special offers, promotions, discounts or any events happening at the bakery. 

#### Navigation menu collapses on mobile devices

To assist the navigation menu responsiveness on mobile devices, a feature can be added that collapses the navigation on mobile devices. 

***

## Technologies Used

* HTML5 – used to mark-up the website using semantics
* CSS3 – Cascading Style Sheets was used to create style
* Gitpod.io – creating the website by writing code; creating a progress log by making commits using the command line and pushing to GitHub
* GitHub – create a project repository

#### Design

* [Google Fonts](https://fonts.google.com/)– for styling the typography 
* [Balsamiq Wireframe](https://balsamiq.com/) – to create wireframes
* [Font Awesome](https://fontawesome.com/) – for social media icons
* [Canva](https://www.canva.com/) - for colour scheme and image editing
* Microsoft Paint 3D – to resize and crop images 

#### Testing 

* [HTML Validator](https://validator.w3.org/) – testing validity of HTML code
* [CSS Validator](https://jigsaw.w3.org/css-validator/) - testing validity of CSS code
* [Am I Responsive](http://ami.responsivedesign.is/#) – checking responsiveness of the site
* [Wave](https://wave.webaim.org/) - checking accessibility of the site
* [Browser Stack](https://www.browserstack.com/) - checking browser compatibility
* DEV Tools – Lighthouse check and responsiveness check on various screen sizes
* Microsoft Excel - to create testing plan and instructions

***

## Testing

The website was tested by the developer, specific testing methods and tools, and other people. This was done to ensure the website is in working order and performs as expected. The following checklist includes a plan and instructions for steps carried out for testing.

![Testing plan and instructions](README-files/testing-plan.PNG)

### Checks carried out by the developer

* Navigations links are linked to corresponding pages and direct user to relevant page.
* Logo on each page directs user back to homepage.
* Order online button directs user to Menu page.
* Bakery menu images and categories direct user to relevant section on Menu page.
* Links to online delivery services are working and direct user to the delivery service website homepage which opens in a new tab.
* Links to ‘click and collect’ are working and direct user to Contact Us page.
* Contact us form is working as expected. User is unable to send a message without completing all required inputs. 
* Message is not sent if incorrect email format in entered in contact us form. 
* Sending a message with completion of all required inputs opens a new tab with comfirmation of form/message sent.
* The google map is working as expected. It opens in a new tab with an option for the user to input their own postcode to receive directions.
* Links are styled to the main grey text colour, and are not blue.
* Hover over effects on all relevant elements are working as expected.
* Social media links are working as expected. They open in a new tab and direct the user to the relevant social media homepage.

### Usability Testing

The website link was sent to a number of family and friends to check its usability. These individuals were given the same checklist of tests carried out by the developer. They were asked to also provide feedback on the following aspects of the website: 

* Easy to navigate through the website
* All links are working as expected
* User-friendly design layout
* Ability to find relevant information
* Easy to understand the website content and the business
* Readability and visibility of text and elements on different screen widths and devices
* Any specific comments / feedback regarding the overall experience

All individuals gave positive responses and a few highlighted some issues to be considered: 

* Remove 'order online' button from menu page as it is not necessary. One person thought the link was not working as it was not directing to another page or section. This suggestion has been implemented. 

* The 'click and collect' links direct the user to Contact Us page but there are no further instructions given on how to order. This issue has not been resolved as it is not within the scope of the project at this stage. One method of resolving this issue would be to direct the user to a customer account page, where further instructions can be given on how to place an order. Another option is to create a page that gives detailed instructions and options on how the user can place an order, for example - by calling the bakery. 

### HTML Validator

The [W3c Markup Validation Service](https://validator.w3.org/) was used to check validity of HTML markup of all four pages of the site. The results are displayed below.

Homepage

![Homepage HTML](README-files/validation/homepage-html.JPG)

Menu Page

![Menu Page HTML](README-files/validation/menu-html.JPG)

Gallery Page

![Gallery Page HTML](README-files/validation/gallery-html.JPG)

Contact Us Page

![Contact Us Page HTML](README-files/validation/contact-us-html.JPG)

### CSS Validator

The [W3c CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to check validity of CSS code. The results are displayed below.

![CSS Validation](README-files/validation/css-validation.JPG)

The warning refers to the import of Google Fonts into style.css. However, this does not cause any significant issues to functioning of the site. 

### Am I responsive?

The [Am I responsive](http://ami.responsivedesign.is/#) checker was used to test the responsive nature of the site's pages.

![Homepage Responsiveness](README-files/responsiveness/homepage-responsiveness.JPG)

![Menu Responsiveness](README-files/responsiveness/menu-responsiveness.JPG)

![Gallery Responsiveness](README-files/responsiveness/gallery-responsiveness.JPG)

![Contact Us Responsiveness](README-files/responsiveness/contact-responsiveness.JPG)

### Lighthouse Test

The Lighthouse Test on Developer Tools was used to test specific aspects of the website on desktop and mobile devices. The site scored well on all pages for desktop and mobile. The lowest score achieved was for performance on Contact Us page. This is due to the Google Map included on this page. However, further investigation revealed that the map is clearly visible and working as intended on mobile devices and therefore this is not considered a significant issue to require further attention. 

#### Desktop

![Desktop Homepage](README-files/lighthouse/desktop-homepage.JPG)

![Desktop Menu](README-files/lighthouse/desktop-menu.JPG)

![Desktop Gallery](README-files/lighthouse/desktop-gallery.JPG)

![Desktop Contact Us](README-files/lighthouse/desktop-contact.JPG)

#### Mobile

![Mobile Homepage](README-files/lighthouse/mobile-homepage.JPG)

![Mobile Menu](README-files/lighthouse/mobile-menu.JPG)

![Mobile Gallery](README-files/lighthouse/mobile-gallery.JPG)

![Mobile Contact Us](README-files/lighthouse/mobile-contact.JPG)

### Wave Test

The [Wave](https://wave.webaim.org/) (Web Accessiblity Evaluation Tool) was used to test accessibility of all pages. There is 1 Alert appearing on tests for all pages which refers to the presence of two adjacent links on the header that lead to the homepage - Logo and Home on the navigation bar. Since this is an intentional design element, it is not considered a significant alert to reqiure attention. 

#### Homepage

![Wave Homepage](README-files/wave/wave-homepage.JPG)

#### Menu Page

Four of the Alerts on this page refer to the use of the word 'click' in reference to the 'click & collect' links. However, these alerts mainly refer to vague and ambiguous links that ask users to "click here". Since the links on this page are specific and clear, it is not neccessary to change this aspect. 

![Wave Menu Page](README-files/wave/wave-menu.JPG)

#### Gallery Page 

![Wave Gallery Page](README-files/wave/wave-gallery.JPG)

#### Contact Us Page

One of the Alerts on this page refers to the lack of a 'legend' for the radio input field on this page. However, as there are only two options on this field, a legend is not considered necessary. 

![Wave Contact Us Page](README-files/wave/wave-contact-us.JPG)

#### Browser Compatibility

The site was tested on Chrome, Firefox, Internet Explorer, Microsoft Edge, and Safari. The developer carried out manual tests by installing theses browsers and checking the site's compatibility. In addition, the [Browser Stack](https://www.browserstack.com/) website was also used. However, the free version of Browser Stack allows for 1 minute of usage only on each browser. The tests revealed that the site is compatible with all Chrome, Firefox, and Microsoft Edge browsers. The site images appear as different sizes on older versions of Safari and Internet Explorer. However, the content is readable and the user is able to navigate through the website.

#### Testing User Stories

* A user looking for information regarding products sold by the bakery and their prices.

A user is able to locate this information on the Menu page. There are links to the Menu page on the header navigation bar of each page. A user can also find links to the Menu page at the bottom of the landing page. The Order Online button also directs user to the Menu page.

* A user wanting to place an order online for delivery or collection.

There is an 'Order Online' button on every page (except for Menu page) which directs user to the Menu page. There are further options on the Menu page to either order from a delivery service, or for collection from the bakery.

* A user looking to find out more about the bakery’s ambience and environment.

The gallery page displays images of the bakery. This gives the user a sense of the ambience and environment of the bakery.

* A user looking for the bakery’s location.

The bakery's address is on the footer which appears on every page. The contact us page includes information regarding the bakery's location. There is Google map that can be used to find directions. 

* A user looking for the opening and closing days and times of the bakery. 

The footer provides information regarding the bakery's opening and closing days and times.

* A user wanting to send a message or provide feedback relevant to the bakery.

There is a form on the Contact Us page where the user can input their personal information with a message and/or feedback. The bakery's email address is also included on the Contact Us page.

***

## Deployment

### Adding and Committing files in GitPod

To add files to the repository:
Type ‘git add .’ in the command line
Type ‘git commit -m “This is the commit message” 
Type ‘git push’

The git commit message should clearly describe the changes made. 

Pushing will send all work to the GitHub repository and automatically update changes made in GitPod to the deployed website. 

### Deployment

The steps below were followed to deploy this project:

* Logged into GitHub
* Clicked on the drop-down menu on the right top corner
* Clicked on ‘Your repositories”
* Clicked on the la-boulangerie repository
* Clicked on the Settings tab above the repository
* Clicked on the Pages link on the left side menu
* Under the “Source”, selected None from the dropdown menu and then selected “Master Branch”
* The page refreshed and a link to the deployed website appeared
* Clicked on the link to open the deployed website

## Known Bugs

* There was no space between the footer and the ‘beverages’ menu section on the Menu page. The bug was fixed by adding a margin-bottom to the ‘beverages’ id. 

* Links to specific sections on Menu page from the homepage menu section were opening with no space above the category heading. The bug was fixed by adding a padding on top of the headings. 

* There are no other known bugs.

***

## Acknowledgements

### Credit

Brian Macharia - I would like to thank my mentor Brian Macharia for his valuable feedback and suggestions. His guidance enabled me to plan and execute the project. 

Tutor Support – I would like to thank the various tutors at the Code Institute tutor support for assisting me in solving problems and issues. 

#### Media

[Kevin Powell](https://www.youtube.com/kepowob) – YouTube Channel – for providing valuable videos on various HTML and CSS topics, particularly CSS grid and flexbox

[Traversy Media](https://www.youtube.com/c/TraversyMedia) – YouTube Channel – for providing informative videos on various HTML and CSS topis – particularly CSS grid and flexbox

[Stack Overflow](https://stackoverflow.com/) – for trouble shooting and resolving code issues

[Google Fonts](https://fonts.google.com/) – for fonts used throughout the website

[Google Images](https://www.google.co.uk/imghp?hl=en&ogbl) - for delivery services logos

[Font Awesome](https://fontawesome.com/) – for social media icons

[Canva](https://www.canva.com/) – for choosing a colour scheme

[Pixabay](https://pixabay.com/) - for free images taken from Pixabay

[Unsplash](https://unsplash.com/) - for free images taken from Unsplash

[Balsamiq wireframe](https://balsamiq.com/) – for creating wireframes in the design process

[W3school](https://www.w3schools.com/) – for HTML and CSS coding information and trouble shooting

[HTML Validator](https://validator.w3.org/) – for testing validity of HTML code

[CSS Validator](https://jigsaw.w3.org/css-validator/) – for testing validity of CSS code

[Am I Responsive](http://ami.responsivedesign.is/) – for checking responsiveness on different screen sizes

[Wave](https://wave.webaim.org/) - for checking accessibility of the site

[Browser Stack](https://www.browserstack.com/) - for checking browser compatibility

***

### Content

Code and Content (not already attributed): Michelle Griffiths










