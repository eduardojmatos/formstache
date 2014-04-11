Formstache.js
============

A JavaScript component to work with html forms.

___

## Dependencies

To work better with DOM, we choose [jQuery](http://jquery.com/) for manipulations, so, you need append it in `<head/>` before **formstache.js**.

To validations, we use [jQuery Validation](http://jqueryvalidation.org/) for validate inputs. See below more details about this feature.

___

## How this works

There is two ways for this component works, via data attributes or calling by JavaScript.

Both needs `formstache.js` appended between `<head/>` tag.

___

### Via data attributes

Set the primary data attributes, like:

    <form action="url/to/post" method="post" data-formstache="true">

      <input type="text" id="form_full_name" name="form_full_name" data-name="Complete Name" data-required="true" data-type="text" />

      <input type="submit" value="Send" />

    </form>

___

### Via JavaScript

Call function, passing same parameters, like:

    $('.my-pretty-form').formstache();
