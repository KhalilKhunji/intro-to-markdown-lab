![Generic Computer Coding Picture](https://images.unsplash.com/photo-1504639725590-34d0984388bd?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
# How to Create an HTML Boilerplate
The foundation of any HTML file is the HTML Boilerplate.
In programs like VSCode, adding a boilerplate is as simple as typing `!`and pressing `Tab` on your keyboard.

However, it's important to know why we always add a boilerplate, and what each part of the boilerplate does!

## The Anatomy of an HTML Boilerplate
There's a variety of HTML Boilerplates you could implement, but a basic one as provided by VSCode looks like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
Let's look at each individual part:
* `<!DOCTYPE html>` - Specifies the document type as HTML.
* `<html lang="en">` - Self-explanatory; the HTML document's language is English! This tag also contains all the html code that well be rendered into the webpage.
* `<head>` - A container for the meta data. This isn't displayed in the web browser when the page is loaded. Web browsers use the information provided in the head to load the page correctly. 
* `<meta charset="UTF-8">` - Specifies the character encoding for the HTML document. In this case, [UTF-8](https://www.utf8.com/).
* `<meta name="viewport" content="width=device-width, initial-scale=1.0">` - A meta tag controlling the size of the window the web page is rendered unto. In this case, it matches the device's width with a 1:1 scale!
* `<title>` - Defines the title of the document. *Hint: You'll see this as the name of the tab on your web browser!*
* `<body>` - Everything inside this tag shows up on the page!

Chances are, you'll always want these elements to be present in every HTML document you make. And if you find yourself adding others (such as links to stylesheets, scripts to javascript files) every time, those will form the additions to your own HTML Boilerplate!

