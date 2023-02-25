# Replication code for "We Don't Have Nearly Enough Startups"

This presentation summarizes the findings from the following essays:
* [It's Valuations (Almost) All the Way Down](https://whoisnnamdi.com/its-valuations/)
* [Old Valuations Die Hard](https://whoisnnamdi.com/old-valuations/)
* [We Don't Have Nearly Enough Startups](https://whoisnnamdi.com/not-enough-startups/)

Notes:
* You'll need a an [api key](https://fred.stlouisfed.org/docs/api/api_key.html) for the `fredr` package in order to pull the data for US GDP and the Nasdaq index. Import the library and set the api key for your environment using `fredr_set_key("API_KEY")` before running the rest of the code
* PDF presentation can be generated by using the `Knit` functionality within RStudio
* Credit for the [Beamer theme](https://github.com/ambropo/JambroBeamerTheme) goes to [Ambrogio Cesa-Bianchi](https://sites.google.com/site/ambropo/home)