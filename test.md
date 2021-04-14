# Project Council Culture Test file

[Back to README file](https://github.com/TezBaydu/Milestone-Project-1-Band#readme)

[Council Culture website](https://tezbaydu.github.io/Milestone-Project-1-Band/)

## Contents
1. [Commits](#Commits)
2. [User Story testing](#User-Story-testing)
2. [Code testing](#Code-testing)
3. [Browser testing](#Browser-testing)
4. [Device testing](#Device-testing)
5. [Colour blindness testing](#Colour-blindness-testing)
6. [User testing](#User-testing)

## Commits
- Over 140 commits
- Commits made in as many instances as possible and although not described well to begin with this got better during the length of the project.

[Back to top ⇧](#Project-Council-Culture-Test-file)

## User Story testing

### Music fan
The user is either a current or potential fan and subscriber of many other groups.

* This user wants to:
1. Be able to navigate through the website easily.
    - Fixed top Nav bar and Nav collapsable button showing pages to navigate to.
    - Fixed band logo on top left of nav bar for user to vaigate to home page.
2. Learn about the band members and their influences.
    - Synopsis on Home page.
3. Have an opportunity to listen to the bands music.
    - Snippets of music on Home and Muic pages.
4. Be able to navigate to relevant social links.
    - Footer at bottom of each page with buttons directing to social sites.
5. Have the opportunity to download or listen to music via downloadable sites.
    - Footer contains buttons to download sites and download buttons associated to latest release and albums in Music page.
6. Be able to contact band and be part of newsletter/e-mail contact list.
    - Contact page has a form which has required fields and an enquiry type selection for Newsletter subscription.
7. Be able to find out where and when band is performing in future.
    - Events page shows upcoming events dates, times and links to sites and therefore their locations.

#### Events organiser
This user is an events organiser looking for a punk rock band to be part of a group of bands for an event.

* This user wants to be able to:
1. View past and future events.
    - Events page has quotes of past events and a table of upcoming events.
2. Listen to music.
    - Music snippets give a feel of music and download buttons can direct user to download sites.
3. Contact band with message to help detail requirements.
    - Contact page has a form with required fields and an enquiry type of Band Booking enquiry.
4. View links to social sites for further details.
    - Footer has links to social sites.

#### Journalist
This user is working on a piece about new or current bands breaking the market.

* They want to be able to:
1. View bands history.
    - Home page has brief synopsis of band.
2. Understand what their music is portraying.
    - Synopsis also shows music portrayal.
3. Listen to music.
    - Music buttons provide snippets for immediate listening pleasure.
4. Find which events band have and will perform.
    - Events page has quotes of pas events and a table of upcoming events.
5. Contact band for comment and rights issues.
    - Contact page has a form with required fields and an enquiry type of General enquiry.

#### Web Developer
This user is looking for imagery or influence for another project.

* They want to be able to:
1. Have easy navigation.
    - Fixed top Nav bar and Nav collapsable button showing pages to navigate to.
    - Fixed band logo on top left of nav bar for user to vaigate to home page.
2. Find how the website was created.
    - [README.md](https://github.com/TezBaydu/Milestone-Project-1-Band#Introduction) file created detailing why and how website was created.
    - Contact form can also be used for General enquiries.
3. Be able to see sources for design.
    - [README.md](https://github.com/TezBaydu/Milestone-Project-1-Band#Credits-and-Acknowledgements) file shows credits for design.
4. Be able to make contact with Developer.
    - Contact form can be used for general enquiries.
    - [README.md](https://github.com/TezBaydu/Milestone-Project-1-Band#Deploying-via-GitHub-Pages) has description of cloning and forking and therefore contact can be made via GitHub.
5. Have an opportunity to clone site if wanting to use content.
    - [README.md](https://github.com/TezBaydu/Milestone-Project-1-Band#Cloning-a-repository) has description of cloning.


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
    
    - Test date and time 14/04/2021 00:12
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

    - Test date and time 14/04/2021 00:12
        - Bootstrap errors:
            - Property text-decoration-skip-ink doesn't exist : none
            - Property overflow-anchor doesn't exist : none
        - Warnings (788)
            - unknown vendor extensions in style.css
                - -webkit-optimize-contrast
                - -webkit-center
                - -moz-center
                - -webkit-box-sizing
                - -moz-box-sizing
                - -webkit-font-smoothing
                - -moz-font-smoothing
                - -o-font-smoothing
            - font-awesome warnings
            - bootstrap warnings

                
- Javascript
    - [Extends Class JavaScript validator](https://extendsclass.com/javascript-fiddle.html)
        * Updated to add semicolons where expected
    
    - Test date and time 14/04/2021 00:12
        - Line: 23	Column: 136	
            - Code: !lunar.hasClass(elem, name) && elem.attr('class', (!!elem.getAttribute('class') ? elem.getAttribute('class') + ' ' : '') + name);	
                - Expected an assignment or function call and instead saw an expression.
        - Line 28	Column 64
            - Code: lunar.hasClass(elem, name) && elem.attr('class', remove);	
                - Expected an assignment or function call and instead saw an expression.
 

[Back to top ⇧](#Project-Council-Culture-Test-file)

#### Browser testing

- Tested on Browsershots.org - 18/03/2021
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

- Browsershots.org Test date 12/04/2021 
    - Site no longer in use !

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
    - Tested on Safari with Mentor and only issue found was against events.html where table was longer than site page.
        - Discovered style on location header in table with 48%.
            - Removed style to no visual affect and this may be the cause of Safari issue.
                - Done

[Back to top ⇧](#Project-Council-Culture-Test-file)

#### Device testing
- Responsiveness checks performed during development.
    - Finalised checks via [Responsive design checker](https://responsivedesignchecker.com)
        - Checked on various devices and found issue with Nexus 7 where contacts page wasn't filling to bottom of screen.
            - adjusted quote margin to help fill gap
- Also tested on [Am I responsive](http://ami.responsivedesign.is) and found no issues

[Back to top ⇧](#Project-Council-Culture-Test-file)

#### Colour blindness testing
- Extension RGBlind downloaded for testing against colour blindness Protanopia and Deuteranopia
    - Adjusted Home page h1 to have a contrasting background to work with Protanopia
    - Music page adjustment on album titles as one album title was not working on parts of the page when scrolling via Protanopia testing.
        Given all titles a dark background border to help identify album title, even through colour blindness.

[Back to top ⇧](#Project-Council-Culture-Test-file)

#### User Testing

- Align mobile contact image

- Make buttons slightly bigger for mobile, however still works when small (similar size as letters when typing)
    * Adjusted larger as design has carried on.

- Letter spacing looks much better

- Image behind mobile deflects from form on mobile version 

[Back to top ⇧](#Project-Council-Culture-Test-file)

[Back to README file](https://github.com/TezBaydu/Milestone-Project-1-Band#readme)