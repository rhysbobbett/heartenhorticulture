# Testing

I have carried out testing to fix bugs and validated the HTML and CSS of each page, results shown below.

## Bugs

Firstly, I will go over basic problems I bugs and issues I encountered when coding the site.

Issue : Upon deployment to Github pages, my logo image was failing to load.
Solution : This was fixed by changing the URL to navigate from the parent directory. This was solved by reading through the CSS documentation 

Issue : When deploying to Github using the animated image png files in the CSS, the URL again failed to load correctly.
Solution : formatting the folder as '../assets/images/filename.jpeg' allows github to correctly find the parent folder allowing images to load correctly.

Issue : The 'Contact us!' button upon the homepage would not be visible when the background was moving.
Solution : Using Z-index in the CSS, the layers can be sorted by their visibility order, and numbered accordingly, the order was corrected to suit the page requirements. This method was applied to allow images to be placed on top of other images on the index.html page.

Issue: This was an aesthetic issue, but having the links in the top right corner didn't provide the accessibility of placing them adjacent to the logo in a user's line of sight when looking at a desktop screen.
Solution: Adjust design to accomodate centering the link navigation bar onscreen.

Issue: Toggle of my burger button was not initiating the dropdown menu.
Solution: I had been using a slightly outdated version of bootstrap, I added the updated CDN links to the head of my pages and it now works.

Issue: Content overlaps with footer on services page.
Solution: Adjust image size using the CSS vh variable and create a container to act as a heading banner. Change the class to that of bootstrap's 'container-fluid' in the correct divs on the page.

## Accesibility Audit 
Using Chrome's Lighthouse developer tools, I was able to get a good accesibility score on each of my website's pages.
I have had to darken some fonts that were originally going to be lighter shades of green, this was to reach a minimum rating of 4 for contrast visibility. The colour scheme I have used is still co-ordinated using my original palette but some colours have been swapped around on certain stand-alone blocks of text and changed slightly from the original specified colours to allow for features such as the active page in the navbar to be seen as active, the active link bootstrap property changes the text to black.


## Code Validation

### HTML
| File | Screenshot | Passed / Notes |
| --- | --- | --- |
Homepage - index.html | ![Homepage - index.html](/documentation/htmlvalid_Index.PNG) | Yes - no errors |
<br>
About us / bio page - about.html |![About us - about.html](/documentation/htmlvalid_about.PNG) | Yes - no errors|
<br>
Services / Portfolio - services.html | ![Services - services.html](/documentation/htmlvalid_services.PNG) | Yes - no errors |
<br>
Contact us - contactus.html | ![Contact us - contactus.html](/documentation/htmlvalid_contact.PNG) | Yes - no errors |
<br>

### CSS
| File | Jigsaw Validation | Screenshot | Notes |
| --- | --- | --- | --- |
Style.css | Pass: No errors |![Jigsaw.w3.org](/documentation/cssvalid_stylesheet.PNG) | The style.css gave no errors, but when using the direct url to validate, bootstrap and fontawesome will produce errors. |

## Browser Compatibility

I have tested the site on various desktop and mobile browsers, results below:
| Browser | Screenshot | Notes |
| --- | --- | --- |
[Google Chrome](https://www.google.com/chrome) | ![Google Chrome](documentation/googlechrometest.png) | |
<br>

[Mozilla Firefox (Developer Edition)](https://www.mozilla.org/en-GB/firefox/developer/) | ![Mozilla Firefox Screenshot](documentation/mozillafirefoxdevedition.png) | |
<br>

[Microsoft Edge ](https://www.microsoft.com/en-gb/edge) | ![Microsoft Edge Screenshot](documentation/microsoftedgescreenshot.png) | |