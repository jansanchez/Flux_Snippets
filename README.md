

# Flux Snippets

> Snippets of Sublime Text for Flux

## Getting Started

#### **Jade:**

-  View

>For example in a file called *new.jade*, we do write 'view' and then press the 'TAB' key.

```js
view
```

And then we get something like this:

```js

extends ../../../layout/layout.jade

//- @view   : new
//- @main   : my_module/account
//- @author : 

block content
    
```

Every time that we press the 'TAB' key, the cursor will displace of line on line.


#### **CoffeeScript:**

-  Add

>For example in a file called *new.coffee* , we do write 'add' and then press the 'TAB' key.

```js
add
```

And then we get something like this:

```js

###
Module description
@class new
@main my_module/account
@author 
###

yOSON.AppCore.addModule "new", (Sb) ->
    
```


#### **Stylus:**

-  Controller

>For example in a file called *new.styl* , we do write 'controller' and then press 'TAB' key.

```js
controller
```

And then we get something like this:

```css

/*!!
 *
 * @controller : affiliation
 * @module     : my_module
 * @author     : 
 *
 */

@require '../../_config/*'
@require '../../_mixins/*'

    
```

-  View

```js
view
```

And then we get something like this:

```css

/*!!
 *
 * @view       : 
 * @controller : affiliation
 * @module     : my_module
 * @author     : 
 *
 */
    
```

