*This repository is a mirror of the [component](http://component.io) module [alexmingoia/mixpanel-component](http://github.com/alexmingoia/mixpanel-component). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/alexmingoia-mixpanel-component`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
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
