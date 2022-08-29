# HomePage

![Screenshot of HomePage](screenshot.png "Screenshot of HomePage")

This is my personal homepage and the generator for it.
It's styled after a monochrome periodic table and has some simple fade-in animations.

## Generating the home page

To generate the home page you will first need to edit the `content.csv` file.
This file is just a plain CSV file with the first entry being the name and the second being the URL.
All the URLs will be prepended with `https://` before being inserted into the template.
You can also use a blank entry with the URL of `blank`, this will create a invisible chunk to act as spacing.
After you edit `content.csv` you just need to run the python script which will generate a `home.html` and `home.css` file.
Then you can just set the `home.html` file as your home page and you're good to go.