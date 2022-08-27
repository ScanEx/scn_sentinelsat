scn-sentinelsat
===========

Forked from `sentinelsat <https://github.com/sentinelsat/sentinelsat>`

Sentinelsat makes searching, downloading and retrieving the metadata of `Sentinel
<http://www.esa.int/Our_Activities/Observing_the_Earth/Copernicus/Overview4>`_
satellite images from the
`Copernicus Open Access Hub <https://scihub.copernicus.eu/>`_ easy.

differences
===========

Remove some features to ensure compatibility with Python2.
Add a lazy_query feature to process search results in chunks. This is useful in case of an unstable internet connection.
