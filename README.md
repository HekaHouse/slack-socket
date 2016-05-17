# slack-socket

`<slack-socket>` Polymer element for managing a web socket connection to Slack RTM API

[API Docs and Demo](https://heka-house-polymer-demos.firebaseapp.com/slack-socket)

[Source](http://github.com/hekahouse/slack-socket/)

## Install

    bower install --save HekaHouse/slack-socket

## Example
    <slack-socket></slack-socket>

Designed to work in conjunction with [slack-auth](https://heka-house-polymer-demos.firebaseapp.com/slack-auth/)

Uses iron-signals to detect slack-access-granted which carries an access token

Also uses iron-signals to detect slack-message-posted which triggers a post to slack

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

slack-socket depends on:

[web-socket](https://github.com/hph/web-socket)

[iron-signals](https://github.com/PolymerElements/iron-signals)

[iron-ajax](https://github.com/PolymerElements/iron-ajax)

## Related

[slack-auth](https://heka-house-polymer-demos.firebaseapp.com/slack-auth/)
