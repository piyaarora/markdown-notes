# Links in markdown

## Inline link
There are two different link types in Markdown, but both of them render the exact same way. The first link style is called an inline link. To create an inline link, you wrap the link text in brackets ( [ ] ), and then you wrap the link in parenthesis ( ( ) ). 

example: Creating hyperlink www.github.com is  [Visit Github](www.github.com)

## Reference link
The other link type is called a reference link. As the name implies, the link is actually a reference to another place in the document. Here's an example of what we mean:

example:
1) Here's [a link to something else][another place].
2) Here's [yet another link][another-link].
3) And now back to [the first link][another place].

[another place]: www.github.com
[another-link]: www.google.com
  
## adding title to a link

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

example:  
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## adding urls and emails

To quickly turn a URL or email address into a link, enclose it in angle brackets(<>).

example:  
<https://www.markdownguide.org>
<fake@example.com>

## Formatting Links
To emphasize links, add asterisks before and after the brackets and parentheses. To denote links as code, add backticks in the brackets.

example:  
I love supporting the **[EFF](https://eff.org)**.  
This is the *[Markdown Guide](https://www.markdownguide.org)*.  
See the section on [`code`](#code).


## Spaces in Link

Markdown applications don’t agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with %20.

[link](https://www.example.com/my%20great%20page)	





