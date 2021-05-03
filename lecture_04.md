# Images in markdown

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ( ! ).

## 1) inline image link
To create an inline image link, enter an exclamation point ( ! ), wrap the alt text in brackets ( [ ] ), and then wrap the link in parenthesis ( ( ) ).

example: ![image1](https://octodex.github.com/images/bannekat.png)

## 2) Reference image link
You'll precede the Markdown with an exclamation point, then provide two brackets for the alt text, and then two more for the image tag, like this: 

![The founding father][name of the url] At the bottom of your Markdown page, you'll define an image for the tag, like this: [name of the url]: link url

example:
![The founding pic][pic] 

[pic]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
