# OIM3690 Web Technologies - Term Project (subject to changes)

## What is the Term Project?

The term project requires you to conceptualize, design, and implement a website. This is an individual effort. 

The website must be published using following hosts: 
1. GitHub project repository
2. ~~the internal FTP server provided to you by Babson as part of this course~~
3. (Optional) external web host or cloud service (if you want to use backend programs, i.e. PHP or Python.) It is important that the web hosting service must provide ad-free service. 

You will be required to 
1. purchase a domain
2. (optional) use web hosting service. You can
   - pay a hosting fee for the service such as GoDaddy or BlueHost, which is total to about \$10-\$30   
   - or use (free) cloud service such as Heroku, Amazon Web Services (AWS), Google Cloud Platform, or DigitalOcean.

The project is to be developed throughout the term and completed in two intermediate stages plus the final submission. The project must be completed and submitted to the instructor by the last day of class. All intermediate stages must be submitted on the day it is due. Each intermediate deliverable is graded and late submissions are penalized 3 points for every day it is late. Extensions may be granted at the instructor's discretion provided you make the request before the due-date. Every deliverable is mandatory and has to be submitted, even if it is late.

## Examples of Term Project:

Your term project website may be based on any topic that conforms to [Babson's Policy on Terms of Use](https://www.babson.edu/terms-of-use/). Also remember that the course only addresses browser-side development. The course does not cover back-end databases, middleware or e-commerce. So, users will not be able to provide comments on your website that can be stored and retrieved later, upload images or multimedia to your website and, not be able to buy/sell products using your website. You can, however, design your website so that it can be extended to support these features at a later stage (beyond this course).

## Examples of Term Projects (to give you a flavor):

1. travel2hk – a site dedicated to informing travelers about Hong Kong and its attractions. It includes night-life, dining options, sites to see, weather, fashion, and even a converter to covert temperature and currency (between Hong Kong currency and any other currencies of the world).
2. JRC Interiors – a website to support a family-owned interior design business. Besides information about the owners, it also presents a portfolio of projects completed, artwork available for sale and creative ideas for decorating your home/office.
3. The Jaucy Store – a website for making and selling clothing and accessories made from recycled products. It offers a catalog of products that the users can browse and insights into making some of these products.
4. Paulina's DR – a site dedicated to highlighting the lifestyles of people in the Dominican Republic.
5. All About Red Sox – you guessed it and it even has video links to some best moments in history!
6. Tie-Off – a site for the Babson Tie-Off organization that helps international students in Babson improve their logical, analytical and persuasive skills. The site includes pictures from past events, information on how to become a member, events scheduled for the semester/year and details about their executive board.
7. Enzo Ferrari – a website dedicated to the life and inventions of Enzo Ferrari.
8. Trip of the Century – a complete description of places, sights, food and experiences of a student that traveled to Italy on a study-abroad program. It is designed for conveying the student's perspective on the trip and includes a gallery of pictures that you can purchase.

### Things You Can Do:

- Technologies that are covered in this course generally
- All the HTML code must be your own.

### Things You May Not Do:
Some items that are strictly **prohibited** are:

- Adobe Flash files
- Server-side scripts (except for _mailer.php_ and _index.php_).
- JavaScript files that you have not developed
- CSS templates that are not customized 
  - you need to customize it at least by removing all of the CSS elements that you have not used in your website pages.
- Website templates or pages developed by any Content Management Systems (CMS) such as WordPress, Drupal or Joomla.


---

## Getting Started

To start your project, you need to create a **new public** repository in GitHub.

## Project Proposal

- Due: **Friday 9/24/2021, by 11:59 PM**
- This proposal is worth **5 points**.

This is a webpage that answers the following questions:

- What is your website about?
- What is the objective of your website? (Also read as why would this site be important?)
- Who is your target audience?
- What content do you plan to include in each page of your website?

As you think through your website, please remember that the website must have at least 5 pages of content besides the homepage, sitemap, and contact/feedback pages.


### Submission:

- Create a webpage, _proposal.html_, save it to project repository (not **_WebTech_** repository).
- Use necessary CSS to style this page.
- **_Commit/push_** to GitHub.


---
## Project Website Domain

- Due **Thursday 10/7/2021, by 11:59 PM**.
- This part is worth 3 points.

### What you need to do:
- Purchase a domain for your project website (we will cover this part in class).
- [*Publish your website*](https://github.com/OIM3690/resources/blob/main/slides/lec10-publish-website.pdf).
- Test the website with any *index.html*.

### Submission:

- Link your own domain to GitHub pages of project repository. Add [Description and Website](https://stackoverflow.com/a/64942409/941742) to your project repository on GitHub.

- Submit the URL of your website to Canvas.

---
## Project Website Planning

- Due **Sunday 10/10/2021, by 11:59 PM**
- This part is worth 3 points.

### What you need to do:
1. Read [Planning a simple website](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website).
2. Create a folder called "*website-design*" under project repository. This folder should at least contain files for the following items:
   1. Draw a sketch of your project homepage (index.html) as step 2 in the [article](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website). Use any tool such as figma.com, moqups.com, or PowerPoint, or even simply draw on a paper and take a photo.
   2. Create a rough sitemap as step 5 in the [article](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website).


### Submission:

- Save all the files.
- **_Commit/push_** to GitHub.
- Create tag `'plan'` for current release. Learn more on [Managing releases in a repository](https://docs.github.com/en/github/administering-a-repository/releasing-projects-on-github/managing-releases-in-a-repository).

---

## Project First Version

- Due **Wednesday 11/3/2021, by 11:59 PM**
- This first version is worth **45 points**.

This must be your complete website, including all of the content that you expect to have in your final submission. Note, only the content must be in place. JavaScript and jQuery elements are not required for this version. All navigation (links) must be in place. So, please DO NOT TREAT IT LIKE A FIRST DRAFT.


### Grading Rubric:

- Create HTML webpages with contents that support the overall objective, including but not limited to:
  - Use of a table. 
  - Use of a form.
  - Images that are appropriately used and adequate to support the website. 
  - Images are defined using both `alt` and `title`. 
  - Video/YouTube video (optional)
  - Audio file with controls (optional)
  - Homepage should be called _index.html_. 
  - Sitemap page (see sample site map at [Apple Site Map](https://www.apple.com/sitemap)). 
  - Contact page with a feedback form. 
  - At least 3 content pages that are completed with informative and relevant content. 
  - Navigation bar that is located in the same place on each page. 
  - Links to the sitemap page and the contact/feedback page available from the navigation bar or from links at the bottom of the page.
- Create a [favicon](https://developer.mozilla.org/en-US/docs/Glossary/Favicon) and add it to your site. See [how to](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#Adding_custom_icons_to_your_site) and [online favicon generator](https://favicon.io/). 
- Attention to SEO principles. Check out `<meta>` part in [lec10-publish-website](https://github.com/OIM3690/resources/blob/main/slides/lec10-publish-website.pdf).
- Look and feel of your site (use of colors, fonts, backgrounds and consistency of styles across the pages) 
  - This is a relative assessment and is based on how well you have used the combination of external style sheet and internal styles to provide consistency across pages and to differentiate individual pages, in addition to the cheerful and welcoming feel that the website creates based on all the styles.

### Submission:

- Save all the files in project repository.
- **_Commit/push_** to GitHub.
- Create tag `'v1.0'` for current release. Learn more on [Managing releases in a repository](https://docs.github.com/en/github/administering-a-repository/releasing-projects-on-github/managing-releases-in-a-repository).


---

## Project Final Version

- Due **Friday 12/10/2021, by 11:59 PM**
- This deliverable is worth **44 points**.

The final version of the project must have the full set of project files on GitHub and linked to _sitemap.html_ in _WebTech_ repository (both GitHub URL and website domain). If you are using web host/cloud, upload/update all the files to the web host/cloud.


### Grading Rubric:

- Improvement on content and styles.
- JavaScript is used for the following functionalities/effects:
  - Change the text on a page in response to the user's action.
  - Change the style of some element in response to the user's action. 
  - Validate a form.
  - Change image(s) using mouseover and mouseout. 
  - Present a slide-show. (optional, but recommended)
  - Animate something or add some other functionalities besides what is listed above. 
- At least Two pages (including homepage) are mobile compatible.
- Responses to peer review feedback

### Submission:

- Save all the files in project repository.
- **_Commit/push_** to GitHub.
- Create tag `'final'` for this release.
- If you are using web host/cloud, upload/update all the files to the web host/cloud.


---
*updated: 11/01/2021*