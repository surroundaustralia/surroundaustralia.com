# SURROUND Website
This is the source code for the SURROUND website at https://surroundaustralia.com. It is a Jekyll website so that the files you see here are not ready for deployment to a web server but are source code that Jekyll compiles into the static HTML, image & CSS files that can then be deployed. Files compiled are stored in the _site/ subfolder which isn't included in the version control so much be rebuilt from source as needed.

## Jekly commands
#### new site
`jekyll new . --force`

#### build site
`bundle exec jekyll serve`

### Commands to deploy compiled files via SCP

#### go to compiled files folder
`cd _site`

# zip it
`tar -cf pages.tar *.html`

# ship it
`scp pages.tar kurrawong.net:/home/ubuntu`



# Suggested structure
* Home
    * Products
        * [SOP](sop.md)
            * [Video](sop-video.md)
            * [Details](sop-details.md)
    * Services
    * Research
        * Internet Standards
        * Semantic Data Management
        * eXplainable AI
    * Customers
        * Current Projects
        * Testemonials
    * Partners
    * About Us
        - Out Story
        - Out Team
        - Engagement
    * Contact
        - Form
        - Addresses

**Research**  
Since SURROUND is an R&D-heavy company, it makes sense to advertise our research right at the top level alongside products
