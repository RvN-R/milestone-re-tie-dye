<h1 style="text-align: center;">Issues I Faced and How I Overcame Them</h1>

* couldn't get Re-Tie Dye logo to fit properly when the page went from large to small. Got around this by setting the setting display to block, margin left and right to auto and then exprimented with the width percentage until I found an option that worked. 

* had unwanted white gaps in my navigation li elements, used the inspector tool and discoverd the bootstrap item "list-inline-item" sets a margin automatically. In my style.css I set that class to 0 margin. Also created my own class in the Ul called menucontainer and set the font size to 0. This sorted out the issue but now the font in my li was 0, so using an id called nav I targeted the li's within that id and set there font size so I could see my navigation headings. Saved images depiciting this. 

* used https://css-tricks.com/centering-css-complete-guide/ to figure out how to center a button "Click me to get Bidding!"

* margins for two bottstrap container classes weren't lining up, discovered container class had padding-right and padding-left settings. I had to over right these settings using insepctor tool in chrome. I then set padding right and padding left for all container classes to 0 in style.css.

* I struggled to get the social icons that I wanted in my footer to center. 
<img src="assets/images/issues-images/can'tgetsocialstocenter.png">

I tried using combination of row justify-content-center with a single col-12 but it wouldn't center. I found that if I used three col 4 and copied the social icons into the 2nd col 4. I left the first and third col emppty and then created a class called social-align to text align the icons. I am sure this isn't a perfect fix and as my journey contiunes I would like to find another solution.











* wasn't happy with my navigation so used https://www.w3schools.com/howto/howto_js_topnav.asp as insperation for new navigation. taken screen shots. 

* header was looking good on desktop screens, but got overly large screen sizes below 767px, used media queries to display none the second col containing websites tagline. taken screen shots.

* The text in the paragraphs of on the About Us page were looking good but they lined up with the top of the images, I needed the text to align with the center of the cols. To do this I used bootstrap align-self-center. 

* Un order list on index wouldn't center, used d flex and justify content center to try and center it. But due to the differing lengths of the bullet points it still didn't look centered. So I changed the background of the col to create a box, which is centered and that seems to have improved the overall look of the un ordered list on large screens. 

* order of the hero images and paragraphs on the about me page looked good for mobile devices, but the order didn't work in larger screen sizes. I used bootstrap order to change the order between one hero and one paragraph in small breakpoints and above. This now makes the about me page layout work for both mobile and larger devices.

* faq looked good on large screen sizes, but the hero image took up too much space on smaller screen sizes. It also left a lot of blank space on medium and small screen sizes. To get past this issue I used a second hero image and slotted it just underneath the orginal hero using a div. I then used bootstap d none, d sm block, d sm none, d md block, d md none and d lg none. I used d none, d md block and d lg none on image of the male model, so it would only show in medium screen sizes. This would solve the issue of too much blank space in medium screen sizes. It would also not show in small screen sizes, which wouldn't compound the issue of the hero taking up too much screen size. I think used d none, d sm none and d md block on the orginal female. This would prevent the hero from appearing in smaller screen sizes thus making the website more responsive. Now only the important FAQ information is present on mobile screen sizes. 
