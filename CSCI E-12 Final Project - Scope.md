# Site: Team Alex Marathon Challenge

**Team Alex Marathon Challenge** is a charity organization formed to promote awareness vision conditions of children living with cerebral palsy(CP). Team Alex is named for Alex Boudreau who will be running the 2017 Miami Marathon with a team of supporters. Team Alex seeks to raise $5000 for CP related charities. The objective website will be used a focal point to coordinate team members, blog about training status, and track fund raising for CP charities by team participates. A secondary objective of the website will be to implement accessibility, HTML5, and responsive standards. To implement some of the social community and fundraising features of the site I plan to leverage social media tools (FaceBook, Twitter, etc), fund raiser service API's, and developer kits to handle aspects of people's personal or financial data. These SaaS offering will be used to enhance the site while protecting people's data.

***
## Audiences / Personas

### Primary Audience

+ Supporters of Team Alex
+ Team Alex Marathon Challenge participants

### Secondary Audience

+ People seaking to learn about CP causes

***
## Scope

The site will be implement is three iterations. The first iteration is consider the minimal viable product (MVP) and focuses on promotion of Team Alex's marathon event and related charities they will be fundraising on the behalf of. Below is enumeration of each iteration and it's goals  

### Minimal Viable Product

+ **Goal**: Launch an initial web presence. Communicate the website's purpose, details of the organization behind the site, how to contact.
    - Home, Contact Us, and Error pages complete. Integration with social media tools complete.
+ **Non-Funcation Requirements**:
    - Setup domain name
    - Create legal disclamer text and clear delination of charity and event relationships
    - Initial surface design and theme for site structure; include responsive framework
    - Setup GitHub repository for site artifacts and content
    - Create FaceBook or Twitter Page / Group as social media integration point.
    - Use Social Media Feed API to include dynamic content
    - Add Google Analytics to capture user flows
    - Setup CI/CD for automate publishing of site
+  **Technical Implementation**:
    - HTML5
    - SCSS / CSS
    - Javascript (within Browser)
    - Node.js or PHP
    - YAML ( for CI/CD automation)
    - Gulp.js ( task runner for web publish; SCSS, Javascript minification, image optimization, etc.)
    

### Second Iteration

+ **Goal**:  Create training journal blog and expand information about Team Alex Marathon Challenge
    - Journal and About pages completed
+ **Nonfuncation Requirements**:
    - Attempt cross promoting with other related charities; e.g. [Team Hoyt Foundation](http://www.teamhoyt.com/The-Hoyt-Foundation.html)
+  **Technical Implementation**:
    - HTML5
    - SCSS / CSS
    - Javascript (within Browser)
    - Node.js or PHP

### Thrid Iteration

+ **Goal**: Recurit team and financial supporters. Support page will include ways folks can help or participate by joining the marathon run team.
    - Donate and Support pages completed
+ **Nonfuncation Requirements**:
    - Setup Crowdraise fundraising tool
    - Promote site through social media tools and friend & family networks
+  **Technical Implementation**:
    - HTML5
    - SCSS / CSS
    - Javascript (within Browser)

### Future Items for Considers (Unplanned Backlog)

+ Post race content for the site
+ Race Photos
+ Media Relations
+ How to recognize contributors and supporters
+ Role of the site after the event

***
##Structure

Initial site structure for website. Diagram includes a key / legend to indicate which iteration each part of the website will be delivered.

![Site Structure]( /assets/structure.svg?raw=true "Team Alex Marathon Challenge Site Structure")

### Site Content Details
_(P)_ Page, _(C)_ Content Section, or _(A)_ Application
+ Home _(P)_
    - Welcome Message _(C)_
    - Latest Journal Entry _(C)_
    - Social Media Feed _(A)_
+ Training Journal _(P)_
    - Blog entries from team member and Alex's trainers _(C,A)_
+ About Team Alex _(P)_
    - Inspiration _(C)_
    - Miami Marathon _(C)_
    - Charity Information _(C)_
    - Related Sites _(C)_
+ Donate _(P)_
    - Donate via Crowdrise _(C)_  
+ Supporting _(P)_
   - Make a Donation _(C)_
   - Run with Us _(C)_
+ Schedule _(P)_
   - Team  _(C)_
   - 2017 Miami Marathon _(C)_
+ Contact Us _(P)_
   - Contact Form _(A)_
   - Form Submission Response _(A)_
+ Page Not Found _(P)_
+ 'Fail Whale' Page _(P)_
