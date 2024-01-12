# CSS Helpers and SASS mixins
These are just me having fun spending a lot of time to save me and others more time in the future. I'll try to add more as I make them. Let me know if you have any requests.

## CSS Helpers
### Debugger
![Screenshot of debugger in action](/assets/debugger.png)
This is WAY better than the standard `border: 1px solid red;`` method. The border adds size, which could shift items in your layout. Better to use outline so layout isn't altered.

### Insecure links
Any link with `target="_blank"` should have a `rel="nofollow noreferrer` for performance and security. This will highlight any external link that doesn't have these.

[Read more or see it in action](https://newvistadigital.com/blog/easy-way-debug-css-and-site-theme-errors)

### Image Missing
![Screenshot of missing image](/assets/image-missing.png)
This is a progressive enhancement for when images are missing. It grabs the `alt` text and provides an explanation of what's going on.

## List of Mixins
* **Funderline** - Fun underline effect for <a> elements
* **Hover** - Simply adds all of the classes for hover effects
* **Material Design** - Gives a card depth effect based on Google's Material Design principals
* **Responsive Video** - Mixin to make embedded videos responsive using human-readable ratios
* **Tooltip Arrow** - Function to generate tooltip using css (including the arrow/pointer)