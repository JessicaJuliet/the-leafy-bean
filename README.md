## Table of Contents

* Purpose
* User Experience Design (UXD)
    * Target Audience
    * User Stories
        * First-time Visitor Goals
        * Returning Visitor Goals
        * Frequent Visitor Goals
* Design
    * Color scheme
    * Typography
    * Wireframes
    * Imagery 
    * Variations
* Features
    * Existing Features
    * Features Left to Implement
* Technologies Used
* Testing
* Deployment 
* Credits 

------


# The Leafy Bean Website

## Purpose

Many local businesses in Ireland have been hit hard by the COVID-19 pandemic. New Government restrictions have led to shop closures and continued uncertainty for small businesses. As consumers’ buying habits shift predominantly online, it’s more important than ever for small businesses 
to have a strong online presence during these challenging times. 

I have created a fictional local independent coffee shop called The Leafy Bean located in Blackrock, Dublin. The Leafy Bean has a poor online presence and is struggling to reach their customers during the pandemic. They requested a fully responsive website which will allow them to notify their customers of their opening hours in line with government restrictions, and promote their new takeaway coffee service. Furthermore, The Leafy Bean wants to establish itself as a local provider of the best coffee in Blackrock and provide information about its high quality coffee beans.

Please note, this company is entirely fictional and was created for the Code Institute’s Milestone Project 1 as part of their Diploma in Full Stack Software Development. It was developed using the knowledge gained from the HTML, CSS and User Centric Design modules. 

