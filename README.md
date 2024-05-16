adapt-contrib-responsiveIframe
===============================

Allows embedded content inside an ``<iframe>`` tag that will respond to theme breakpoints.


Usage
-----
Once installed, the component can be used to embed content within a course that will respond to the theme breakpoints - small, medium, large and xlarge.

Width and height can be specified for the content at each of these breakpoints.


JSON Format
-----------

Width and height for each breakpoint is set via the ``_width`` and ``_height`` attributes. Each of these contain ``_small``, ``_medium``, ``_large`` and ``_xlarge`` attributes, which correspond to the breakpoint you wish to target.

For example JSON format, see [example.json](https://github.com/LearningPool/adapt-contrib-responsiveIframe/blob/master/example.json)
