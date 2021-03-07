# Testing

<a href="README.md">Main README file</a>

I used <a href="https://validator.w3.org/">Markup Validation Service</a> and <a href="https://jigsaw.w3.org/css-validator/">CSS Validation Service</a> to check both HTML and CSS using the direct input function of both services. The results came back with no issues flagged.

I used Chromes inspect feature Lighthouse on all of my pages, to try and improve the sites performance. The reports found the following: 

<b>Home Page</b> - when tested on mobile and desktop performance the page scored well. For Accessibility, Best Practices and SEO it scored in the high 90's. However, it was let down with Performance with a score of 71 for mobile and 87 in desktop. Report blamed large image file sizes, and large image in the header. 

<b>About Page</b> - when tested in mobile and desktop the page scored in the high 80's for Performance and Accessibility. It scored in the high 90's for Best Practices and SEO. However, when tested for mobile devices the page scored 70's for Performance and high 80's for Accessibility. The report mentioned unused CSS being present and size of the images. I went through the HTML to delete any unused CSS classes, and also experimented in Photoshop saving the images with lower bit depth to try and speed up load time. 

<b>Shop Page</b> - when tested in mobile and desktop the page scored in the high 80's for Performance, Accessibility, Best Practices and SEO. However, in mobile it scored high 60s for Performance. The main issues seem to be caused due by large image file sizes, and unused javascript within Bootleg components. I don't know enough about Javascript to delete these unused features without seriously affecting the use of the component itself. Once I deploy some more Javascript within the site, hopefully some of these unused features will become used. Regarding image sizes I experimented in Photoshop with differing files sizes. This is more vital with this page due to the amount of images the client will end up using on this page.  I also experimented with different codecs like JPEG, and saved at a lower bit depth. Load time was less but image quality was unacceptable so I went back to PNG. 

<b>FAQ Page</b> - when tested in mobile and desktop the page scored in the high 90's for Performance, Accessibility, Best Practice and SEO. However, it was let down in the mobile report scoring in the high 60's for Performance. Similar reasons that where report in the Lighthouse reports for the Shop page were reported here. Size of images and unused Javascript within the Bootleg components. 

In conclusion from looking at all of the Lighthouse Reports more experimentation with image file sizes and codecs is required to improve the load up time of the website. As already mentioned an attempt was made during the creation of this site, which improved the results and performance within Lighthouse. However, with some additional research on the subject I am sure we can see some slight improvement in load up of the site.

## Testing Client Requirements featured in README.md

* ### We need a platform that illustrates and shares our key values.
    i.  No matter the webpage they are currently on, visitors to the website can easily navigate to the About page. The About page contains key information and explains the clients key values with the help of hero images that echo the connotations of the paragraphs. 

* ### We need a platform that depicts and captures the brands ethos.
    i.  I've used the header and the footer to capture the main ethos of the brand. To do this I used the clients logo, which perfectly illustrates the echo friendly nature of the brand. We have also used a tagline to succinctly explain the brands ethos in single sentence. In both the header and the footer we have used the same background image, keeping a consistent theme running through the website.

* ### We need a platform that makes those visiting it empowered and confident to use.
    i.  The navigation of the website is simple to use, it shouldn't be daunting for first time visitors. The location of the navigation bar remains consistent throughout the site. We have used active buttons within the navigation to inform the visitor of there location should they get confused. At anytime they can click the main logo at the top right hand corner of the page, and be transported back to Home. Where they can carry on there journey exploring the site. 

* ### We need a platform that is a safe and none toxic environment to enhabit.
    i.  I've used pastel soft colours throughout the site to create a calm environment in which to visit. The colours are those used in the main background image of the header and footer, this keeps continuity. 

<hr>

## Testing User Stories from UX section in README.md
<hr>

### Testing First Time Visitor Goals

1. As a First Time Visitor, I want to easily understand the main purpose of the site, and learn more about the organisations founding values.
    *   Home features a Jumbotron Bootstrap component listing out the key workings of the site. 
    *   About page features three paragraphs explaining the organisations values, with hero images to reinforce those connotations. 
        
1. As a First Time Visitor, I want to be able to easily navigate throughout the site to find key content. 
    *   No matter the page the visitor is on, they can navigate to any page on the site using the navigation bar found in the header. Location of the navigation bar remains the same no matter the screen size. 
    *   The colours used on the navigation bar relating to each page remains consistent throughout the site. To help remind the visitor which page he/she is currently on, the colour of that pages navigation button remains full. The other navigation buttons to the other pages stay grey. The coloured button on a grey background is also more visible to the visitor.  
    *   The logo image in the top right hand corner of the header always leads back to the home page.
    *   The call to action button featured in the Home Jumbotron links to the websites Shop page, which should be one of the main reasons for there visit to the site. 

1. As a First Time Visitor, I want to clearly find out what makes this organisation different from its competitors.
    *   About page features three paragraphs explaining the organisations unique selling points, also features hero images to aid in explanation. 

1. As a First Time Visitor, I want to source information that validates the organisations legitimacy, most efficient way to do this is  through there social media.  
    *   In the footer of every page are three social icons linked to the organisations social media sites. The sites open up in a different tab, so the visitor can continue there journey through the website without being diverted to a different website. 


### Testing Returning Visitor Goals

1. As a Returning Visitor, I want to be able to navigate to the store quickly. 
    *   Home features Jumbotron Bootstrap component with a call to action button linked to the Shop page. 

