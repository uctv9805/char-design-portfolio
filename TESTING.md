# Testing

## Manual Testing

- I regularly tested elements as I completed them, using the site preview within gitpod I could write the code and then test the site to make sure links worked and the website was responsive.

- I published the page on GitHub pages and then tested the website on different sized devices as well as different brand devices (android/apple/amazon/desktop) 
 to check responsiveness. 

- Let freinds and family visit and use the website and report back any unusual findings or problems. 

- I used Chrome Developer tools to simulate different screen sizes in order to test responsiveness.

## Bugs & Fixes

1. Intended Outcome - Create a Navbar using bootstrap that would be responsive across devices
    - Issue:
        - Could not get the navbar into the correct position and issue with the spacing on the navigation elements, trying to correct was taking up too much time.
    - Solution
        - Created my own Navbar using custom HTML and CSS and used media queries to make it responsive.
    
2. Intended Outcome - Option to download portfolio in 2 different sections on the site. 
    - Issue:
        - The download would work in the preview on GitPod but would not work on deployed site - file could not be found on site.
    - Solution
        - Went back to my code and checked file paths for download which I thought to be correct there was a source missing, reworked code and the download was successful on the deployed site. 

3. Intended Outcome - Have the hero image and animation work across multiple screen sizes.
    - Issue:
        - The animation was causing the hero image to overlap other sections. 
    - Solution:
        - I decided that the animation lost it's impact on smaller screen sizes anyway so decided to remove this feature from smaller screen sizes so that just a fixed image was present and it no longer covered any other elements. 


## Validator Testing

### HTML
No errors were returned on any of the pages when passing through the official W3C validator
- W3C Validator for [Home](https://validator.w3.org/nu/?doc=https%3A%2F%2Fuctv9805.github.io%2Fchar-design-portfolio%2Findex.html)
- W3C Validator for [Gallery](https://validator.w3.org/nu/?doc=https%3A%2F%2Fuctv9805.github.io%2Fchar-design-portfolio%2Fgallery.html)
- W3C Validator for [Contact](https://validator.w3.org/nu/?doc=https%3A%2F%2Fuctv9805.github.io%2Fchar-design-portfolio%2Fcontact.html)
- W3C Validator for [Contact Action](https://validator.w3.org/nu/?doc=https%3A%2F%2Fuctv9805.github.io%2Fchar-design-portfolio%2Fcontactaction.html)

### CSS
When testing using the official jigsaw validator using the URI some errors were raised coming directly from the bootstrap URI, not related to any of my code - I proved this by adding my CSS and ran the validator by direct input and no errros were reported in my code

- Jigsaw Validator for [style.css](http://jigsaw.w3.org/css-validator/validator$link)