# html.steven
student name:Steven Alfred phiri
student ID:2505612467
github repository url: https://github.com/stephenalfred308-stack/html.steven

Quality Control Hub by Steven Alfred Phiri


Question 2: HTML Elements
1. The 5 Most Challenging Elements
<details> & <summary>: These were tricky because they provide interactive "accordions" natively. Without CSS, making sure the content inside didn't look cluttered when expanded took a few tries.
<fieldset> & <legend>: These are vital for accessible forms. Grouping related inputs (like "Contact Info") and getting the legend to sit correctly on the border is a precise semantic task.
<figure> & <figcaption>: It’s easy to just use <img>, but wrapping them in a figure with a caption for better accessibility and SEO is a more professional approach that requires careful nesting.
<table> (with <thead>, <tbody>, <tfoot>): Tables get complicated quickly. Ensuring the headers stayed aligned with the data rows without CSS to fix the widths required very clean markup.
<datalist>: This provides an "autocomplete" feature for inputs. Linking the id of the datalist to the list attribute of an input was a specific technical hurdle I had to double-check.

2. Semantic Structure
I avoided "div-soup" by using:
<header>: Contained the site title and a <nav> for primary links.
<main>: Wrapped the core unique content of the page.
<section>: Used to break the page into logical chunks (About, Skills, Portfolio).
<article>: Used for individual project descriptions within the Portfolio section.
: Contained the copyright, contact links, and <address> tags.
3. The Most Useful Layout Element
The <table> was surprisingly the most useful. Since I couldn't use CSS Grid or Flexbox, the table allowed me to present complex skill comparisons and data in a readable, structured format that wouldn't just be a vertical wall of text.

Question 3: HTML Attributes
1. Three Essential Attributes
href: Without this, the site is a dead end. It turned my text into a web of navigation.
src: Essential for all media (images) and giving the site a visual identity.
name: Crucial for the <form>. Without the name attribute, the data from input fields wouldn't be sent correctly when the user hits "submit."
2. Class vs. ID
id: I used this as a "unique identifier." For example, each section had a unique ID (e.g., id="contact") so I could create internal "jump links" in my navigation menu.
class: I used these to group elements that shared a common purpose (e.g., class="project-card"), even though I wasn't styling them yet, to prepare the document for future CSS.
3. Improving User Experience
The alt attribute. It’s invisible to most, but for users with visual impairments or slow internet, providing a clear description of images ensures the website remains functional and inclusive for everyone.

Question 4: Development Process
Planning: I used a pen and paper to draw a "wireframe." I listed out the 25 elements I wanted to include first so I didn't forget any "exotic" ones like <abbr> or <mark>.Testing/Debugging: I used the W3C Markup Validation Service. I would paste my code in, and it would point out things like unclosed tags or missing required attributes (like alt for images).
Challenges: The biggest challenge was making the site look organized without CSS. I overcame this by using semantic hierarchy—using <h1> through <h3> properly so the browser’s default styling naturally created a visual flow.

Question 5: Git & GitHub
1. Git Commands
I used a standard workflow:
git init 
git add . 
git commit -m 
git push origin main

Question 6: Code Quality & Best Practices
Validation: I ensured no tags were left hanging and that every attribute had its value in double quotes. I checked for a proper <!DOCTYPE html> and lang="en" attribute.
Clean Code: I used consistent indentation (2 spaces) and included comments (``) to make the code readable for other developers.
Future Improvements: If I had more time, I would implement Meta Tags for better SEO and social media previews, and perhaps experiment with the <canvas> element for a basic interactive drawing area.

Technical Checklist (The "Cheat Sheet")To hit your requirements, ensure your code includes these specific items:25 Elements Used15 Attributes Usedhtml, head, title, body, header, nav, main, section, article, footer, h1, p, em, strong, ul, ol, li, a, img, table, tr, th, td, form, input, label, textarea, button, blockquote, cite, mark, abbrhref, src, alt, id, class, lang, charset, type, value, placeholder, required, name, target, rel, rows, cols
