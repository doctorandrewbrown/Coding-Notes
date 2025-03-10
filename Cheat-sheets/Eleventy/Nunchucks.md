## Specifying Nunchucks as the templating engine
```javascript
module.exports.config = {
	...
	htmlTemplateEngine: "njk",
    ...
};
```
The snippet from the ```eleventy.config.js``` file shows how to configure eleventy to use Nunchucks. This allows you to use eleventy layout files with the ```.html``` 
extension which is really convenient during development with vscode, as you can take advantage of emmet html code completion.
