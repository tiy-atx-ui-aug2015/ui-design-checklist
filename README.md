# ui-design-checklist
Everything you should do when creating a website/app

# File Structure
- Create a root directory
- Add a css folder with style.css and reset.css/normalize.css
- Add an images folder
- Create an index.html file in the root directory
- Use HTML5 elements

# HTML
- Name your file index.html for the homepage
- Add <!DOCTYPE>
- Add <html> below <!DOCTYPE>, followed by </html>

# The Head and The Body
-  In between your &lt;html&gt; tags, create &lt;head&gt;&lt;/head&gt; tags, followed by &lt;body&gt;&lt;/body&gt; tags

# What goes in the head?
- <title>Your Title Goes Here</title> The title will show up on the tab of your webpage
- Put in your <meta> tag, yo!
- You can link the style sheets you use to the html sheet with the link tag. Ex. link type="text/css" rel="stylesheet" href="style.css"

# SASS
- Use partials to maintain modular pieces of your CSS for organization. For example putting mixins or variables in partial Sass files and import them into the main style sheet.
- Import partial files by putting "@import 'name of your partial here';" at the top of your main style sheet.
- bum lines
- more bum lines

# CSS
- Don't Repeat Yourself
- Keep css code organized, logical, and searchable
- Use comments for other people working on the same project
- Use media queries to create progressive enhancement

# Design/Strategy
- Mobile (Small Screen) First
- Use Media queries with the following syntax:
  "@media screen and (min-width: ___px) {  }"

