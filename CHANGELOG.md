### 1.12.0
**2017-07-31**

* Merged fix for Collections->Items call

### 1.11.0
**2017-02-16**

* Add support for passing headers to all requests.

### 1.10.0
**2017-02-01**

* Send data as JSON to allow for greater flexibility. In addition, this ensures the new metadata property works as expected.

### 1.9.0
**2016-12-20**

* Ensure PHP 7 compatibility.

### 1.8.0
**2016-12-02**

* Add browse resource with the `all` method.

### 1.7.0
**2016-11-29**

* Add watching resource (an alias to `customers/:id/watching`) with the `items` method.

### 1.6.1
**2016-11-21**

* Fix bug introduced in 1.6.0 that was causing `collections/:id/items` requests to return the wrong response.

### 1.6.0
**2016-11-18**

* Add watchlist resource (an alias to `customers/:id/watchlist`) with `items`, `addItem`, `removeItem` methods.
* Fix bug with analytics resource not loading when initializing the library manually.

### 1.5.1
**2016-10-17**

* Allow passing of collection resource both as the first param or as part of a single params array with key `collection`.

### 1.5.0
**2016-08-19**

* Add analytics resources with `report` method

### 1.4.1
**2016-04-22**

* Fix typos with handleCurlError method

### 1.4.0
**2016-02-18**

* Fix bug with parsing `href`/`id` param
* Add customers `addProduct` and `removeProduct` methods

### 1.3.1
**2016-02-18**

* Update readme intro

### 1.3.0
**2016-02-16**

* Add customers `update` method for updating customers
* Fix bug with using href as param (instead of ID)
* Restore readme to reference `files` (videos resource) and `items` (collections resource)

### 1.2.0
**2016-01-08**

* Add customer delete method
* Alternative methods for collection items (`allItems`) and video files (`allFiles`)

### 1.1.0
**2015-12-22**

* Add methods for products api endpoint
* Fix readme links
* Allow parameters for items methods

### 1.0.1
**2015-12-21**

* Add method for video > files endpoint

### 1.0.0
**2015-12-19**

* Update readme

### 1.0.0-beta.3
**2015-11-28**

* Add composer support
* Add change log

### 1.0.0-beta.2
**2015-11-28**

Fixes glaring issues in the "Initial Beta":

* Use the production API URL!
* Better error handling
* Return associative arrays (not the JSON string from the API)
* Handle API connection timeouts


### 1.0.0-beta
**2015-11-24**

Initial Beta Pre-release
