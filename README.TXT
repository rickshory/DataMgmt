This is an earlier version of a data processsing package further developed as "NDVI-modules". The repository "NDVI-modules" is the more current work, this one should be considered obsolete.

------------
This is the code for generic data management. The immediate purpose is to get the season-long NDVI traces from the data loggers used in the various branches of the Greenlogger project.

 Needs are:
Persistent storage (some kind of database) because the datasets are so large, come in in various pieces and formats, and need post-processing.
Something cross-platform, and an alternative to MS Access which many potential users don't have and/or won't deal with.

 The code is in Python, heavily using the GUI package wxPython.

 The database system is SQLite.
