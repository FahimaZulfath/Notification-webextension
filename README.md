# Notification-webextension
A simple web extension which displays a alert notification when click on a link.
This add-on injects JavaScript into web pages. This add-on will not work properly when it's run on pages in the "addons.mozilla.org" domain.


This extension contain two javascript file.

The content script listens for clicks in the page it's attached to. If a click is on a link, the content script sends the link's href to the background script.

The background script listens for this message. When the background script receives the message, it displays a notification containing the href.

The notification's content, as well as the extension's name and description, are localized into German, Dutch, and Japanese, as well as the default en-US.
