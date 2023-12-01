## Themeing DateBox

This section is more of an attempt to explain what the "theme" system actually does - it is nothing more than an automatic class application. In these examples, you will see the defaults are usually:

 1. Based on bootstrap, as thats what the docs use
 2. Are something like "outline-primary"

This is because the bootstrap4 framework is based heavily on bootstrap [Buttons](https://getbootstrap.com/docs/4.3/components/buttons/).  In most cases, the framework file is generating html with a class name of "btn btn-sm btn-" and then appending the "theme" name onto that.  In this example, it would make the full class string "btn btn-sm btn-outline-primary".  Of course, since this is just string concatnation, you can add as many extra classes as you like.  For instance, the ___theme\_cal\_OutOfBounds___ is set to "outline-secondary border-0" to also remove the border on those buttons.

## Icons

Icons in datebox are actually included (new in 5.0.0).  You may pass a known instance name in any icon theme option, or, if you want a custom one, a SVG string.

Known icons:
 - __next__: Next Chevron
 - __prev__: Previous Chevron
 - __plus__: Plus Sign
 - __minus__: Minus Sign
 - __check__: Check Mark
 - __cancel__: X Mark, Cancel, Close
 - __goto__: Goto symbol
 - __clear__: Trash Can
 - __clock__: Clock
 - __calendar__: Calendar


## Theme Options

These are all of the theme related options, a subset from the full options list.

{{run:apiGen.getCatTheme}}