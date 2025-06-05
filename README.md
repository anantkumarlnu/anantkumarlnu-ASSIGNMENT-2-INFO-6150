# ASSIGNMENT-2-INFO-6150
2nd assignment for the INFO 6150(12566).

name - Anant Kumar LNU
NUID - 002050375

Going of the similar structure that I followed for the first assignment, I'll list out the core requirements and where they are covered in the assignment:
- Favicon - https://www.drawkit.com/illustrations/chubbs-character-illustrations an image from this collection was cropped and used for the favicon, it kind of matched the initial color palette of the website, hence the choice.
- Table - implemented for the referrals section
- Form - implemented for the comments section
- Images - author image on the page uses the image tag
- Hyperlink - in the nav. in the floated column 
- Button - reachout button on the top right corner of the page.
- audio - audio at the bottom of the page, recommendation background sound for the ultimate viewing experience 
- video - recent trips section 
- header - the page has an header, explanation of implementation is below 
- footer - the page has an footer, explanation of implementation is below 
- summary - the intro portion below the image is written in the summary tag  
- menu - used as an unordered list for the project cards
- tel for contact information - reachout button 
- mailto for contact information - in the footer
- Use an external CSS file only. - have implemented this.
- Use of float and overflow property - float has been used to implement the column layout for the discover bar that acts as a navigation for the page, overflow has been used for the referral table.

-Use of column layout structure -  implemented for the web design of the page
-Use of absolute and relative position whenever necessary - used for placement of the image for all views and also used for ipad navigation 
-Add a table, then style the table using CSS selectors. Guide for CSS Selectors - http://www.w3schools.com/cssref/css_selectors.aspLinks to an external site. - table has been implemented for the referral section

-Create a professional image gallery for certifications, etc., with hover effects and figure captions. Include this in your portfolio. - dummy certifications were created in pages and those were used since I do not have any certifications. All my certifications belong to the company that I used to work for, bummer, ik ik. 

-Make the website responsive using media queries for devices like iPad(768px) and Smartphones (350 – 365px). - implemented the same, more explanation below

Include the readme.txt/readme.md file and include all the tags used and give a short description - implemented 

The assignment must be submitted on your PRIVATE GitHub account (use Northeastern email account). The zip file must be submitted on CANVAS, and the GitHub URL of the assignment must be in the canvas remarks. - will be done

WEB LAYOUT DESCRIPTION --
HEADER SECTION
- A header is used to contain the Name title and reachout button.
- float is used to implement the column layout for the discover bar, which has links to different sections of the page
- The first section of the page is the introduction section that has my pic along with the usage of summary and detail tag. The detail tag has my linkedin Introduction
- absolute positioning was used to achieve the image position, a slight box-shadow is used as well to give it a nice elevated effect
- projects are kept in cards. I have 3 cards per flex container and the positioning of the cards are determined with the help of flex
- menu is used as an unordered list for the project description section

REFERRAL SECTION 
- This section has the table and styling implementation as well for the tables
- th and thead was selected for the darker shade of blue
- nth even child was selected using the pseudo class to achieve the lighter background color for the second data row for the table
- the table's container's height is kept smaller intentionally to showcase the use of overflow and scroll property
- the content of the referral sections are taken from the letter of recommendations that I received from the listed individuals
- the scroll bar width has also being adjusted using css 

CERTIFICATIONS SECTION 
- Image gallery with hover effect and with the use of figure and figure caption has been created
- box-shadow, boldness, background color and a few other properties are toggled on hover.
- the certificates open in a new tab when clicked, this has been achieved with the help of target="_blank"
- the certificates are dummy certificates that I created using pages template, this was crossed checked with TA before implementation

TRAVELS
- travels section has similar card layout to the certification section
- it has videos from my recent trip to NY
- I faced a peculiar issue while implementing the video tag.
- the videos were originally in .MOV format. adding these directly resulted in the videos being 180 deg flipped.
- trying to flip it the other way using transform property resulted in the controls getting inverted.
- fixed the issue my converting the mov files to .mp4 files, will have to check the limitations of the video tag

COMMENTS SECTION
- the comment section makes use of the form tag
- the form tag has a textarea field and a submit button that is present to take feedback

FOOTER SECTION 
- The footer section has the mailto link and audio tag
- The audio tag has the audio file of the GTA V loading screen, which, in my humble opinion, makes for a better viewing experience.
- I created a voice memo from a yt video for the same, since this website will not see the light of day, there won't be any copyright issues

IPAD IMPLEMENTATION 
- the column layout was abandoned for the ipad layout and instead absolute positioning was used again for the nav links
- the header gets a background color as well
- sections like project container and certification were added separately with different layout to reduce the number of cards for the ipad layout
- the ipad layout has 2 project cards and 2 certificate cards per row.
- this was achieved by setting the 3 card container to display:none in the media query styles
- column layout was used for the travel section

MOBILE IMPLEMENTATION 
- Navigation was removed since the heading of the page as getting cluttered
- image size was reduced and border radius was increased - for the author image
- the reachout text was also removed and now we only have the icon left
- flex direction for all flex containers were changed to column to fit the smaller screen better

RESOURCES 
- colors for the website were selected from - https://yeun.github.io/open-color/#teal and - https://flatuicolors.com/palette/defo
- favicon was taken from a collection on - https://www.drawkit.com/
- icon svgs were taken from - https://heroicons.com/
- stackoverflow, w3school and MDN were used for resolving issues during the implementation 

