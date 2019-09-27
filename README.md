# Twitch-old-UI
Go back to old dark theme on Twitch


This is a script for Tamper monkey extension.



    // ==UserScript==
    // @name        Twitch old UI style
    // @namespace   english
    // @description Twitch old UI style dark
    // @include     http*://*twitch.tv*
    // @version     1.5
    // @run-at document-start
    // @grant       GM_addStyle
    // ==/UserScript==



    var style = document.createElement('style');
    style.type = 'text/css';
    style.innerHTML = 'h1{font-size:1em!important}div#dfp-directory-banner+div{display:none}.tw-mg-3>div:nth-child(1){display:none}body{--color-background-base:#6441A5;font-family:Helvetica!important}.tw-root--theme-dark body{background-color:#222!important}.tw-c-background-base{background-color:#522A81!important}.tw-root--theme-dark .side-nav__overlay-wrapper{background-color:#181220!important}.tw-root--theme-dark .chat-room{background-color:#202020!important}.tw-root--theme-dark .channel-root__right-column{background-color:#202020!important}.tw-c-text-link .tw-flex-grow-1{flex-grow:1!important}';

    document.getElementsByTagName('head')[0].appendChild(style);


[Donation](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=733STQQTLRD4U&source=url)
