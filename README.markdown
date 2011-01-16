## RedBee Connector

> Version 0.1

## Contributors

* Scott Mebberson <scott@scottmebberson.com>, [http://scottmebberson.com](http://scottmebberson.com) Current Developer

## About

This is an Adobe AIR application that will run on either Windows or Mac, and allows you to test or configure a RedBee device (USB to serial communication only at this point).
To get this working, you'll need to download and install TinkerProxy2 (this dependancy may be removed at a later point in time).

It's still early stages and you can't do a whole lot, see the list below. To get this working, at this point, you'll need to build it yourself with Flash Builder or with the Flex 4 SDK. You'll also need the RedBee-AS3 library, which you can find here https://github.com/smebberson/RedBee-AS3. I'll make a compiled AIR version available shortly.

## Features

*	recieve an asynchronous tag swipe event showing the tag that was swiped, and if it is a saved tag
*	retrieve the firmware version of the RedBee