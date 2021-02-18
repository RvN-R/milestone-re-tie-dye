<h1 style="text-align: center;">Re-Tie Dye Website</h1>
<a href="#">View the live project here.</a>

This is the main shop front for the organisation Re-Tie Dye. It is designed to be responsive and accessible on a range of devices, making it easy to navigate and meet the business key goals. 

Include image of my site from <a href="http://ami.responsivedesign.is/">Responsive Web Design is..</a> below.


# Client Requirements
* We need a platform that illustrates and shares our key values.
* We need a platform that depecits and captures the brands ethos.
* We need a platform that makes those visitng it empowered and confident to use.
* We need a platfrom that is a safe and none toxic enviroment to enhabit.  
* We need a platform that encourages users to return time and time again. 

# User Experience (UX)

* ## User Stories

    * ### First Time Vistor Goals

        1. As a First Time Vistor, I want to easily understand the main purpose of the site, and learn more about the organizations founding values. 
        1. As a First Time Vistor, I want to be able to easily navigate throughout the site to find key content. 
        1. As a First Time Vistor, I want to clearly find out what makes this organization different from its competitors. 
        1. As a First Time Vistor, I want to find out how to user the site as efficently as possible
        1. As a First Time Vistor, I want to source information that validates the organzations legitimacy, most efficent way to do this is  through there social media.  

    * ### Returning Vistor Goals

        1. As a Returning Vistor, I want to be able to navigate to the store quickly. 
        1. As a Returning Vistor, I want to be notified on when new auctions going live and when.
        1. As a Returning Vistor, I want to be able to place a bid on an item quickly. 
        1. As a Returning Vistor, I want to be able to see if any changes to the "How It Works" section has been changed.

    * ### Frequent User Goals

        1. As a Frequent User, I want to check to see fi tehre are any newly added items in the store. 
        1. As a Frequent User, I want to see if any new auctions are going live soon. 
        1. As a Frequent User, I want the platform to recognize I have visted and used before. 

* ## Design 

    * ### Color Scheme  
        * Main color scheme sourced with the help of a website called <a href="https://coolors.co/">coolors</a>. 
        Hex numbers of each colour used included below: 

            * #ffadad
            * #ffd6a5
            * #fdffb6
            * #caffbf
            * #9bf6ff
            * #a0c4ff
            * #bdb2ff
            * #ffc6ff

     
    * ### Typography 
        * Kavoon is the font chosen for use across the website site , with Sans Serif as the back up font in case 
        there are any issues importing into the site correctly. Kavoon shares the same connotations as the brand image of the
        organisation, so it meets the clients requirements. 


    * ### Wireframe Mockups - Desktop

        * <a href="assets/images/readme-images/Desktop-Home .png"> Home</a>
        * <a href="assets/images/readme-images/Desktop-AboutUs.png">About Us</a>
        * <a href="assets/images/readme-images/Desktop-F.A.Q.png">F.A.Q</a>
        * <a href="assets/images/readme-images/Desktop-Shop.png">Shop</a>
        * <a href="assets/images/readme-images/Desktop-ItemPage.png">Item Page</a>
        * <a href="assets/images/readme-images/Desktop-ItemPagePopOut.png">Item Page Pop Out</a>

   * ### Wireframe Mockups - Mobile Device

        * <a href="assets/images/readme-images/Mobile-Home.png">Home</a> 
        * <a href="assets/images/readme-images/Mobile-Home-Nav.png">Home with Navigation</a>
        * <a href="assets/images/readme-images/Mobile-About Us.png">About Us</a> 
        * <a href="assets/images/readme-images/Mobile-AboutUs-Scrolled.png">About Us scrolled</a>  
        * <a href="assets/images/readme-images/Mobile-FAQ.png">F.A.Q</a> 
        * <a href="assets/images/readme-images/Moble-FAQ-Scolled.png">F.A.Q scrolled</a>
        * <a href="assets/images/readme-images/Mobile-Shop.png">Shop</a> 
        * <a href="assets/images/readme-images/Mobile-Shop-Scolled.png">Shop scrolled</a>
        * <a href="assets/images/readme-images/Mobile-Item.png">Item Page</a> 
        * <a href="assets/images/readme-images/Mobile-Item-Scroll.png">Item Page scrolled</a>
        * <a href="assets/images/readme-images/Mobile-Item-Pop-Up.png">Item Page Pop Out</a>

            


* ## Images
    * Tie Dye back ground image for header https://unsplash.com/photos/7EK5WABscqw

Notes on issues i got passed: 
* couldn't get Re-Tie Dye logo to fit properly when the page went from large to small. Got around this by setting the setting display to block, margin left and right to auto and then exprimented with the width percentage until I found an option that worked. 
* had unwanted white gaps in my navigation li elements, used the inspector tool and discoverd the bootstrap item "list-inline-item" sets a margin automatically. In my style.css I set that class to 0 margin. Also created my own class in the Ul called menucontainer and set the font size to 0. This sorted out the issue but now the font in my li was 0, so using an id called nav I targeted the li's within that id and set there font size so I could see my navigation headings. Saved images depiciting this. 
* used https://css-tricks.com/centering-css-complete-guide/ to figure out how to center a button "Click me to get Bidding!"
* margins for two bottstrap container classes weren't lining up, discovered container class had padding-right and padding-left settings. I had to over right these settings using insepctor tool in chrome. I then set padding right and padding left for all container classes to 0 in style.css.
* struggling to get the social icons to center. tried using combination of row justify-content-center with a single col-12 but it wouldn't center. Quick fix I used three col 4, copied the social icons into the 2nd col 4, then created a class called social-align to text align the icons. I left the 1st and 3rd col 4 blank and got the end effect. This isn't a perfect fix and I would like to find another solution. have images.


