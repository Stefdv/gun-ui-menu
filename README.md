### Under development...
Gun integration not ready yet!
## Gun-ui elements
Gun-Ui is a set of - Polymer -webcomponents that enables you - the frontend developer - to build complex - Gun - applications without writing any ( well...almost) javascript

Every gun-ui- element has just 2 required attributes "soul" and "prop" that will link the element to a certain data-point.

## Purpose of gun-ui-menu
* Build a menu from your Gun data



## Dependencies
Offcourse you'll need [Gun](https://github.com/amark/gun)
Like all Gun-Ui elements, `gun-ui-data-provider` requires `gun-ui` to be placed in your main document.

Please read the [docs for `gun-ui`](https://github.com/Stefdv/gun-ui)



## But Why?
Want to build a CMS ? You can with Gun, and with Gun-Ui it's even easier. Gun-ui-menu builds a menu from your Gun data.

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
 <gun-ui-menu soul="contacts" items="{{myContacts}}"></gun-ui-menu>

```
#### That's it!  No javascript!
