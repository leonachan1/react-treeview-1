
## install

Npm:
```sh
npm install react-treeview
```

Bower:
```sh
bower install react-treeview
```

The CSS file:

```html
<link rel="stylesheet" type="text/css" href="path/to/react-treeview.css">
```

## API

#### &lt;TreeView />

- `collapsed`: whether the node is collapsed or not.
- `defaultCollapsed`: the [uncontrolled](http://facebook.github.io/react/docs/forms.html#uncontrolled-components) equivalent to `collapsed`.
- `nodeLabel`: the component or string (or anything renderable) that's displayed beside the TreeView arrow.
- `itemClassName`: the class name of the `.tree-view_item` div.
- `treeViewClassName`: the class name of the `.tree-view` div.
- `childrenClassName`: the class name of the `.tree-view_children` item div.

TreeViews can be naturally nested.

The extra properties transferred onto the arrow, so all attributes and events naturally work on it.

## Styling
The CSS is flexible, commented and made to be easily customized. Feel free to inspect the demo's classes and check the [short CSS code]
## Build It Yourself/Run the Demos

Build: `npm install && npm run prerelease`

Demos: `npm install && npm start && open http://localhost:3000`

## License

MIT.
