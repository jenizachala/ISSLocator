# ISSLocator

Program takes a given latitude and longitude as input to compute and display the time, in local time zone, when the ISS will be overhead next time

Implements a <a href = "http://api.open-notify.org/iss-pass.json?lat=29.721670&lon=-95.343631&n=1">JSON</a> parser to pull time at the given location from a web service API

Imported library, <a href = "https://github.com/RomanIakovlev/timeshape">TimeShape</a>, for time zone conversion

Unit tests done using JUnit and Mockito

Uses Jenikins CI for building the project with gradle and code testing

Created with a partner for a Software Design course
