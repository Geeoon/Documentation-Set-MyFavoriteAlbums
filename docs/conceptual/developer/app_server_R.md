<!-- app_server_R.md -->

## app_server.R
The app_server.R file defines the server to be used by Shiny.  The server defined in this file is different from the Shiny library server, as the app_server.R file is specifically for defining how the backend R code should be run by the Shiny server.  Each of the statistical tabs' behavior is programmed here.  My Favorite Album’s default code will call functions defined in other files to compile and serve the statistics.
