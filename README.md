# Medium Editor Remove Formats

This extension adds button, that removes not only inline formats, but also converts headers back to paragraphs.

```
npm i --save medium-editor-remove-formats
```

You can also use it without browserify, or with AMD or with RequireJS. But why?

```javascript
const Plain = require('medium-editor-remove-formats')();


new MediumEditor(element, {
    extensions: {
        plain: new Plain({
            label: 'My label'
        })
});

```

## License

MIT of course
