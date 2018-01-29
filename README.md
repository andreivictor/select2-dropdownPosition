# select2 - 'dropdownPosition' option

Extends Select2 v4 plugin by adding an option to set the position of the dropdown.


## Description ##
Select2 automatically places the dropdown, either above or below the element.
In some cases (e.g. mobile devices) it can be a better experience to force the dropdown to a certain position.

This feature was already discussed in the official plugin repository (https://github.com/select2/select2/issues/2710), but hasn't been included yet.

The new `dropdownPosition` can take the following values:

 - `auto` (default) - it uses the old behavior, placing the dropdown either above or below the element, depending on available space,
 - `below` - the dropdown is always displayed below the element;
 - `above` - the dropdown is always displayed above the element.
 
 
 ## Setup ##
Include the script after Select2 main javascript file:
```html
<script src="select2.js"></script>
<script src="select2-dropdownPosition.js"></script>
```

## Usage ##
Initialize the select2 plugin with the `dropdownPosition` option set to `above` or `below`:

```javascript
$("select").select2({
    // other options 
    dropdownPosition: 'below'
});
```


## Demo ##
Demo available on [JsFiddle](https://jsfiddle.net/byxj73ov/). 