Please see [The Leafy Bean’s](https://jessicajuliet.github.io/the-leafy-bean/) live website. 

## User Experience Design (UXD)


### Target Audience

### User Stories

* First Time Visitor Goals

    * As a first-time visitor, I want to be able to navigate through the website easily on mobile to find what I’m looking for
    * As a first-time visitor, I want to see a visually pleasing website with eye-catching coffee related imagery to entice me to buy
    * As a first-time visitor, I want to locate their social media links to see if they have a large social following and whether they're well-rated
 
* Returning Visitor Goals

    * As a returning visitor, I want to find information about their takeaway service 
    * As a returning visitor, I want to check the shop’s opening hours during the current COVID-19 restrictions
    * As a returning visitor, I want to see information about the quality of their coffee beans

* Frequent Visitor Goals

    * As a frequent visitor, I want see if they they take resuable cups
    * As a frequent visitor, I want to check to see if they have a loyalty scheme
    * As a frequent visitor, I want to read about the company to establish whether they're an independent 
    coffee shop or a chain

## Design 

### Colour Scheme
The two main colours used across the website are white and brown to tie in with The Leafy Bean's product offering - coffee. Furthermore, a dark grey was used for the paragraph text, instead of black, to improve its contrast and readability on screens.

Adobe Color was used to create a colour swatch to find the right shade of brown for the site. A dark brown (Hex Code #695138) was used for the H2 headings and a lighter shade of brown (Hex Code #8f6f4d) was used for icons and buttons. 

#### _Adobe Color Swatch_:

![Colour swatches](https://github.com/JessicaJuliet/the-leafy-bean/blob/1bc7680561ed4c7ea9e4e8733e5ad784f6c640cf/assets/img/color-swatches.png "Colour Swatches")


### Wireframes

The Leafy Bean's website is a single page site. A single page design was chosen because the website has a narrow focus and is purely informational. Furthermore it's ideal for a mobile first design and users will have less clicking to do to find the information they need. 

Please see the wireframes below for the varying devices:
* [Mobile Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/mobile-wireframe.pdf)
* [Tablet Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/tablet-wireframe.pdf)
* [Desktop Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/desktop-wireframe.pdf)

A high-fidelity mockup for mobile was also created using Adobe Illustrator to trial the use of colour and to allow for better visualisation of how the website would look prior to commencing coding. 
* [High-fidelity mobile mockup](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/hifi-mobile-mockup.png)

### Fonts

The fonts originally chosen for this website were [Roboto](https://fonts.google.com/specimen/Roboto) and [Playfair Display](https://fonts.google.com/specimen/Playfair+Display?query=playfair), 
based on inspiration take from [The Art of Coffee](https://theartofcoffee.ie/) website. However, once I commenced building the site, 
I didn't feel that Playfair Display tied into the branding I had in mind for The Leafy Bean - a fun and modern coffee shop 
who's knowledgeable about their coffee! 

I trialed new fonts using Google Fonts and Google Chrome Developer tools to view sample text from The Leafy Bean's website in various fonts. Furthermore, I took guidance from Google Font's "Popular Pairings" to find new fonts.  

I decided to change Playfair Display to [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab?query=roboto) instead. Roboto Slab offers a more fun font with its friendly and open curves, versus Playfair which has a more vintage feel to it. 

### Imagery

The website uses strong impactful coffee related imagery to reinforce The Leafy Bean's product offering and to also appeal to the website user. These images were sourced from [Pexels](www.pexels.com) and [Unsplash](www.unsplash.com) and referenced in the code. In addition, the images give structure and dimension to the website and help provide the user with a positive overall user experience. The size and positioning of these images will vary depending on the screensize. 

Lots of white space was used to help structure and organise the content, improve user experience and improve the legibility of text on the site

## Features

The website is a single page site and is broken down into eight sections. Each section is described in more detail below along with its features and how they meet the visitor goals outlined in the user stories: 

### Existing Features

**Section 1 - Navbar**

The Navbar is fully responsive and collapses down into a hamburger menu on smaller devices. In addition, it provides a full list of links to access each of the key sections on the website, and remains fixed to the top on all devices so the user can easily navigate the site should they not wish to scroll.

> As a first-time visitor, I want to be able to navigate through the website easily on mobile to find what I’m looking for
    
**Section 2 - Hero Image**

The hero image sets the scene for The Leafy Bean's quality product offering by displaying a large and enticing image of coffee and descriptive text overlaying that. 
It includes a CTA which directs users to the shops Opening Hours/ Find Us section of the website. The text displayed shortens down to just the H1 heading on mobile devices so as not to obstruct the users view of the attractive coffee image.

> As a first-time visitor, I want to see a visually pleasing website with eye-catching coffee related imagery to entice me to buy

**Section 3 - Coffee to Go**

The Coffee to Go section provides information about The Leafy Bean's takeaway coffee service. It includes four icons which highlight the shops unique selling points and expand when hovered over on desktop or click on mobile or tablet devices. They allow users to quickly identify The Leafy Bean's key selling points 

> As a returning visitor, I want to find information about their takeaway service

> As a frequent visitor, I want see if they they take resuable cups

> As a returning visitor, I want to see information about the quality of their coffee beans

**Section 4 - Bean Points**

The Bean Points section describes details of the shops loyalty scheme and provides a strong image of coffee beans to capture the users attention.

> As a frequent visitor, I want to check to see if they have a loyalty scheme

**Section 5 - About**

The About Section offers the user more information about The Leafy Bean and their passion for coffee. It also includes a grid of four images to help illustrate the about content. These remain in a grid of four across all devices to reduce the scrolling for users. 

> As a frequent visitor, I want to read about the company to establish whether they're an independent 

**Section 6 - Opening Hours/ Find Us**

The Opening Hours/ Find Us section includes details of The Leafy Bean's opening hours during the COVID-19 pandemic. It also includes an embedded Google map to help users find the shops location.

> As a returning visitor, I want to check the shop’s opening hours during the current COVID-19 restrictions

**Section 7 - Contact**

The Contact section offers a simple contact form to allow the user to send a message to the shop with any queries they may have. The fields are all required and it will not allow a user to submit it unless it has an @ in their email address.

**Section 8 - Footer**

The Footer highlights the shops contact details and address again it also includes links to their social platforms. These were all included in the Footer because this is a location which they are most commonly expected to be by website users.

> As a first-time visitor, I want to locate their social media links to see if they have a large social following and whether they're well-rated

### Features Left to Implement  

Users would like to have a newsletter to sign up to which provides them which insights on the latest coffee trends. This feature was not implemented in the initial release, but will be addressed for a future release. It's dependent on the growth of The Leafy Bean's marketing team.

## Technologies Used

* [GitHub](https://github.com/)
    * GithHub is the hosting site used to store the source code for the Website

* Git
    * Git was used as the version control software to add, commit and push code to the GitHub repository

* [balsamiq](https://balsamiq.com/wireframes/)
    * balsamiq was used to create low-fidelity wireframes of the website

* [Bootstrap](https://getbootstrap.com/)
    * Bootstrap was used throughout the website for the grid layout, navbar, forms and buttons 

* HTML
    * HTML was the main language used to create this website

* CSS
    * Custom CSS was used to add bespoke design

* [Adobe Photoshop](https://www.adobe.com/ie/products/photoshop.html)
    * Photoshop was used to create high-fidelity mock-ups of the website

* [Adobe Illustrator](https://www.adobe.com/ie/products/illustrator.html)
    * Illustrator was used to create the logo and favicon for the website

* [Adobe Color](https://color.adobe.com/)
    * Adobe Color was used to generate a color palette for the website

* [Google Fonts](https://fonts.google.com/)
    * Google Fonts was used to find and sample fonts for the website

* [Font Awesome](https://fontawesome.com/)
    * Font Awesome was used to source the icons used across the site


## Credits

### Media 
* The photos used in this website were obtained from [Pexels](https://www.pexels.com/) and their source is 
referenced in the code



