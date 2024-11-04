# Welcome to Innerbreath!

## Introduction
The Meditation Website is a platform designed to help users embark on a journey of mindfulness and wellness. It provides a range of breathing techniques, guided meditation resources, and personalized private sessions to help users find balance, reduce stress, and improve mental clarity.

## Features
Guided Breathing Exercises: Explore various breathing exercises, such as Box Breathing and the 4-7-8 Technique, with easy-to-follow instructions.
Private Session Sign-Up: A form to book personalized meditation sessions with specific needs, age, and goals.
User-Friendly Design: A calming, intuitive layout that enhances the user experience.

## Technologies Used
### Languages
HTML/CSS

### Libraries
<ul>
<li><a href="https://fonts.google.com" target="_blank">Google Fonts</a></li>
Font styles
<li><a href="https://fontawesome.com/" target="_blank">Font Awesome</a></li>
Used for Icons
</ul>


### Platforms
<ul>
<li><a href="https://github.com/" target="_blank">Github</a></li>
Storing code remotely and deployment.
<li><a href="https://code.visualstudio.com/" target="_blank">Visual Studio Code</a></li>
IDE for project development.
</ul>

### Other Tools
<ul>
<li><a href="https://www.favicon-generator.org/" target="_blank">Favicon generator</a></li>
Favicons
</ul>

## Bugs
<ul>
<li>Tried launching the preview from the terminal in github but I was not able to see anything on the preview only a blank page. Then i tried launching the preview in VSC and that made it work after that it has worked fine. 
<li>Tried to set the main content to text-align:center but when checking the accessibility score of the website it got lower. So I changed it to align-justify wich made the score even lower then i changed it to align-left instead for better accessibility on the website.</li>
</ul>

## Testing
### Validation
<ul>
<li>HTML has been validated with <a href="https://validator.w3.org/#validate_by_input" target="_blank">W3C HTML5 Validator</a></li>
<li>CSS has been validated with <a href="https://jigsaw.w3.org/css-validator/validator" target="_blank">W3C CSS Validator</a></li>
</ul>

### General Testing
<ul>
<li>I tested that the website works on diffrent browsers:Chrome, Firefox, Opera GX,</li>
<li>I checked so it is responsive and functions on all standard screen sizes using the devtools in Chrome.</li>
<li>I tested all navigations, header, and the forum page submit.
<li>I checked so all text in the project is easy to read.</li>
</ul>

### Accessibility Testing
Accessibility testing where done in [PageSpeed-Insights](https://pagespeed.web.dev/)

<p>First test.</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/innerbreath bad accessibility.png">

<p>Got two things that needed to be fixed for better accessibility:</p>
<p>First problem:</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/names and labels problem innerbreath.png">
<p>Fixed the problem by adding a aria-label to all social media link in the footers on all HTML files.</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/names and labels solution innerbreath.png">
<p>The second problem:</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/contrast problem innerbreath.png">
<p>Fixed this problem by simply change the color of the logo in the header to a darker color for better contrast which makes it easier to read.</p>

I tried The accessibility test after I fixed the problems and then i got these resault.
<p>PC Test</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/pc preformence on innerbreath.png">
<p>Mobile Test</p>
<img src="/workspaces/Project1_Meditation_Website/assets/css/images/Media/mobile preformance innerbreath.png">

## Credits
Favicon generated in [favicon-generator](https://www.favicon-generator.org)
Pictures for website all taken from [pixabay](https://pixabay.com/).
Social media buttons in footer [W3schools](https://www.w3schools.com/howto/howto_css_social_media_buttons.asp).
The icons in the footer were taken from [Font-Awesome](https://fontawesome.com/)
Guidense during the project from my mentor Rory Patrick.
Forum file I took inspiration from the coders coffeehouse forum in the course from Code institute.
The text generated on exrecises page is mostly from my head and from reading about Wim hoff (A breathing meditation Icon) for years. I put the exrecise page in Chat GPT-4 to generate a FAQ page, I checked it and it looks good to me, but there may be some spelling mistakes or some sentences that dont make sense to a naitive english speaker.

## What I wanted to do
One thing I wanted to do was add a a background image to the forum page so it would have looked better for laptop/pc users. So that the forum was in a block and easy to read but the empty right part of the screen was a relaxing image. The layout of the forum page on mobile and tablet is good and did not need any additional image to make the page look more livly. Also wanted to add background image to header but it made the accessibility score go down since the logo was hard to see, I could have made a logo picture that had a background wich made it easy to read out but I did not have time.
