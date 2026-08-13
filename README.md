# Int. HTML && CSS Project: Sign up Form

## Source
- [The Odin Project, Fullstack JavaScript Path, Intermediate HTML && CSS, Project: Sign-up Form](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form)


## Scope
- HTML and CSS, focus on forms and styling
- The base project is to create a web page to resemble the following [template](https://raw.githubusercontent.com/TheOdinProject/curriculum/afdbabfab03fbc34783c6b6f3920aba4a4d3b935/intermediate_html_css/forms/project_sign_up_form/imgs/sign-up-form.png)
- Project scaffolding created with flexbox
- Page responsiveness and JavaScript related validation is not implemented


## Key Reflection Points
- Terminal use

    - working in the terminal to create the project directory structure and for unzipping and moving/copying files

- Google DevTools

    - Due to unexpected sizing issues where my body elements were not equal and some escaping their containers, I decided to redo the project structure and copy over the element information after
    - I slowed down my pace in the 2nd attempt, using DevTools to verify the structure, sizing, and element nesting. This way, when I wrote styles, I was certain it selected the correct target

- Position Property

    - The parent container needs relative position so that a child element with absolute positioning, is only absolute, *inside* their container
    - I noticed the template has the form with a box shadow, and I used relative position to give the form a shadow, even while being flexed (stretching to fill its container)

- Organizing CSS
    - CSS selections fill many lines and in my project redo, I used comments to group sections by flexbox and general styling

## Project Considerations/Logic Errors
- displaying pattern validation for users to see while filling form
- zooming in affects my element sizing, have not yet reached page responsiveness concept


## New Feature Additions
- N/A


## Related Topics/Concepts
- HTML, CSS, flexbox, positioning, forms, linear-gradient, text-transform, font-face, viewport, git, pseudo classes, terminal

## Credits

### Fonts
- Norse font by <a href="https://www.joelcarrouche.com/fonts/norse">Joel Carrouche</a>

### Photos
- Photo by <a href="https://unsplash.com/@heytowner?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">JOHN TOWNER</a> on <a href="https://unsplash.com/photos/empty-concrete-road-covered-surrounded-by-tall-tress-with-sun-rays-3Kv48NS4WUU?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText" target="_blank" rel="noreferrer">Unsplash</a>

### Images/Logos
- <a href="https://raw.githubusercontent.com/TheOdinProject/curriculum/5f37d43908ef92499e95a9b90fc3cc291a95014c/html_css/project-sign-up-form/odin-lined.png" target="_blank" rel="noreferrer">Odin Logo</a>