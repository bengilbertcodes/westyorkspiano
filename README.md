# West Yorkshire Piano Studio

This is a website for the West Yorkshire Piano Studio - a music business based in Leeds, UK. The website aims to give the user access to information about all the services on offer, an overview of the business and a way of contacting the business. Music lessons are the primary focus of the West Yorkshire Piano Studio. The site also aims to showcase some of the music that Ben performs with others and also a podcast that he produces.  

![MOCKUP](docs/readme_images/mockup.jpg)

## Features

### Site wide
* Navigation Menu   
    * Contains links to the Home, Lessons, Music and Contact pages and is responsive on all devices utilising the burger icon for smaller screen sizes.
    * The user will easily be able to navigate between pages of the site on any device.
    * Clicking the West Yorkshire Piano Studio title will return the user to the homepage from anywhere on the site.

    ![Large Screen Nav Menu](docs/readme_images/large-screen-nav.jpg) ![Small Screen Nav Menu](docs/readme_images/small-screen-nav.jpeg)

* Footer
    * This contains links to social media and music websites. Icons are accessible to people using a screen reader through the use of aria labels. ALl icons open into new tabs. The social media and music websites will enable the user to get a bigger picture about the West Yokrshire Piano Studio.
    
    ![Footer](docs/readme_images/footer.jpg)

* Favicon
    * The site will use a favicon consisting of the West Yorkshire Piano Studios initials and in keeping with the websites colour scheme. 
    * This will make it easier to identify the site when users have a lot of browser tabs open.

    ![Favicon](docs/readme_images/favicon.jpeg)

* 404 Page
    * If a user navigates to a broken link then a custom 404 page will be displayed.
    * The user will be able to navigate back to the correct site through the menu or additional link. No need to use the browsers back button.

    ![404 page](docs/readme_images/404-page.jpg)

### Landing Page
* Images
    * As the main focus of the business is music lessons both images will be friendly and demonstrate that the West Yorkshire Piano Studio is a fun place to come and learn at.

    ![Hero Image](docs/readme_images/hero-image.jpg) ![Friendly Lessons image](docs/readme_images/friendly-image.jpg)

* Text 
    * A brief introduction to the West Yorkshire Piano Studio, Ben Gilbert and the some of the services available. A link to the contact page also encourages the user to get in touch with further questions.

### Lessons Page
* Opening paragraph
    * Some exciting text to encourage users visiting the site looking for music lessons. 

![Lessons text](docs/readme_images/lessons-text.jpg)

* Lesson Boxes
    * These contain examples of types of lessons that can be covered at the West Yorkshire Piano Studio. Split into three categroies and boxed to help separate the information.

![Lesson Type boxes](docs/readme_images/lessons-boxes.jpg)

* Images
    * A series of three images showing off the piano in the West Yokrshire Piano Studio.
    
![Lesson images](docs/readme_images/lessons-images.jpg)

### Music Page
* Iframes
    * A more interactive page for the user. Page uses 5 iframes, 4 containing youtube videos and one containing a podcast from podbean.com
    * Each iframe uses appropriate media controls as well as links to the external sites where more inforation is available.
    * An additional title is used above each iframe to give user information about it's content.
    * Another get in touch link encourages the user to navigate to the contact page.

    ![Youtube iframe](docs/readme_images/iframe-1.jpg)
    ![Podbean iframe](docs/readme_images/iframe-2.jpg)

### Contact Page
* Contact Form
    * A form to allow users to contact Ben at The West Yorkshire Piano Studio and enquire about music lessons, live music for events or further questions.
    * The form consists of the following fields and attributes all with placeholder text:
        * Name (required, type=text)
        * Email (required, type=text)
        * Mobile (required, type=phone)
        * Message (required, textarea)
    
    ![Contact form](docs/readme_images/contact-form.jpg)

    * When send is clicked and all fields have been completed the user will see thankyou.html displaying a success message. A 10 second timer is implemented to here to return the user to the homepage.

    ![Thank you message](docs/readme_images/thankyou.jpg)

### Existing Features

* A fully responisve design - designed to work from screensizes greater than 280px.
* A crop down menu utilised when the burger icon is clicked on smaller screens.
* Contact form and confrimation (thank you) page.
* Images throughout the site.

## Design

### Wireframes

Home Page
![Home page wireframe](docs/readme_images/index.png)
![Home page mobile wireframe](docs/readme_images/index-mobile.png)


Lessons Page
![Lessons page wireframe](docs/readme_images/lessons.png)
![Lessons mobile page wireframe](docs/readme_images/lessons-mobile.png)


Music Page
![Music page wireframe](docs/readme_images/music.png)
![Music mobile page wireframe](docs/readme_images/music-mobile.png)


Contact Page
![Contact Page wireframe](docs/readme_images/Contact.png)
![Contact mobile page wireframe](docs/readme_images/contact-mobile.png)



## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* Visual Studio Code
    * The website was developed using Visual Studio Code IDE
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Social media icons, burger/menu icon and music notes icon were obtained from https://fontawesome.com/.
* Google Fonts
    * The two fonts used (Merriweather and Karla) came from https://fonts.google.com/
* Webp Image converter
    * https://image.online-convert.com/ was used to convert images to .webp.
* Photos (Mac)
    * Used to resize photos throughout the site.
* Favicon.io
    * The favicon was created at https://favicon.io/favicon-generator/.
* Balsamiq
    * Wireframes were created using Balsamiq for Desktop https://balsamiq.com/wireframes/desktop/

### Testing

## Responsiveness

All pages were tested to ensure a responsive design was acheieved on screen sizes from 280px (Galaxy Fold) and upwards as defined in WCAG 2.2 Reflow Criteria (https://www.w3.org/TR/WCAG22/#reflow).

Steps to test:

1. Open Chrome browser and naviagte to https://bengilbertcodes.github.io/westyorkspiano/.
2. Right click and se;ect Inspect to open developer tools.
3. Set to Responsive and reduce the width to 280px and set zoom to 50%.
4. Click and drag to repsonsive window up to max-width.

Expected results:

The site is responsive on all screen sizes, no images and iframes are stretched.
No horizontal scroll is present.
No elelments overlap.

Actual Results:
The webiste meets all responsiveness criteria.

The website has also been checked in Firefox, Safari, Chrome and Edge browsers and the following devices:
- Google Pixel 3a
- Ipad Pro
- Iphone 13

### Accessibility 

The Wave Accessibility (https://wave.webaim.org/) tool has been used throughout development and for the final testing of the website.

No errors were reported accross the site. 

Alerts:

- For redundant links where Home in the nav menu is next to the clickable page title. I am happy to leave this as is.
- Copyright text is very small. Due to this being just a copyright note I am happy to leave this.
- Embedded Youtube videos are present - Ensure that synchronized captioning is available. Two videos do not need captioning and two with a singer don't have them. This is something I need to consider for future recordings. 

### Lighthouse Testing

index.html:
![Lighthouse image for index.html](docs/readme_images/homepage-lighthouse.png)

lessons.html:
![Lighthouse image for lessons.html](docs/readme_images/lessons-lighthouse.png)

music.html
