# Code

To denote a word or phrase as code, enclose it in backticks (`).

example :   
`x+y = z;`


## Escaping backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

example:  
``Use `code` in your Markdown file.``

# Code blocks

To create code blocks, indent every line of the block by at least four spaces or one tab.

    <html>
        <head> 
            this is head
        </head>
    </html>


# Fenced code blocks

The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using fenced code blocks. Depending on your Markdown processor or editor, you’ll use three backticks (```) or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines!

example:

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
## Syntax highlight
This feature allows you to add color highlighting for whatever language your code was written in.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


