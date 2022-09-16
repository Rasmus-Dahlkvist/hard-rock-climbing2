# Hardrock-Climbing!
This is a website for anyone interested in climbing, beginners and experienced climbers alike we learn from each other. 

Link to my [Github Repo](https://github.com/Rasmus-Dahlkvist/hard-rock-climbing2)

Link to my [Live Site](https://rasmus-dahlkvist.github.io/hard-rock-climbing2/)

![am i responsive screenshot](/assets/readme-images/am-i-responsive.png)

## Features
---
### Navigation and header
- At the top center of the page we have our logo **Hardrock-Climbing!**
- The main navigation menu is located just beneath the logo.
- On big screens the navigation menu stretches in a horisontal line and covers the screen width.
- On small screens the navigation menu turns into a dropdown menu with a centered "hamburger icon"
- On desktops and laptops the navigation menu text changes color when hovering over them.
- I also decided to have a large backround image right beneath the navigation menu to set the mood.
- I have used the full image for large screens and a cropped version for small screens.

![navigation bar screenshot](/assets/readme-images/header-screenshot.png)

### Welcome section
This section contains
- Our slogan.
- Explains why you should try climbing.
- And also a quote from Chuck Pratt.

![welcome section screenshot](/assets/readme-images/welcome-section.png)

### Events section
This section contains 
- Text specifying what types of climbing we do.
- Three links to wikipedia where you can read more about those types of climbing.
links:
[Bouldering](https://en.wikipedia.org/wiki/Bouldering)
[Toprope](https://en.wikipedia.org/wiki/Top_rope_climbing)
[Lead](https://en.wikipedia.org/wiki/Lead_climbing)
- On desktops and laptops the links changes color when hovering over them.
- And a table explaining what we do and when.

![events section screenshot](/assets/readme-images/events-section.png)

### Join our email list section
This section contains
- A sign up form where you write your first name last name and email adress.
- The first name field is required.
- The last name field is required.
- The email field is required and will require you to use an email adress
- Submit button to send your form 
- On desktops and laptops the button changes color when hovering over it.

![join our email list screenshot](/assets/readme-images/form-section.png)

### Footer
The footer contains 
- Our contact information with font icons.
- Clickable font icon links to facebook and youtube.

![footer screenshot](/assets/readme-images/footer.png)

## Testing
---
- I have tested this page on big and small screen sizes in Firefox and chrome.
- I have made sure this page looks good and is responsive on standard screen sizes using devtools.

### Bugs
### Fixed bugs
While using devtools my website seemed responsive and worked great with most screen sizes. 
But when i deployed my site to github pages i discovered that
- My site collapsed on itself when using smaller screens.
- Same problem when using windowed mode on desktop.
- My h1 text was separated into two lines on some small screens.
- Only a concern! the table in events is not as responsive as the rest of the site.

I worked on fixing the colapsing problem for three days straight and had huge problems with it.

I think what fixed the colapsing problem was adding min-height: 100%; to the #home, #events, #form and footer in styles.css

And for the h1 i had to change the font size to 100% in media queries.

### Unfixed Bugs
- The problem with setting the h1 font size to 100% in media queries is that on mobile screens it makes the h1 as small as the h2s and i am not very happy about that.
- The table in events has not been a problem on the screens i have tested it on but i am concerned that on some small screens it may not fit 100%.

### Validator Testing
Using W3C validators for testing html and css.
- HTML = Document checking completed. No errors or warnings to show.
- CSS = Congratulations! No Error Found.

Using Lighthouse in devtools for testing accessibility on index.html

![lighthouse screenshot for index.html](/assets/readme-images/lighthouse-test-homepage.png)

Using Lighthouse in devtools for testing accessibility on submitted.html

![lighthouse screenshot for submitted.html](/assets/readme-images/lighthouse-test-thanxpage.png)

## Deployment
---
This site was deployed using github pages.

When you are in the repository you want to deploy:

1. Click on "Settings"
2. Click on "Pages"
3. Find Build and deployment
4. In the Source dropdown menu select "Deploy from a branch"
5. In the Branch dropdown menus select "main" and "/(root)"
6. Click Save
7. Wait 5 minutes 
8. Refresh page
9. Now you should have a link

This is my live link - [Hardrock-Climbing!](https://rasmus-dahlkvist.github.io/hard-rock-climbing2/)

## Fork Repo

When you are in the repository you want to fork:

Locate the "Fork" button on the top right of the page and click it

## Create Local Clone

1. Under the repository name, click on the ‘code’ tab
2. In the clone box, HTTPS tab, click on the clipboard icon
3. In your IED open GitBash
4. Changed the current working directory to the location you want the cloned directory to be made
5. Type ‘git clone’ and then paste the URL copied from GitHub
6. Press enter and the local clone will be created


## Credits
---
### Content
- The code for making the header, navigation bar and hamburger label with dropdown menu was heavily inspired from [Simple Responsive Hamburger Menu With Pure HTML CSS](https://www.youtube.com/watch?v=4996fn82c4c)
- The code for making the times table in the events section was inspired by [W3S HTML Tables](https://www.w3schools.com/html/html_tables.asp) and [W3S CSS Styling Tables](https://www.w3schools.com/css/css_table.asp)
- The code for making the signup form was inspired by [FreeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-html-forms-by-building-a-registration-form/step-62), [W3S HTML Forms](https://www.w3schools.com/html/html_forms.asp) and [W3S CSS Forms](https://www.w3schools.com/css/css_form.asp)
- The code for making the social media font icon links was taken from Code Institutes [Love Running project](https://github.com/Rasmus-Dahlkvist/Love-Running/blob/main/index.html)
- The text font i used was taken from [Google Fonts](https://fonts.google.com/specimen/Rubik+Dirt?query=rubik)

### Image
- The image i used was taken from [Pexels](https://www.pexels.com/photo/person-rock-climbing-3077882/)

### Font Icons
- The font icons i used was taken from [Fontawesome](https://fontawesome.com/icons)

### Color palette
- The colors i used was based on recomendations from [ColorSpace](https://mycolor.space/)

![colorspace screenshot](/assets/readme-images/colorspace-palette-screenshot.png)

### The README.md
Inspiration for writing this readme file.

- The overall layout was taken from Code institutes
