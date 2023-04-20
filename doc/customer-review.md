# Customer review of the Filarmony project
## Introduction
After submitting the project to the customer, the following issues have been reported as not meeting their original requirements.
In this document, we address these failures and present the solutions that have been implemented for the final deployment.

## __Basic requirements failures__
### __L01__ Design an interactive Front-End web application using HTML and CSS based on the principles of user experience design, accessibility and responsivity.
- __1.4__ Ensure that foreground information is never distracted by backgrounds
    * __Fail:__ Information is varying across different devices
    * __Fix:__ Addressed at L02 basic requirements failures
- __Additional:__
    * The site could be improved further by adding a favicon.
    * There are responsive scroll issues on mobile sized devices
- __Fix:__
    - [x] Add a miningfull favicon
    - [x] Eliminate horizontal scroll-bars.


### __L02__ Test a Front-End web application through the development, implementation and deployment stages
- __2.6__ Use CSS media queries across the application to ensure the layout changes appropriately and maintains the page's structural integrity across device screen sizes.
    - __Fail:__ Doesn’t work well across various devices / screen sizes.
    - __Fix:__ 
        - [x] Size  properly the page main logo for small screen devices
        - [x] Relocate/rechape Navegation menu and content menu for small screen devices
        - [x] Resize the "With-Us" text for small screen devices
- __Additional:__
    * Significant horizontal scrolling is present on mobile and tablet.
- __Fix:__
    - [x] Acomodate screen elements for no horizontal scroll-bars presence.


### __L03__ Deploy a Front-End web application to a Cloud platform
- __Additional:__
    - Git commits could be made more frequently.
    - Git commit messages could be improved.
- __Fix:__ 
    - [ ] Perform commits per source file change as well as per implemented functionality.

### __L04__ Maximise future maintainability through documentation, code structure and organisation
- __4.5__ Organise HTML and CSS code into well-defined and commented sections.
    - __Fail:__  Code comments missing for different sections.
    - __Fix:__ 
        - [ ] Add comments to HTML sections even if they have self explanatory names.
- __Additional:__
    - Significant horizontal scrolling is present on mobile and tablet.
- __Fix:__ 
        - Addressed at L02 basic requirements failures


### __L05__ Demonstrate and document the development process through a version control system such as GitHub
- __Additional:__
    - Some README areas could be improved.
- __Fix:__ TODO

## __Bonus requirements failures__
- __1.3__ Implement a website that provides an excellent solution to the key project goals, demands and expectations.
    - __Fail:__ Responsive issues present
    - __Fix:__ Addressed at L02 basic requirements failures
- __2.1__ Document any bugs found and their fixes and explanation of any bugs that are left unfixed.
    - __Fail:__ Testing steps or guidelines are missing / incomprehensible.
    - __Fix:__ TODO
- __4.1__ Present a clear rationale for the development of the project, in the README, - Key project goals, target audience
    - __Fail:__ README file is lacking in detail for the required sections.
    - __Fix:__ TODO
- __5.1__ Commit often for each feature/fix, ensuring that commits are small and well-defined, with messages that clearly and concisely describe the exact reason for a particular commit.
    - __Fail:__ Commits are regular but description is not clear in some cases.
    - __Fix:__  Addressed at L03 basic requirements failures

