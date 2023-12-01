JTSage-DateBox
=================

DateBox is a jQuery date and time picker. [Full Documentation and Demos](http://datebox.jtsage.dev/), that works with a multitude of CSS frameworks.


DateBox Features
----------------

DateBox is extreamlly full featured.  Included are:

 * Control to pick date, time, duration, or nearly any combination of the above.
 * Limiting on nearly any criteria on the date, time, or duration.
 * Callbacks and Triggers on create, open, close, change, destroy and several other-progress moments of execution
 * Display as a popover, modal, slide down, or inline control with the form.  Including hiding the actually input element if desired.
 * Ability to output to multiple input elements to send differing formats or parts of the date to the server easily.
 * 4 different visualation modes
    * A calendar
    * Input boxes for each date part with +/- buttons
    * Slidable columns where the date reads right-to-left or left-to-right
    * Slidable weeks where the date reads top-to-bottom
 * Full localization with translations in 40+ languages and locales
 * CSS Framework agnostic.  If there is not a pre-configured version for your preferred choice, adding it is simple.
 * No CSS includes, all styling done by CSS framework or very sparing style hooks.

Special Thanks
--------------

An extra special thanks to [Phill Pafford](http://stackoverflow.com/users/93966/phill-pafford) for answering tons of questions about DateBox, and jQueryMobile in general on StackOverflow.

And last but not least, thanks to all the [contributors](https://github.com/jtsage/jtsage-datebox/contributors) to the project on github.

Downloading
-----------

All scripts are available on the cdn:

DateBox uses the following version scheme:

[http://cdn.jtsage.com/jtsage-datebox/&lt;VERSION&gt;/](http//cdn.jtsage.com/jtsage-datebox/)

#### Latest Versions:

[cdn repo](http://cdn.jtsage.com/jtsage-datebox/latest/)

#### Custom Download Builder:

[script](http://datebox.jtsage.dev/builder/)

Available Options
-----------------

Please see the full api documentation at: [dev.jtsage.com](http://datebox.jtsage.dev/)

Developers
----------

To build locally:

Full lint test, all files : `npm test`

The full release : `npm run release`

Update dist/latest only : `npm run latest`

Run the test suite : `npm run lint`

Build the documentation : `npm run docs`

Run a local server @:8080 for the documentation : `npm run serve`

Run a local version of the builder server: `npm run build-builder && npm run servebuild`

Check the package.json for more options. 

External Libraries
------------------

Most frameworks include a stripped down version of the jQueryUI widget library

Please refere to the licesenses of the included files for details.

Also note, these are copies, not dependancies, so that the maintainer has
more control over version incompatabilities.


