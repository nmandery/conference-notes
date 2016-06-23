Testing web mapping applications and services
=============================================

Web mapping apps
----------------

- selenium with chrome as webdriver
- phantom.js
- the tests are written in python - to seperate them from javascript development and for easier implementation
- Only chrome is tested, issues with other browsers are handled upon user feedback

Web services
------------

- WMSchecker run by jenkins every morning
- https://github.com/geosense/WMSchecker - checks for OGC WMS servers, how they perform
- alternative to WMSchecker: https://github.com/geopython/GeoHealthCheck - Service Status Checker for OGC Web Services
