This template creates a HTML5 app that is designed to retrieve and parse a webservice written in PHP. The parsing is done by javascript. It can then be converted to an Android app using the Phonegap build service.

The PHP webservice contains a list of category names, website links and a title. The category names and website links are separated by a semi-colon (;), and each category name, and each website link are separated by a comma (,).

The PHP webservice can be hosted on a remote service and is called everytime the user opens the app. If the webservice cannot be reached (because, for example, the user is offline), then a default set of categories and links is displayed. Each time the webservice successfully returns to the app, the categories and links are automatically updated. The new list of categories and links is then stored in the app using HTML5 storage and thus becomes the new default list. This allows for content to be dynamically updated without the user having to re-download the app.

This particular version of the HTML5 app is designed to be used on an Android device. The links are designed to open in a new window - therefore the link targets are expressed as {openExternal : true}.

The app is built using the Foundation 3 framework and is fully responsive.

Please visit http://jaredblyth.com/apps.php for examples of apps built using this template.