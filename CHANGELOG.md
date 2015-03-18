## 0.4.0

* Updated for Firebase api v2.2.2

* Deprecated `name` getter on Firebase and DataSnapshot

* Added `key` getter on Firebase and DataSnapshot, replacing `name`

* Added changeEmail()

* Added authAnonymously(), authWithOAuthPopup(), authWithOAuthRedirect()

* Added getAuth() and onAuth() listener

* Added orderByChild(), orderByKey(), orderByValue(), orderByPriority()

* Added equalTo(), limitToFirst(), limitToLast()

* Deprecated `limit` on Query object

* Added `exists` getter to DataSnapshot

* Added several tests

## 0.3.0

* Add createUser(), removeUser() and authWithPassword()
  (thanks to wilsynet)
* AuthResponse.auth was changed to type JsObject

## 0.2.1

* Added new `authWithCustomToken` method (thanks to rayk)
* Deprecate `auth`

## 0.2.0+1

* Updated README to include latest `firebase.js` link.

## 0.2.0

* A number of breaking changes and updates.

* A number of methods are now properties.

## 0.1.1+3

* Fixed up tests.

* Cleaned up library structure.