# OIM3690 Web Technologies - 2022 Spring - Homework 1

**Notice**: all the HTML files required below should be directly under folder _WebTech_.

## 1. Creating _index.html_ (30 points)

Create a page _index.html_ (you can reuse the one you have already created or delete it and start from scratch.) This page should have the following content:

1. A heading "All About _Your Name_" (where _Your Name_ should be replaced with your name) using `<h1>` tag.
2. A subheading "Contact Information" using `<h3>`.
   1. Your GitHub profile page address, any social media profile address and your email using appropriate tags.
   2. Your email must be hyperlinked using email link.
3. A line called "Quick Links" with two hyperlinks titled "About Me" and "My Interests" (or "My Hobbies"). These should take you to the subheading specified in (4) below and to the subheading specified in (5) below. Use using appropriate tags.
4. A subheading called "About Me" using `<h2>`
   1. A paragraph under this subheading describing why you came to Babson and what you plan to do after graduation. This paragraph must contain the word "Babson College" somewhere.
   2. Hyperlink "Babson College" to Babson's website.
   3. Add an image of yourself inside this paragraph. The image file must be under *WebTech/images* folder.
5.  A subheading called "My Hobbies" or "My Interests" using `<h2>`
    1.  A paragraph under this subheading describing your interests/hobbies (using the `<p>` tag). 
    2.  Pick a word that best represents your interests and hyperlink it to a popular website dedicated to this hobby/interest (for example, if your interest is playing tennis, link the word "_tennis_" to [www.usta.com](https://www.usta.com/en/home.html)).
6.  Add horizontal lines above the first subheading and below the last paragraph. 
7.  Add a hyperlink at the bottom of the page, below the last horizontal line, to link this page to *sitemap.html*. The text must read "My Work in WebTech".
8.  Use one or multiple HTML Entities (special characters).

## 2. Styling _index.html_ (20 points)

Style _index.html_ using only **internal** CSS as follows:

1. `<h1>` - any `serif` font, any dark color, and centered on the page.
2. `<h3>` - any `cursive` font, any color of your choice and centered on the page.
3. `<h2>` - any non-standard font using [Google Fonts API](https://developers.google.com/fonts/docs/getting_started), any color of your choice, left-aligned.
4. `<p>` - any `sans-serif` font, any color of your choice, with a size of 1.2em.
5. `<p>` - the first line of each paragraph must be indented by 30px.
6. `<img>` - floated to the left with a margin of 20px all around. Choose `height` (and/or `width`) appropriately. 
7. `<body>` - set a background color (any color), and set the left and right margins to 50px.

## 3. Creating _sitemap.html_ (15 points)

Create a page called _sitemap.html_ (you can reuse the page you have already created or start from scratch.) This page should have the following content:

1. A heading "Work done in WebTech by XXXX" (replace XXXX with your name). Use `<h1>`.
2. Add a horizontal line below the heading.
3. List the following items, one below the other:
   1. Exercise 01 (and hyperlink it your first class work, _ex01.html_).
   2. Exercise 03 (and hyperlink it to the _index.html_).
   3. Exercise 04 (and hyperlink it to _ex04.html_).
   4. Exercise 05 (and hyperlink it to _ex05.html_).
   5. Exercise 06 (and hyperlink it to _ex06.html_).
4. Make sure that each of the hyperlinked documents has a hyperlink back to the sitemap page.
5. Add a horizontal line below this list. 
   - **Challenging version**: Add a horizontal line below this list **without using `<hr>` tag**.
6. Add the image, [_home.jpg_](https://raw.githubusercontent.com/OIM3690/resources/main/templates/images/home.jpg), and hyperlink the image to _index.html_. The image file must be under _WebTech/images_ folder.


## 4. Styling _sitemap.html_(10 points)

Style _sitemap.html_ using only **internal** CSS as follows:

1. `<body>` - set the background to any color of your choice, set the right and left margins to `100px` and `150px` respectively.
2. `<h1>` - any `serif` font, any dark color, and centered on the page.
3. List - any font of your choice, any color, size of 1.2em.
4. The image must have a width of `50px`.
5. **Challenging Question**: change color of horizontal line to any color of your choice.

## 5. Additional Requirements (20 points)
1. You have demonstrated that you can use the online resources, such as 
[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) and [W3Schools](https://www.w3schools.com/), to continue to learn on your own.  
   1. Use an HTML tag or an attribute for an HTML element that we have not covered in class. **Add HTML comment** to describe what new tag you have used and where I can find it.
   2. Use at least one CSS property that we have not covered in class on any element(s). **Add CSS comment** in `<style>` section to describe what style you have used and where I can find it.
2. All words are spelled correctly. 
2. Your pages can pass HTML validation without errors.

---
## Submission (5 points)

1. ***Commit and push*** to GitHub. 
2. Create a release.
   - Use tag version '`hw1`' for this release. You don't need to attach any files. 
   - Learn more about [Managing releases in a repository](https://docs.github.com/en/github/administering-a-repository/releasing-projects-on-github/managing-releases-in-a-repository).
