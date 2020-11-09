# Supported Methods

Below is a list of methods that Xylem REST services support.
Not all resources will support all methods, but all resources using the methods below MUST conform to their usage.

Method  | Description                                                                                                                | Idempotent
------- | -------------------------------------------------------------------------------------------------------------------------- | -------------
GET     | Return the current value of an object                                                                                      | True
PUT     | Replace an object, or create a named object, when applicable                                                               | True
DELETE  | Delete an object                                                                                                           | True
POST    | Create a new object based on the data provided, or submit a command                                                        | False
HEAD    | Return metadata of an object for a GET response.                                                                           | True
PATCH   | Apply a partial update to an object                                                                                        | False
