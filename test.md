# Project Council Culture Test file

## Testing

#### Commits
- Commits made in as many instances as possible and although not described well to begin with this got better during the length of the project.

#### Code Testing

- HTML
    - [HTML code checker](https://validator.w3.org/)
    - Initial test highlighted several instances of unsutiable code of which have been updated.
        * Associated to commits on 16th March 2021 and 18th March 2021

- CSS
    - [CSS code checker](https://jigsaw.w3.org/css-validator/)
    - Initial test highlighted several instances of unsutiable code of which have been updated.
        * Associated to commits on 16th March 2021 and 18th March 2021
    * Sorry! We found the following errors (2)
        * URI : https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css
            * 6	abbr[data-original-title], abbr[title]	Property text-decoration-skip-ink doesn't exist : none
            * 6	.accordion	Property overflow-anchor doesn't exist : none
        - This is the code asked to be copied from bootstrap but is showing errors on a couple of styles not encoded.
        - As these are coding issues in bootstrap but doesn't affect website is considered accepatble.

    * Warnings
        * Extensions recognised in browsers but not in validator
        * Considered acceptable as doesn't affect website.

- Javascript
    - [Extends Class JavaScript validator](https://extendsclass.com/javascript-fiddle.html)
        * Updated to add semicolons where expected

#### Browser testing

- Tested on Browsershots.org
    * HTTP_USER_AGENT 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.90 Safari/537.36'
    * One error:
        * Exception Type:	AttributeError
        Exception Value:	'SafeText' object has no attribute 'status_code'
        Exception Location:	/usr/local/lib/python2.7/dist-packages/django/middleware/locale.py in process_response, line 41
        Python Executable:	/usr/bin/python
        Python Version:	2.7.17

        * Looked online in stack overflow and has been answered but involves Django:
            *https://stackoverflow.com/questions/43987462/django-safetext-object-has-no-attribute-get
    - Not consdiered an issue as website is working effectively on all browsers.

#### Device testing
- Responsiveness checks performed during development.
    - Finalised checks via [Responsive design checker](https://responsivedesignchecker.com/)
        - Checked on various devices and found issue with Nexus 7 where contacts page wasn't filling to bottom of screen.
            - adjusted quote margin to help fill gap


#### Colour blindness testing
- Extension RGBlind downloaded for testing against colour blindness Protanopia and Deuteranopia
    - Adjusted Home page h1 to have a contrasting background to work with Protanopia

#### User Testing

- Align mobile contact image

- Make buttons slightly bigger for mobile, however still works when small (similar size as letters when typing)
    * Adjusted larger as design has carried on.