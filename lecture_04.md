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

# Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

example:

[![An old rock in the desert](https://octodex.github.com/images/bannekat.png)](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
