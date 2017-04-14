# Resume In Markdown 
This repository contains:
* A resume written in markdown.
* Information and files to convert to pdf, docx, or html.

## File Conversion
To convert to other file formats [pandoc][1] is used.  
In addition, a CSS file is used to control the formatting. The [github-like CSS for pandoc][2] is one option.
Place a copy of the target .css file and target it with the pandoc command.

### Command
Use the pandoc command as follows.
```
pandoc resume.md -f markdown -t html -o resume.html --css github-pandoc.css
```

### Storage
The html file may then be placed on a website like github.io.

[1]: http://pandoc.org/
[2]: https://gist.github.com/dashed/6714393
