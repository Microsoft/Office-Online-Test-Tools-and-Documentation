
All optional values default to the following values based on their type:

============   ================
Type           Default value
============   ================
Boolean        ``false``
String         The empty string
Integer/Long   Varies; see individual properties for details
Array          Empty array
============   ================

..  important::

    No properties should be set to ``null``. If you do not wish to set a property, simply omit it from
    the response and WOPI clients will use the default value.
