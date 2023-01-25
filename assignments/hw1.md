# OIM3690 Web Technologies - 2023 Spring - Homework 1

**Notice**: All the **HTML** files should be located directly under folder _WebTech_.

## 1. Creating _index.html_ (30 points)

Create a page _index.html_. You can reuse the one you have already created or delete it and start from scratch. This page should have the following elements:

1. A heading "All About _Your Name_" (replace _Your Name_ with your actual name) using `<h1>` tag.
2. A section called "Quick Links" using appropriate tag(s). It should also include 4 hyperlinks:
   1.  The first link is "About Me" which should jump to the subheading specified in (3) below.
   2.  The second link is "My Interests" (or "My Hobbies") which should jump to the subheading specified in (4) below.
   3.  The third link is "Contact", which should jump to the section specified in (6) below.
   4.  The fourth link is "Portfolio", which should link to _sitemap.html_.  
3. A section for "About Me. It should include the following elements:
   1. A heading called "About Me" using `<h2>`
   2. Create two paragraphs under this subheading: one paragraph introducing yourself and another paragraph introducing why you came to Babson and what you plan to do after graduation.
   3. The second paragraph must contain the word "Babson College" somewhere. Hyperlink "Babson College" to Babson's website.
   4. Add an image of yourself inside first paragraph. The image file must be located under *WebTech/images* folder.
   5. There is no minimum or maximum number of words for each paragraph, but ensure that the page layout looks balanced (e.g. there should not be a very short paragraph along with a very large image).
4.  A section for "My Hobbies" or "My Interests". It should include the following elements:
    1.  A heading called "My Hobbies" or "My Interests" using `<h2>`
    2.  In clude a paragraph under this subheading describing your interests/hobbies (using the `<p>` tag). 
    3.  Pick a word that best represents your interests and hyperlink it to a popular website dedicated to this hobby/interest - for example, if your interest is playing basketball, link the word "_NBA_" to [www.nba.com](https://www.nba.com).
    4.  Add a relevant image inside the paragraph. The image file could be internal or external.
    5. There is no minimum or maximum number of words for each paragraph, but ensure that the page layout looks balanced (e.g. there should not be a very short paragraph along with a very large image).
5.  Add horizontal lines above the first subheading and below the last paragraph. 
6.  Add a section at the bottom of the page, below the second horizontal line using appropriate tag(s). This bottom section should include the following information: 
    1.  A subheading "Contact Information" using `<h3>`.
    2.  Your name and the course name.
    3.  Your GitHub profile page URL, any social media profile URL (optional) and your email address using appropriate tags. The email must be hyperlinked using email link.
    4.  A hyperlink to *sitemap.html*.
    5.  Any other information you think is appropriate for this section.
7.  Use one or multiple HTML Entities (special characters) somewhere.

## 2. Styling _index.html_ (20 points)

Style _index.html_ using only **internal** CSS as follows:

1. `<h1>` - any `serif` font, any font color, any background color (or background image), and centered on the page.
2. `<h3>` - any `cursive` font, any color of your choice and centered on the page.
3. `<h2>` - any non-standard font using [Google Fonts API](https://developers.google.com/fonts/docs/getting_started), any color of your choice, left-aligned.
4. `<p>` - any `sans-serif` font, any color of your choice, with a size of 1.2em.
5. `<p>` - the first line of each paragraph must be indented by 30px.
6. `<img>` - floated to the left with a margin of 20px all around. Choose `height` (and/or `width`) appropriately. 
7. `<body>` - set a background color (any color), and set the left and right margins to 120px.
8. All the **links** should **not** have underlines.

## 3. Creating _sitemap.html_ (15 points)

Create a page called _sitemap.html_. You can reuse the page you have already created or start from scratch. This page should have the following elements:

1. A heading "Work done in WebTech by _Your Name_" (replace _Your Name_ with your name) using `<h1>` tag.
2. A horizontal line below the heading.
3. A bullet-point list of all HTML pages created, including:
   1. Exercise 01 (and hyperlink it your first class work, _ex01.html_).
   2. Exercise 03 (and hyperlink it to the _index.html_).
   3. Exercise 04 (and hyperlink it to _ex04.html_).
   4. Exercise 05 (and hyperlink it to _ex05.html_).
   5. Exercise 06 (and hyperlink it to _ex06.html_).
4. Add a horizontal line below this list. 
   - **Challenging version**: Add a horizontal line below this list **without using `<hr>` tag**.
5. Add the image, [_home.jpg_](https://raw.githubusercontent.com/OIM3690/resources/main/templates/images/home.jpg), and hyperlink the image to _index.html_. The image file must be located under _WebTech/images_ folder.


## 4. Styling _sitemap.html_(10 points)

Style _sitemap.html_ using only **internal** CSS as follows:

1. `<body>` - set the background to any color of your choice, set the right and left margins to `200px`.
2. `<h1>` - any `serif` font, any dark color, and centered on the page.
3. List - any font of your choice, any color, size of 1.2em.
4. The image must have a width of `50px`.
5. All the **links** should **not** have underlines.
6. **Challenging Question**: change color of horizontal line to any color of your choice.

## 5. Additional Requirements (20 points)
1. Demonstrate that you can use the online resources, such as 
[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) and [W3Schools](https://www.w3schools.com/), to continue learning on your own.  
   1. Use an HTML tag or an attribute for an HTML element that has not been covered in class. **Add an HTML comment** next to the element, describing the new tag/attribute you used and where you learned it from.
   2. Use at least one CSS property that we have not covered in class on any element(s). **Add CSS comment** next to new CSS property(ies) in `<style>` section, describing the new CSS property(ies) you used and where you learned it from.
2. Ensure that all words are spelled correctly.
3. Test your website on different screen sizes to ensure that the website is compatible with different screen sizes and that it looks good on different devices. You can use Chrome's DevTools to check how your website looks on different screen sizes.
4. Ensure that your pages pass HTML validation without errors by using validators like W3C validator.

---
## Submission (5 points)

1. ***Commit and push*** to GitHub. 
2. Create a release.
   - Use tag version '`hw1`' for this release. You don't need to attach any files. 
   - Learn more about [Managing releases in a repository](https://docs.github.com/en/github/administering-a-repository/releasing-projects-on-github/managing-releases-in-a-repository).
