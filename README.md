## Texas Fundaraising website

A simple website for tracking donations from Urban Institue Centers to mutual aid groups in Texas to provide support for those affected by the recent winter storms. See [here](https://ajjitn.github.io/texas-fundraising-urban/web_report.html) for the website and more details on our fundraising effort.

The website itself is built with Rmarkdwon + Github pages. The Rmarkdown is mostly text, with some data being read in from Google sheets with `library(googlesheets4)`. This repo also uses Github Actions to automatically render the Rmarkdown every 8 hours (ie 8 AM, 4 PM and 12:00 AM) as people update the Google sheet with fundraising totals.