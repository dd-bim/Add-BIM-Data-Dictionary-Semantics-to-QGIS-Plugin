# Feature classification with data dictionary

This plugin can be used to add a classification and additional attributes to features by editing the attribute table in QGIS.
To classify features, a data dictionary API can be queried to retrieve classes and associated attributes from a specific data dictionary.
The plugin is implemented against the buildingSMART Data Dictionary (bsDD), but any data dictionary that follows this API structure can be queried.

If attributes exist, you can assign values to them before adding them to features.
You can select only some features or classify all features in the layer with the same class and attributes.