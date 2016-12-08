# icon-label

A Polymer Element showing an iron-icon and stylized text that is also optionally a link.

### Example
```html
    <icon-label
        icon="icons:polymer"
        icon-style-class="style-class"
        link="http://link"
        target="_blank"
        text="Click Me">
    </icon-label>
```

### Styling

`<icon-label>` provides the following custom properties and mixins for styling:

Custom property           | Description                                 | Default
--------------------------|---------------------------------------------|----------------------
`--icon-label-link-hover` | Style used when hovering over the link      | none
`--icon-label-text`       | Style used with both link and non-link text | none

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install
