# Project Council Culture Test file

## Testing

#### Commits
- Over 120 commits
- Commits made in as many instances as possible and although not described well to begin with this got better during the length of the project.

#### Code Testing

- HTML
    - [HTML code checker](https://validator.w3.org/)
    - Initial test highlighted several instances of unsutiable code of which have been updated.
        * Associated to commits on 16th March 2021 and 18th March 2021

    - re-test performed 12/04/2021 after adjustments post 18/03/2021
        - index.html: Document checking completed. No errors or warnings to show.
        - music.html: Document checking completed. No errors or warnings to show.
        - events.html: Document checking completed. No errors or warnings to show.
        - contact.html: Document checking completed. No errors or warnings to show.

- CSS
    - [CSS code checker](https://jigsaw.w3.org/css-validator/)
    - Initial test highlighted several instances of unsutiable code of which have been updated.
        * Associated to commits on 16th March 2021 and 18th March 2021
            * Sorry! We found the following errors (2)
                * URI : https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css
                    * 6	abbr[data-original-title], abbr[title]	Property text-decoration-skip-ink doesn't exist : none
                    * 6	.accordion	Property overflow-anchor doesn't exist : none
                        - This is the code asked to be copied from bootstrap but is showing errors on a couple of styles not encoded.
                        - As these are coding issues in bootstrap but doesn't affect website is considered acceptable.

    

    - Re-test performed 12/04/2021 after adjustments post 18/03/2021
        * Sorry! We found the following errors (4)
            -   URI : https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css
                * 6	abbr[data-original-title], abbr[title]	Property text-decoration-skip-ink doesn't exist : none
                * 6	.accordion	Property overflow-anchor doesn't exist : none

            * This is the code asked to be copied from bootstrap but is showing errors on a couple of styles not encoded.
                * As these are coding issues in bootstrap but doesn't affect website is considered acceptable.


        - URI : https://tezbaydu.github.io/Milestone-Project-1-Band/assets/css/style.css
            * 76	.navbar-expand-lg	none is not a flex-basis value : none
            * 81	.navbar-collapse	none is not a flex-basis value : none
                *   values removed from css once found is not required in inspect mode in Chrome.
                * Re-tested again and after borders applied to album titles and No errors found in CSS files.
        
    - Warnings (787): unknown vendor extensions
        * Extensions recognised in browsers but not in validator
        * Considered acceptable as doesn't affect website.
                

    

- Javascript
    - [Extends Class JavaScript validator](https://extendsclass.com/javascript-fiddle.html)
        * Updated to add semicolons where expected

#### Browser testing

- Tested on Browsershots.org - Retested 12/04/2021 and site no longer in use !
    * HTTP_USER_AGENT 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.90 Safari/537.36'
    * One error:
        * Exception Type:	AttributeError
        Exception Value:	'SafeText' object has no attribute 'status_code'
        Exception Location:	/usr/local/lib/python2.7/dist-packages/django/middleware/locale.py in process_response, line 41
        Python Executable:	/usr/bin/python
        Python Version:	2.7.17

        * Looked online in stack overflow and has been answered but involves Django:
            *https://stackoverflow.com/questions/43987462/django-safetext-object-has-no-attribute-get
    - Not considered an issue as website is working effectively on all browsers.

- Firefox (version 87.0)
    - Tested on own version
        - index.html
            - .header-text h1 css width: fit-content not recognised
                - change to max-content
        - music.html
            - .aftermath-mobile-list css max-width: fit-content not recognised.
                - changed to width: max content and text-align: -webkit-center AND -moz-center so works with firefox too
        - events.html
            - .table-section min-width: fit content not needed
                - removed
            - .table height:fit-content 
                - removed
        - contacts.html
            - .darren-quote width: fit-content not recognised
                - changed to width: max content
                - also text-align: -moz-center to centralise in firefox too
            - Form test successful

- Microsoft Edge (version 89.0)
    - Tested on own version of Microsoft Edge (version 89)
        - No link, element or aesthetic issues

- Safari
    - Decided to sign up for free trial on Browserstack.com after stackoverflow advice
        - Design and visual tests successful on mojave, catalina and big sur.
        - Only have 1 minute of free testing so attempted as best as could without having to purchase a package.


#### Device testing
- Responsiveness checks performed during development.
    - Finalised checks via [Responsive design checker](https://responsivedesignchecker.com)
        - Checked on various devices and found issue with Nexus 7 where contacts page wasn't filling to bottom of screen.
            - adjusted quote margin to help fill gap
- Also tested on [Am I responsive](http://ami.responsivedesign.is) and found no issues


#### Colour blindness testing
- Extension RGBlind downloaded for testing against colour blindness Protanopia and Deuteranopia
    - Adjusted Home page h1 to have a contrasting background to work with Protanopia
    - Music page adjustment on album titles as one album title was not working on parts of the page when scrolling via Protanopia testing.
        Given all titles a dark background border to help identify album title, even through colour blindness.

#### User Testing

- Align mobile contact image

- Make buttons slightly bigger for mobile, however still works when small (similar size as letters when typing)
    * Adjusted larger as design has carried on.

- Letter spacing looks much better

- Image behind mobile deflects from form on mobile version 

[Back to README](https://github.com/TezBaydu/Milestone-Project-1-Band#readme)