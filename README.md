# NOTE this will be updated frequently! 

## Technologies learned🛠️ <br>
### HTML <br>
  `h1`-`h6`, `p`, `ul`, `ol`, `li`, `script`, `a`, `title`, `span`, `div`
  - void tags (they only have an opening tag): <br>
   `img`, `style`, `link`, `hr`, `meta`

### CSS
  `width`, `height`, `color`, `background-color`, `display`, `position`, `float`, `clear`, `@media`
  
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
      
    - inline (only takes up as much width as necessary. It does not start on a new line and allows other elements to appear beside it.) <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/1e86f080-e2f6-41e3-9eda-e2af672b6e3e" width=500px>
    - inline-block (make an element behave like both an inline and a block-level element. It allows the element to flow inline with surrounding content while                     also maintaining block-level properties, such as setting a specific width and height.) <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/0716a631-c872-45ba-bf46-7b59ef6e98ce" width=500px>


  - **position**
    - static
    - relative
    - absolute
    - fixed
   
  - **float**  
    - left <br><p>
      BEFORE:<br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/0663c868-da33-4a86-9213-78c4c9146627" width=200px> <br>
      AFTER: <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/f6dd7682-9bdd-41f2-b256-df32f8f6f648" width=500px>
     - right <br><p>
      BEFORE:<br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/0663c868-da33-4a86-9213-78c4c9146627" width=200px> <br>
      AFTER: <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/5c6dd494-65c6-4776-b737-ac1bffef2fb2" width=500px> <br>
  - **clear**
    Used when we need to avoid the style effect "float: left" that the element before has. 
     - left <br><p>
      BEFORE:<br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/476358c1-c3c8-47b6-9c2a-0bf948589ad5" width=500px> <br>
      AFTER: <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/9a15498c-6419-4d95-ae03-f7ae3b5d133b" width=500> <br>
    - both <br>
      <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/99149cfd-62ff-4441-816f-0a948acc4147" width=500> <br>
      
  - **@media**
    - max-width: ###px
     BEFORE:<br>
     <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/b11c648a-3b42-406d-a405-ce705593352a" width=500px> <br>
     AFTER: <br>
     <img src="https://github.com/ZYMNZ/WebDev/assets/98342638/24fd9dbd-e4d8-4eff-baf5-70865de0713c" width=500> <br>
