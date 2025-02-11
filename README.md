# INFO 1300(SP25) - Activity - Theme Practice

In this activity we will practice using CSS classes to enhance our sites theme.

This is a practice activity; not for credit. Feel free to expand as inspired.

## Instructions 

- note the `styles` sub-folder and the `site.css` file inside
  - review these styling rules and observe what they do
  - note that they do all things you did in Lab 3
  - be sure you can read and understand all of these CSS rules 
  
- lets improve the CSS we used to fill an image's width to the browser's width for only the image of downtown Ithaca using the class selector.
  - we started with this code:

            img {
                  display: block;
                  width: 100%;
                  max-width: 800px;
                  min-width: 400px;
            }

            header img {
                  width: auto;
                  min-width: auto;
            }
  - lets use a class to make this more general:
    
            CSS - 

            .fit-width {
                  display: block;
                  width: 100%;
                  max-width: 800px;
                  min-width: 400px;
            }

            HTML - 

            <picture>
                  <img class="fit-width"
                       src="images/downtown-ithaca.jpg"
                       alt="Downtown Ithaca with a view of Cayuga Lake">
            </picture>


- explore other properties
  

## Coding Resources

- **CSS Reference:** [MND CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
  - [MND Text Styling Guide](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Fundamentals)
  - [Colors by Name](https://developer.mozilla.org/en-US/docs/Web/CSS/named-color)
  - [Selectors](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture)
  
## VS Code and Development Server

- **To Code**: Open this repository as a Codespace on GitHub.
- **To View Site**: Start the web server by clicking "Go Live" in the bottom right-hand corner.
  - Once the web server has started, view the website in a web browser by clicking "Open in Browser".
