# NOTE this repo will be updated frequently! 

## Technologies learned🛠️ <br>
### HTML <br>
  `h1`-`h6`, `p`, `ul`, `ol`, `li`, `script`, `a`, `title`, `span`, `div`
  - void tags (they only have an opening tag): <br>
   `img`, `style`, `link`, `hr`, `meta`

### CSS
  `width`, `height`, `color`, `background-color`, `display`, `position`
  
#### Types of CSS: `internal`, `external`, `inline` 
  - internal: Writing the CSS code in the **SAME** HTML file using the `<style></style>` tag. <br>
    Example: <br>
    <style> <br>
      p{ <br>
        color: red; <br>
      } <br>
    </style>
    
  - external: Writing the CSS code in an external file for example `style.css` and we access it with the <link> tag. <br>
    Example: <br>
    `<link rel="stylesheet" href="./style.css"/>` <br>
    note: Inside the href attribute it might be different depending on your file location!
  
  - inline: Writing the CSS code directly in the tag's attribute section using the `style` keyword. <br>
    Example: <br>
    `<p style="color: red;>`
#### CSS NOTES
  - **font-size**
    - 1pt (point) = 1/72nd inch
    - 1px = 1/96th inch
    - 1em = 100% of parent (meaning if the parent is 20px the element will be 20px too)
    - 2em = 200% (meaning if the parent is 20px the element will be 2 x 20px = 40px)
  
  - **display**
    - block (takes up the entire full width of the web page) <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/aff2b44c-df0d-44f3-9927-df4a181ecb26" width=500px>
      
    - inline (only takes up as much width as necessary. It does not start on a new line and allows other elements to appear beside it.)
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/1e86f080-e2f6-41e3-9eda-e2af672b6e3e" width=500px>
    - inline-block (make an element behave like both an inline and a block-level element. It allows the element to flow inline with surrounding content while                     also maintaining block-level properties, such as setting a specific width and height.)
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/0716a631-c872-45ba-bf46-7b59ef6e98ce" width=500px>


  - **position**
    - static
    - relative
    - absolute
    - fixed  
