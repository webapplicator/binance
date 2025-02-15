# Changelog

## 1.3.8
-   Optimise local imports.
-   Cleaning, including indentation.
-   Deprecate yarn in favour of npm.
-   Fix tests.
-   Expose utility method for generating custom order ID.
-   Add example on providing custom order ID.
-   Update docs.

## 1.3.7

-   Minor docs tweaks.
-   Update package.json links.

## 1.3.6

-   Bump dependencies. #104, #106, #107, #108.
-   Add depositAddressWithNetwork and allCoinsInformation REST methods. #100

## 1.3.5

-   Fix beautifer issue related to arrays and errors from binance server

## 1.3.4

-   Allow baseUrl override in constructor #46
-   Add requestOptions (proxy support + more) #64
-   Update vulnerable dependencies #73, #81
-   Provide `processFilter()` helper functionality for order prices and amounts #43
-   Fix endless onUserData keep alive timer #85

## 1.3.2/3

-   Add an error handler to the websocket so the process doesn't exit
-   Handle malformed JSON responses in websocket messages

## 1.3.1

-   Fix error handling for callbacks when response is empty, introduced by clock drift changes

## 1.3.0

-   Add the ability to have the library handle system clock drift

## 1.2.2

-   Fix beautification of allTickers event arrays when using combinedStreams

## 1.2.1

-   Fix account function signature so as not to break potential calls when upgrading

## 1.2.0

-   Remove example responses from README for cases where they match the new official docs
-   Update README links to point to new official docs on github
-   Fix onUserData so the keep alive interval requests function properly
-   Use new base url specified in new official docs
-   Add new REST and WebSocket API functionality to include all that's specified in the newest set of documentation

## 1.1.2

-   Add lots of example responses and query parameter details to the README
-   Fix onUserData where the promise wasn't being returned
-   Add travis CI and coveralls

## 1.1.1

-   Minor docs updates
-   Set callback to deliver Error object on non 2XX return codes

## 1.1.0

-   Setup account related APIs with new routes and signing
-   Add allPrices and allBookTickers routes
-   Add withdraw, withdrawHistory, depositHistory and depositAddress routes
-   Setup the recvWindow query string option only to show up on signed routes

## 1.0.3

-   Fix typo for websocket response beautify
-   Properly handle 500 responses from the server which are not JSON
-   Properly set recvWindow query option when passed to the constructor
-   Update readme
-   Update tests for fixes

## 1.0.2

-   Fix readme, remove extraneous file

## 1.0.1

-   Fix automatic timestamp issue

## 1.0.0

-   First release
