# My City | Cluj Napoca

This is the website I created to promote my city. Cluj Napoca is a city in full development both economically and tourist, with a rich historical heritage. Transylvania is an area full of vampire legends and Cluj Napoca is no exception. As a visitor you will discover in the heart of Transylvania a multitude of ancient tourist attractions, local traditions dating back centuries, but you will also discover local gastronomy, famous festivals throughout Europe as well as warm people and ready to welcome guests.

Potential readers will find out new things about this part of Transylvania and photos and video images will make them at least curious to visit the city. The project was made possible with the support of Cluj Napoca City Hall.

> ## Contents
* [UX](https://github.com/iulianpro/my-city#ux)
    - [User stories](https://github.com/iulianpro/my-city#user-stories)
    - [Strategy](https://github.com/iulianpro/my-city#strategy)
    - [Scope](https://github.com/iulianpro/my-city#scope)
    - [Structure](https://github.com/iulianpro/my-city#structure)
    - [Skeleton](https://github.com/iulianpro/my-city#skeleton)
    - [Surface](https://github.com/iulianpro/my-city#surface)
* [Features](https://github.com/iulianpro/my-city#features)
    - [Existing Features](https://github.com/iulianpro/my-city#existing-features)
    - [Features Left to Implement](https://github.com/iulianpro/my-city#features-left-to-implement)
* [Technologies Used](https://github.com/iulianpro/my-city#technologies-used)
* [Testing](https://github.com/iulianpro/my-city#testing)
* [Deployment](https://github.com/iulianpro/my-city#deployment)
* [Credits](https://github.com/iulianpro/my-city#credits)
    - [Content](https://github.com/iulianpro/my-city#content)
    - [Media](https://github.com/iulianpro/my-city#media)
    - [Acknowledgements](https://github.com/iulianpro/my-city#acknowledgements)

> ## UX

### User stories
The visitor will discover on this website a city about which they may not have heard before, loaded with history, legends, places to visit, festivals and it is addressed to people who are passionate about travel, adventures, eager to discover new places. The website offers them a starting point, then will interest them in the future to visit and discover The Heart of Transylavania, Cluj Napoca.

As a user, I want to:
* that when accessing the website, to see a landig page that will arouse my curiosity to navigate further;
* to find out new information about a future holiday destination;
* to see pictures and video images with the location described to give me an opinion about this city;
* to can send a message if I want to find out more details about this location;

As a owner I want to:
* make known to the public the existence of a city that can be a perfect destination for a city break for example;
* the visitor can access the photos and watch the video clip to know the city;
* receive messages from users when they send one using the contact form

### Strategy
My goal was to create a minimalist and user-friendly website as possible, to present the city of Cluj Napoca, a starting point for the user to find out about this place.

### Scope
For the user, I wanted to provide some brief information that will arouse the interest of visiting this city.

### Structure
The main structure of the site comprises five sections, modals for images gallery, a few links to the external pages of the institutions that supported this project, as well as to their social media pages, a video inserted with iframes and a contact form. The navbar is positioned at the top and is fixed, so it can be viewed even when scrooling. For a more enjoyable browsing experience, I used ```html {scroll-behavior: smooth;}``` so that navigating from one section to another would be smooth. Also, the left side of the navbar contains the website name and a logo created with Font Awesome. In small screens, the navbar will collapse into a "hamburger" icon. When the icon is clicked, the navbar will expand and show the whole menu.

The main image has a backwards transform scale animation for an attractive design. The images in the About and Contact sections have a transition on hover, also for a special design.

Also, the images in the Gallery section, besides the modal use for viewing, have a grow shadow on hover effect to indicate to the user when selecting a certain image. This effect was made possible by importing an external Hover.css library as I showed below.

For the video section, I used a video presentation of the city of Cluj Napoca produced by the Lazar company for the Cluj Napoca City Hall after obtaining its takeover agreement, which I can make available if necessary.

The Contact section is a live one, meaning that the user can send a message by entering their first name, last name, email address and some message. The data is retrieved by an external server hosted by mailchimp.com, where I have a free user account. Also, after the user presses the send button and sends the message, he is redirected to the contact.html page which displays a successful message sent. This page is a clone of the main page from which the previous sections were deleted.

### Skeleton
The website has been structured in one single page with five simple and concise sections, plus landing page, footer and succesfully message sent, contact.html page, that will arouse the user's curiosity to document about this land of legends and, why not, to visit it. The wireframes can be viewed here: 
* [Landing Page](wireframes/landing-page.jpg); 
* [About Section](wireframes/about-section.jpg);
* [Visit Section](wireframes/visit-section.jpg);
* [Gallery Section](wireframes/gallery-section.jpg); 
* [Video Section](wireframes/video-section.jpg);
* [Contact Section](wireframes/contact-section.jpg);
* [Footer](wireframes/footer-section.jpg);
* [Contact Page](wireframes/succ-contact-section.jpg).

### Surface
The color scheme chosen by me is also a minimalist one. The main color used is # 782b1e, which was extracted from the main image using Adobe Color tool.


> ## Features
This initial version of the website has some brief features so that the user can find general information about Cluj Napoca. In the future, the website will offer more functionalities such as a section with a more detailed presentation of the places to visit but also others that I have detailed below.

### Existing Features
* **About** - In this section, the reader meets the city of Cluj Napoca, learns some details regarding history, tourist attractions, important cultural events, as well as emblematic tourist locations for the area.
* **Visit** - This section presents brief information on the existence of the airport, medieval tourist attractions, festivals in the city, local gastronomy, about the strange forest on the outskirts of the city, as well as on the cafes in the city.
* **Gallery** - A rich gallery with pictures from the city, will awaken the reader's imagination and desire to explore more.
* **Video** - This short video presentation of the city will have the greatest impact, it offers the user a close contact with the reality of the city, with everything he can discover.
* **Contact** - This section is live, let the user send a message.

### Features Left to Implement
As I said above, in the future the website will include more functionalities such as a section with a more detailed presentation of places to visit, an interactive map with their location, accommodations, restaurants, caffee shops, various events, but and other features.


> ## Technologies Used
To create this website, several technologies were used, as well as some frameworks, libraries and tools detailed below:
* HTML
* CSS
* [Bootstrap](https://getbootstrap.com/)
* [jQuery](https://jquery.com/)
* [Popper.js](https://popper.js.org/)
* JavaScript
* [Hoover CSS](http://ianlunn.github.io/Hover/) by [Ian Lunn](https://ianlunn.co.uk/)
* [Font Awesome](https://fontawesome.com)

Also, the following tools were used:
* Compress images with [Tinyjpg](https://tinyjpg.com/)
* Crop and resize images with [Iloveimg](https://www.iloveimg.com/crop-image)
* Convert image to ICO file with [Hnet](https://hnet.com/png-to-ico/)
* Extract color palette from image with [Adobe Color](https://color.adobe.com/create)
* Pick colors with [Eye Dropper](http://eye-dropper.kepi.cz/) Chrome extension
* Import Fonts from [Google Fonts](https://fonts.google.com/)
* Simple wireframe maker with [Wireframe](https://wireframe.cc/)
* [HTML Validator](https://validator.w3.org/)
* [CSS Validator](https://jigsaw.w3.org/css-validator/)
* [CSS Autoprefixer](https://autoprefixer.github.io/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Git](https://git-scm.com/) installed on local device
* [GitHub](https://github.com/) for host the deployed website and repository of all versions
* Testing with [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/)
* Testing with [Cross Browser Testing](https://app.crossbrowsertesting.com/test-center)
* Learned from [W3schools](https://www.w3schools.com/)


> ## Testing
The website was tested both after the creation of each section separately but also after its completion. I tested all the functionality in the main browsers that ran on several operating systems: Chrome, Firefox, Opera, Microsoft Edge, Safari, Dolphin, in Windows 10, Mac OSX 10.14, Android and iOS operating systems, both physically on different personal and friends' devices, as well as the [Cross Browser Testing tool](https://app.crossbrowsertesting.com/test-center). For full responsiveness, for the whole site, I used Bootstrap 4.4.1.

Testing during section construction was done primarily with Chrome DevTools, making sure each element works correctly and optimally, including responsiveness across devices. For navbar, I tested the functionality of all links, including the site brand. I also tested the color change of links to hover and toggle and collapse functioning in small devices. I also tested the functionality of the animated background, which I created with the Love Running project as a model. During the tests, I noticed that background-attachment: fixed; is not functional in the iOS Safari browser. To fix the problem, I used in media query ```@media (max-width: 992px) {.callout-img, .bg-design {background-attachment: scroll;}}```. After a new test, the respective browser displays the background image.

The **About** section launched the challenge of disproportionality between the image on the left and the text on the right in different screens, which is why in medium and large screens, I chose to hide 1 paragraph. Also, I also tested the functionality of the transition effect transform scale 1.1 of the image.

The **Visit** section has been tested to verify responsiveness across devices and resolutions.

The **Gallery** section has been tested to verify the optimal functioning of grow shadow on hover, modal functionality, display of the closing icon over the modal image as well as the responsiveness across devices. I found that in some browsers less important, the close icon is not displayed. Unfortunately for this problem, I did not identify a solution.

For the **Video** section I tested the functionality of playing video images displayed on the website using iframes as well as responsiveness.

In the **Contact** section, I tested the optimal functioning of the fields, first name, last name, email and textarea, as well as changing the color of the box on hover, the optimal functioning of the "Send" button, blocking the sending of data if the fields are not completed or the email is completed incorrectly, all fields being required, the functionality of transmitting the collected data to the mailchimp.com server, as well as redirecting the user to the contact.html page, which displays a successful message sent. For the moment, the user can send a single message from the same email address. If it sends the second message, the mailchimp.com server will display an error message. The functionality will be developed in a future version of the website.

The **Footer** has been tested to verify responsiveness across devices, the optimal functioning of both internal and external links. External links open in a new page so that the user does not leave the page on which they are located. The "Insta Feed" subsection is dysfunctional and was created to balance footer content on large screens. Also, it is only displayed on the screens lg and xl.

I also tested the website for HTML and CSS code validation with [HTML Validator](https://validator.w3.org/) and [CSS Validator](https://jigsaw.w3.org/css-validator/).

The results of the tests performed with [Cross Browser Testing](https://app.crossbrowsertesting.com/test-center) can be consulted below:
* [iPhone 11 Pro / Mobile Safari 13](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35088253/5e97584b)
* [Android / Opera Mobile 42](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35088175/7bc2afe8)
* [Android / Firefox Mobile 53](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087947/638e0607)
* [Android / Dolphin Mobile 11.5](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087861/0816b09c)
* [Android / Chrome Mobile 58](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087649/3d533aff)
* [Mac OSX 10.14 / Safari 12](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087451/6b686933)
* [Windows 10 / Google Chrome 79](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35086819/3dfadd4a)
* [Windows 10 / Opera 63](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087285/11239ae9)
* [Windows 10 / Microsoft Edge 17](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35087075/3942a830)
* [Windows 10 / Firefox 71](https://app.crossbrowsertesting.com/public/i761c79c22fd3844/livetests/35086987/d5917eab)


> ## Deployment
For developing this project, I used three resources, GitHub for host the deployed website and repository of all versions, Git that I installed locally and Visual Studio Code, my favorite IDE editor.

To deploying My City | Cluj Napoca in GitHub Page, I followed the following steps:
* In my account GitHub website, I selected Repositories
* I selected ```my-city``` from the GitHub Dashboard.
* I navigated to *Settings* and to the *GitHub Pages* section.
* From the *Source* section, I clicked on the drop-down menu and selected *Master Branch*.
* Once *Master Branch* is selected, the page has been automatically refreshed, with a detailed ribbon display *GitHub Source Saved Pages* indicating the successful implementation.
* The link to the website I found in the *GitHub Pages* section, with a ribbon notification that states: 
```
Your site is published at https://iulianpro.github.io/my-city/
```
To run locally, you can clone this repository directly in your favorite editor, by typing in the terminal the following command:
```
git clone https://github.com/iulianpro/my-city.git
```

> ## Credits

### Content
The text of the About section was inspired by [Wikipedia](https://en.wikipedia.org/wiki/Cluj-Napoca) but not taken as such, I adapted it into a personal version by adding ideas. The Visit section is entirely conceived and written by me, knowing the city of Cluj Napoca, I lived in this city for many years. However, I must remind the employees of the Cluj Napoca City Hall, who were very receptive to expressing their agreement to use the video material, which brings additional relevant information to this website.

### Media
* Vector icons for Visit section from [Flaticon](https://flaticon.com)
* Purchased images from [Adobe Stock Images](https://stock.adobe.com)
* Free images from the Facebook account of [Cluj Napoca Mayor](https://www.facebook.com/EmilBoc.Intotdeaunapentruclujeni/?epa=SEARCH_BOX)
* Video images with the written consent of [Clujbusiness](https://clujbusiness.ro/) website owned by Cluj Napoca City Hall

### Acknowledgements
To create this website, an inspiration but at the same time a source from which I learned many technical elements, was [W3schools](https://www.w3schools.com/). I would also like to thank Twitter for creating Bootstrap which is a magic framework. I would also like to thank the Code Institute instructors who are doing a great job and from where I learned a lot in just a few months. I would also like to thank the colleagues with whom I had discussions on the Slack channels, from where I also had to learn. And last but not least, I thank my mentor [Simen Daehlin](https://github.com/Eventyret).

*This website was created for educational purposes, January 2020.*