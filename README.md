# Precipa

Precipa is a weather information app designed for the Google App Engine. It relies on Yahoo GeoPlanet and Weather for the temperature and condition, and in Flickr to bring high-resolution, geo-tagged photos related to the conditions outside. Our goal is that if you look for "New York, NY" and it's rainy, the screen shows you a picture of New York City during a rain. That's Precipa.

The picture searching algorithm is a major issue for Precipa, as we need to be certain the picture had to be taken on exteriors, be public, and shows whatever weather condition it needs, and we're putting our efforts on it.

## To-do list
 * Fine-tune the picture searching algorithm, maybe even search a service that serves the purpose better than Flickr (as it's full of badly tagged pics).
 * Develop the phone browser detection and interface.
 * Reorganize the code, and make modifications according to the new Python updates available on App Engine.

You can check the app running in [appspot](http://precipapp.appspot.com)
