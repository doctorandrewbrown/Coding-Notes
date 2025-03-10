 What is the Nunchucks ```{{ content|safe }}``` filter for?

The Nunchucks templating language automatically "escapes" any ```html``` code when processing markdown files. This means that, unless otherwise instructed, any ```html``` code in content ```.md``` files, will be treated as plain-text and not as html code. So ```<h1>Hello!</h1>``` in a markdown file, would not be rendered as expected in the browser as <h1>Hello!</h1> but literally as ```<h1>Hello!</h1>```. The ```safe``` filter, used when inserting markdown from a ```.md``` file, into an eleventy layout file, allows any ```html``` in the ```.md``` 
file to be rendered normally.
