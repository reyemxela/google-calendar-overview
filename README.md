# Google Calendar Overview

This project aims to provide a simple way to get a 6-month (or _n_-month) overview of a shared Google Calendar, which can then be displayed on a TV using a Raspberry Pi for example.

Early on, this was just a personal project with a hardcoded setup. But as I was updating a few things, I realized it could be helpful to others, so I decided to add more functionality and make everything configurable.

This runs as a single static .html file, so it can be downloaded and run locally, or you can simply use the hosted version, [https://reyemxela.github.io/google-calendar-overview](https://reyemxela.github.io/google-calendar-overview).

All settings are passed in via URL parameters, for example `[URL]?cols=3&rows=2&calendar=...`  
If no calendar ID is passed in, a simple configuration page is displayed to help generate the correct URL parameters.
