### Under development ( 17-01-2018 )
Gun is not yet integrated

## Gun-ui elements
Gun-Ui is a set of - Polymer -webcomponents that enables you - the frontend developer - to build complex - Gun - applications without writing any ( well...almost) javascript

Every gun-ui- element has just 2 required attributes "soul" and "prop" that will link the element to a certain data-point.

## Purpose of gun-ui-menu
* Build a menu from your Gun data

## But Why?
Want to create a CMS ? Or just a 'contacts' list ? Well.. give a 'soul' to 'gun-ui-menu' and it will build your menu for you.

## Dependencies
Offcourse you'll need [Gun](https://github.com/amark/gun)
Like all Gun-Ui elements, `gun-ui-menu` requires `gun-ui` to be placed in your main document.

Please read the [docs for `gun-ui`](https://github.com/Stefdv/gun-ui)

### Installation
( still bower...sorry. When Polymer 3 arrives i will switch to yarn)
```
bower install gun-ui-menu --save
```
import it
```
<link rel="import" href="/bower_components/gun-ui-menu/gun-ui-menu.html">
```
Use it
```
 <gun-ui-menu soul="contacts"></gun-ui-menu>
```
#### That's it!  No javascript!
