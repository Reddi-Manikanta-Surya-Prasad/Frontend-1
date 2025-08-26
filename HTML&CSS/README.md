# Mastering HTML and CSS

---
## Boilerplate:
### <!DOCTYPE html> 
    It is just document type declaration, this is essential for ensuring that the browser to render the page as an html document
### <html lang="en">
    it is the root element of the entire html document lang="en" is an attribute, it represents the basic primary language as English
### <head></head>
    It consists of non visible information
    It consists of Meta tags, Meta tags provide some additional information about the entire document,
    it also consists the title of the page 
### <meta charset="UTF-8"> 
    charset="UTF-8" specifies the character encoding, it is universal character set that includes all the  characters and symbols
### <meta name="viewport" content="width=device-width, initial-scale=1.0">
    It is used to control the view port size and scaling on different devices, specifically for mobiles
### <title>Document</title>
    title tag is used specify the title of the page
### <body></body>
    everything about the content will be included in inside the body
## Tags
   Tags are fundamental building blocks of HTML markup and they are used to define the structure and the content in the HTML.
   There are 3 types of Tags
### 1. Container/Paired/Dual Tags
       -> The container tags define a block of content within html document. They have opening tag and closing tag.
       example <p></p>, <h1></h1>, <div></div>
### 2. Non-Container/Empty/Self-Closing Tags
       -> The Non-Container tags doesn't have any content, these tags are used to insert specific elemens or provide 
       attributes to certain parts of an HTML.
       example: <br>, <hr>, <img>
### 3. Nested Tags
       -> Nested Tags in HTML refer to the situation where one HTML tag is placed inside another HTML tag.
       example: 
       <div>
        <h1></h1>
        <p></p>
       </div>
### Element == Tags+Content
### Attributes
    Attributes in HTML provides an additional information about an HTML element. 
    This additional information could occur the modification eighter the behaviour or the appearance of an element.
    Attributes are always added in the opening tags.
    <p id="para"></p>
    --> Syntax: attributeValue="attributeValue"
### adding image
    <img src="image.png" alt="related to image", title="image-title-to-hover-on-img>
    --> src attribute specifies source url of the media, like image, video or audio.
    --> alt attribute provides the alternate text for images or a fallback content of any other element
    --> title attribute the title of the image shows when hover on the image, it is the kind of advisory information.