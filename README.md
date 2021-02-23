# Rockstar: Rocker RStudi0 and Verse images preconfigured with rJava, OpenJDK Java 11, and other packages.

[![License](http://img.shields.io/badge/license-LGPL-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/lgpl-3.0.html) [![LinkedIn](https://raw.githubusercontent.com/thospfuller/awesome-backlinks/master/images/linkedin_32.png)](https://www.linkedin.com/in/thomasfuller/) [![Twitter](https://raw.githubusercontent.com/thospfuller/awesome-backlinks/master/images/twitter_32.png)](https://twitter.com/ThosPFuller) [![GitHub](https://raw.githubusercontent.com/thospfuller/awesome-backlinks/master/images/github_32.png)](https://github.com/thospfuller) [![Email](https://raw.githubusercontent.com/thospfuller/awesome-backlinks/master/images/email_32.png)](http://eepurl.com/b5jPPj) [![Coherent Logic Limited](https://github.com/thospfuller/awesome-backlinks/blob/master/images/CLSocialIconDarkBlue.png?raw=true)](https://coherentlogic.com?utm_source=rockstar_on_gh)

[The *Rockstar project* can be found on *GitHub*](https://github.com/thospfuller/rockstar) and [*Rockstar images* can be found on *DockerHub*](https://hub.docker.com/repository/docker/thospfuller/rockstar-rstudio)

This Rockstar RStudio Dockerfile inherits from [rocker/rstudio](https://hub.docker.com/r/rocker/rstudio/) and contains the following:
- rJava and OpenJDK 11
- drat
- RJSONIO
- packrat
- xml2
- roxygen2
- devtools
- logging

Note also that the _rstudio_ user has been added to the sudo group.

Rockstar is used by the RCOBOLDI ( R COBOL Data Integration) Package which is an R package for importing COBOL CopyBook data into the R Project as data frames.

Rockstar can also be helpful for data scientists or data engineers who need to use R with RJava. The rJava package can be slightly involved to set up and the Rockstar RStudio Dockerfile will help you get past this. The Rockstar RStudio Dockerfile can also act as a referece for engineers that need to configure rJava with a JDK or JRE.
