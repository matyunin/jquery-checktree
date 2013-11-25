jquery-checktree
================

Simple jquery plugin for checkbox tree.

### Usage:

Now you should include jquery, jquery-checktree plugin and plugins stylesheet. Put this lines in a head.

```html
<script src="http://www.example.com/static/js/jquery.js" type="text/javascript"></script>
<script src="http://www.example.com/static/js/jquery-checktree.js" type="text/javascript"></script>
<link href="http://www.example.com/static/css/jquery-checktree.css" media="all" rel="stylesheet" type="text/css" />
```

This is simple html tree with checkboxes.

```html
<ul id="tree">
   <li><label><input type="checkbox" />Level 1 - 1</label></li>
   <li>
      <label><input type="checkbox" />Level 1 - 2</label>
      <ul>
        <li><label><input type="checkbox" />Level 2 - 1</label></li>
        <!-- ... -->
      </ul>
   </li>
   <!-- ... -->
</ul>
```

Now you can initialize tree.

```js
$('#tree').checktree();
```
