1: gem 'capybara' - Capybara is an integration testing tool. It simulates how a user would interact with a website.

gem 'launchy'  - Launchy is helper class for launching cross-platform applications. Launchy is here to make a common approach to launching external application from within ruby programs.

gem 'rspec'    - RSpec is a behavior-driven development (BDD) framework.  Basically, a tool for testing your code.

gem 'shotgun'  - This gem provides a Guard that restarts Rack apps when watched files are modified similar. (Rack provides a minimal interface between webservers that support Ruby and Ruby frameworks.)


2: This is the bare minimum code for HTML5 assuming you're running javascript and css.
Breakdown of the different lines:

-23: This lines tells the browser what version of HTML we're using.
-24: This line is the opening html tag and also state the language the page will mostly be in.
-25: This line starts the document header (a container for introductory content or a set of navigational links).
-26: This line specifies the character encoding used.
-27: This is the title of your website.
-28: This line is used to link a CSS file and control the contents appearance.
-29: This line enables you to link a JavaScript script to the page.
-30-34: The rest are closing tags


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>title</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
  </head>
  <body>
    <!-- page content -->
  </body>
</html>


3: Assets are a non-source code resource used in your solution.
