MixPanel Component
==================

This is the mixpanel integration library packaged as a 
CommonJS [component](https://github.com/component/component).

Note: The MixPanel integration library requires that it 
be attached to the window on `window.mixpanel` in addition to 
being exported with `module.exports`.

Example:

    var mixpanel = require('mixpanel');
    mixpanel.init('your_token');
