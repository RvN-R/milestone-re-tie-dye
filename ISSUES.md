<h1 style="text-align: center;">Issues I Faced and How I Overcame Them</h1>

* couldn't get Re-Tie Dye logo to fit properly when the page went from large to small. Got around this by setting the setting display to block, margin left and right to auto and then exprimented with the width percentage until I found an option that worked. 

* had unwanted white gaps in my navigation li elements, used the inspector tool and discoverd the bootstrap item "list-inline-item" sets a margin automatically. In my style.css I set that class to 0 margin. Also created my own class in the Ul called menucontainer and set the font size to 0. This sorted out the issue but now the font in my li was 0, so using an id called nav I targeted the li's within that id and set there font size so I could see my navigation headings. Saved images depiciting this. 

* used https://css-tricks.com/centering-css-complete-guide/ to figure out how to center a button "Click me to get Bidding!"

* margins for two bottstrap container classes weren't lining up, discovered container class had padding-right and padding-left settings. I had to over right these settings using insepctor tool in chrome. I then set padding right and padding left for all container classes to 0 in style.css.

* I struggled to get the social icons that I wanted in my footer to center.

<img src="assets/images/issues-images/can'tgetsocialstocenter.png">

I tried using combination of different Bootstrap layout components like row justify-content-center with a single col-12 but the icons wouldn't center. I found that if I used three col 4 and copied the html for the social icons into the 2nd col 4, and then left the first and third col emppty the icons would appear close the the center. I then created a class called social-align to text align the icons to get the desired affect. I've included images of the html code below. 

<img src="assets/images/issues-images/can'tgetsocialstocenterfix.png">

I am sure this isn't a perfect fix and as my journey contiunes I would like to find another solution.


* The header was looking good on desktop screens, but on small screen and remote devices the header took up too much room on screen sizes below 767px. 

<img src="assets/images/issues-images/largeheaderinmobileview.png">

I used media queries in my style.css so that when screen sizes went below 767px they didn't display the second col that contains the websites tagline. It wouldn't be benificial to a remote users experience

<img src="assets/images/issues-images/largeheaderinmobileviewfix.png">

* The text in the paragraphs of on the About Us page were looking good but they lined up with the top of the images, I needed the text to align with the center of the cols. To do this I used bootstrap align-self-center. 


* The order of the hero images and paragraphs on the about me page looked good for mobile devices, as shown in the image below: 

<img src="assets/images/issues-images/heroandtextlayoutaboutmemobile.png">

However, I didn't like the way the order worked screen sizes above small. 

<img src="assets/images/issues-images/heroandtextlayoutaboutmedesktop.png">

To get passed this issue I used bootstrap order to change the order between one hero and one paragraph in small breakpoints and above. This now makes the about me page layout work for both mobile and larger devices.

<img src="assets/images/issues-images/heroandtextlayoutaboutmedesktopfixcode.png">
<i>image of html code used to fix the about me layout</i>

<img src="assets/images/issues-images/heroandtextlayoutaboutmedesktopfix.png">
<i>image of about me after the html fix code has been deployed</i>

* The FAQ page looked good on large screen sizes, but the hero image took up too much space on smaller screen sizes. It also left a lot of blank space on medium and small screen sizes.

<img src="assets/images/issues-images/toomuchfreespaceinfaqmdsize.png">
<i>hero leaving too much room on medium screen sizes.</i>

 To get past this issue I used a second hero image and slotted it just underneath the orginal hero using a div. I then used bootstap d none, d sm block, d sm none, d md block, d md none and d lg none. I used d none, d md block and d lg none on image of the male model, so it would only show in medium screen sizes. 
 
 <img src="assets/images/issues-images/toomuchfreespaceinfaqmdsizeaddmale.png">
<i>medium screen size after inclusion of male model hero.</i>
 
This solved the issue of too much blank space in medium screen sizes. In addition it wouldn't show in small screen sizes either, which wouldn't compound the issue of the hero taking up too much screen size. I then used d none, d sm none and d md block on the orginal female. This would prevent the hero from appearing in smaller screen sizes thus making the website more responsive. This has now improved the user experience for those viewing the FAQ page on a remote device. 

<img src="assets/images/issues-images/toomuchfreespaceinfaqmdsizeaddmalehtmlfix.png">
<i>html code I used to fix to make the FAQ more responsive.</i>