1. As a Returning Visitor, I want to be notified on when new auctions going live and when.
    *   Shop has a Modal once the visitor clicks on "Bid" providing the opportunity to submit there details to be notified of future auctions.  
    * Home features a Jumbotron with a list of useful information, this information details when new auctions will go live.

1. As a Returning Visitor, I want to be able to place a bid on an item quickly. 
    *   Home features Jumbotron Bootstrap component with a call to action button linked to the Shop page. Once on the Shop page the visitor can browse available items and then click a call to action button labelled "bid". At this stage the button is linked to a Modal for registering interest in an item. Future features will allow the visitor to place a bid on said item. As it stands within two clicks the visitor can bid on an item. 

1. As a Returning Visitor, I want to be able to see if any changes to the "How It Works" section has been changed.
    *   Home features Jumbotron Bootstrap component entitled "How it Works", which is updated as and when changes are made. 

<hr>

## Manually Testing Website features
<hr>

### Home Page

1.  Navigation
* Go to the "Home" page.
* Change the screen size from desktop to tablet, then change from tablet to smaller devices and verify that the navigation bar is responsive. 
* Confirm that the text in the navigation button isn't restricted by differing screen sizes, and the bar continues to travel the width of the screen. 
* Hover over the navigation buttons and make sure the hovering function works. 
* Click the logo in the top right hand corner of the header, verify that it links to the home page. 
* Click on each navigation button and confirm that they link to the correct page. 
* Repeat verification of functionality and responsiveness on iPhone and iPad. 

2.  Home Content
* Go to the "Home" page.
* Change the screen size from desktop to tablet, then change from tablet to smaller devices and verify that the "So How Does This Work" Jumbotron is responsive.
* Make sure there are no overflow issues effecting the layout of the bullet points within the un ordered list. 
* Make sure the "Get Bidding" button is centered on all device screen sizes.
* Perform the following manual check: <b><i>Home > Get Bidding!</i></b> When you click the button you should be transported to the Shop page. 

3.  Footers
* Hover over each social media icon and confirm colour and shadow transitions are as designed. Colour should be off white and the shadow should be dark grey. 
* Perform the following manual check: <b><i>Home > Scroll to Footer > Click Icon</i></b> When you click the icon a new tab should open with the clients relevant social media account. 
* Reduce screen size to verify that the icons size is responsive, and they remain centered. 
* Also confirm the footer itself is responsive by decreasing and increasing screen sizes.  

### About Page

1.  Navigation
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages. 

2. About Content
* Verify that distance of the heading from the navigation bar is identical to Shop and FAQ pages. 
* Change the screen size from desktop to tablet, then change from tablet to smaller devices and verify hero images and text are appearing as designed. Order of images and hero images should change appearance from how its appears on larger devices. 
* On smaller devices make sure there are no overlay issues that effect the readability of the content.

3.  Footer
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages.   

### Shop Page

1.  Navigation
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages. 

2. Shop Content
* Verify that distance of the heading from the navigation bar is identical to About and FAQ pages. 
* Change the screen size from desktop to tablet, then change from tablet to smaller devices and verify hero images and text are appearing as designed. On medium and larger screens three item cards should appear alongside each other. On smaller screen sizes the item cards should appear one above each other, improves small screen experience. 
* On smaller devices make sure there are no overlay issues that effect the readability of the content.
* Perform the following manual check: <b><i>Home > Shop > Bid</i></b> When you click the "Bid" call to action button a Modal should appear.
* With the Modal form open fill out one email address as prompted and click submit, you should get a notification to fill out the remaining information. Perform this exact check with "Confirm Email Address" and "Notify me of future auctions" check box. 
* Once you've filled out the Modal form click submit, a new tab should open linked to Code Institutes form dump. Future revisions of the website will link to the back end of the website. 
* Click on each image, the image should appear in a Modal. Perform the same test on medium and small screen sizes, and make sure the display of the image isn't impaired by differing screen sizes.  


3.  Footer
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages.   

### FAQ Page

1.  Navigation
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages. 

2. Shop Content
* Verify that distance of the heading from the navigation bar is identical to Shop and FAQ pages. 
* Change the screen size from desktop to tablet, then change from tablet to smaller devices and verify hero images and accordion component appear as designed. On large screen sizes the FAQ page should appear with an accordion component on the left and a hero image on the right. On medium screen sizes the FAQ page should appear with an accordion component on the left, and two smaller hero images on the right. On small screen sizes all that should appear is the accordion component. 
* Perform the following manual check: <b><i>Home > FAQ > Question cards</i></b> When you click on the question card an answer card should appear underneath it. Repeat this check on each question to confirm the relevant answer appears. When you click on the next question card the previous answer card that was open should close.  

3.  Footer
* Repeat navigation testing steps performed on home page. 
* Confirm HTML and CSS styling match navigation bar on previous pages.  

##Further Testing

* Viewed the website on various devices including iPhone 11, iPad Pro, Microsoft Surface and iMac Pro. On extremely large screen sizes the website was off center. To get past this issue I set the body's max width to 2000px and the left and right margin to 0. This centered the website on larger screen sizes. 
* Sent link of website to family and friends for them to check over the site. It was also reported the background image of the header takes a while to load. Still trying to find the actual reason for this bug. I've experimented compression the image in Photoshop to lower the file size, thus speeding up the load time. This has worked slightly but more experimentaion on file size needs to be completed to improve to the load time. 
