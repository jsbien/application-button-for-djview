# External Application Button
Communicate with external applications of your OS through a toolbar button or context menu item.

"External Application Button" extension allows you to define customizable toolbar button and context menu items that can execute external executables by passing command-line arguments of your choice. Using this application, for instance, you can send the current page to another browser or send selected text to a text editor. It is even possible to directly send image URLs to a photo editor of your choice or send download links to an external download manager!

https://github.com/andy-portmen/external-application-button/issues/50

The Djvu format was very popular in digital libraries, but when the NPAPI plugin stopped to be supported viewing online documents in this format became terribly cumbersome (you cannot simply download the document because DjVu keeps the pages in separate files). Your excellent extension is in principle the right solution, but the configuration seems too difficult for a typical DjVu user. It would be also nice to eliminate the need to use the context menu and open the document without asking.
Cf. https://sourceforge.net/p/djvu/feature-requests/100/


    download the entire project from https://github.com/andy-portmen/external-application-button/archive/master.zip
    extract to a local directory and open the firefox folder
    create a new directory called "configs"
    paste your exported config file here and rename it to win.json if you are on a Windows machine.
    open about:debugging#/runtime/this-firefox in a browser tab
    press "Load Temporary Add-on" and point it to the manifest file inside the "firefox" directory.

You must now have a custom EAB extension and the previous config should have been exported to this new installation.

For the extension to actually work, you need to add its custom id (....@temporary-addon) to the list of supported ids of my native client (config.js file) and reinstall the native client;

https://github.com/andy-portmen/native-client/releases/tag/0.9.1
https://github.com/andy-portmen/native-client/blob/master/config.js

### YouTube Preview
[![Preview](https://img.youtube.com/vi/sTOHWbX7dKU/0.jpg)](https://www.youtube.com/watch?v=sTOHWbX7dKU)

### Links
  * Homepage: https://add0n.com/external-application-button.html
  * Chrome Store: https://chrome.google.com/webstore/detail/external-application-butt/bifmfjgpgndemajpeeoiopbeilbaifdo
  * Firefox add-ons: https://addons.mozilla.org/en-US/firefox/addon/external-application/
  * Opera addons: https://addons.opera.com/en/extensions/details/external-application-button/
