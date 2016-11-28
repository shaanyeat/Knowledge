### Install Semantic UI
Semantic UI is available in an eponymous package on NPM
```bash
npm install semantic-ui --save
cd semantic/
gulp build
```

### Include in Your HTML
Running the gulp build tools will compile CSS and Javascript for use in your project. Just link to these files in your HTML.

```html
<link rel="stylesheet" type="text/css" href="semantic/dist/semantic.min.css">
<script src="semantic/dist/semantic.min.js"></script>
```
