# TRAIN COMPOSITION VIEWER

A simple application that is automatically populated with a live data from the digitrafic-service API build by ReactJS and Babel.

You can find:

* List of [traffic train](https://rata.digitraffic.fi/api/v1/live-trains?station=SLO) to get a list of trains passing by a station code
  Add data json in query parameter e.g `data : { station: "SLO" }`
* Find train compositions by fetched [composition API](https://rata.digitraffic.fi/api/v1/compositions/960?departure_date=2017-05-02)
* Some ideal for styling web.
* Smooth scrolling

# Getting Started

## Installing & Running

It is just a simple app which can see directly from your browser, no need to set up nodejs, no need webpack.
So, download folder then open [`/index.html`](/index.html) with your browser.