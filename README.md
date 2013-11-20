AppDataRoom-Javascript-Bridge
=============================

Javascript bridge that provides native functionality to web bundles running within App Data Room


#Public Methods:

##sendEmail
  Sends an email via the platform's native mail application

#####Parameters
* to
  * (string) destination email address
* cc
  * (string) carbon copy email address
* subject
  * (string) subject of email
* body
  * (string) body of email
* successCallback
  * (function) function to be called on success
* errorCallback
  * (function) function to be called on error


##getItem
  Gets a value for a specified key from the native local database

#####Parameters
* key
  * (string) key to retrieve
* successCallback
  * (function) function to be called on success
* errorCallback
  * (function) function to be called on error


##setItem
  Sets a value for a specified key to the native local database

#####Parameters
* key
  * (string) key to store
* value
  * (string) value to store
* successCallback
  * (function) function to be called on success
* errorCallback
  * (function) function to be called on error


