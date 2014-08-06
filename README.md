`<display-query></display-query>`
==============
[polymer](http://polymer-project.org/)-element for simple media-query if-else without writing CSS

Example:
--------
```
<display-query query="min-width: 700px">
    <div class="yes">
        this content will be shown when matching the media-query
    </div>
    <div class="no">
        this content will be shown when the media-query is not matched
    </div>
</display-query>
```
all elements using class `yes` will be shown when query matches, otherwise all elements with class `no` are shown.

Attributes:
-----------
- `query` media-query
- `display` display type for the element [flex|block|inline], default: block

License:
--------
[MIT](http://bbuecherl.mit-license.org)
