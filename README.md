leption
=======

A Python script to display mpd info on a Roku Soundbridge.  Still
under 'way heavy development.

## Requirements

* Python
* [python-mpd2][2]
* [configobj][3]

## Config file

You'll need a file named `config.ini` that looks like this:

    soundbridge_host = "192.168.0.1"
    soundbridge_port = "4444"
    mpd_host = "192.168.0.2"
    mpd_port = "6600"

leption looks for it in the same directory as leption itself.

## TODO

See notes.org.

## Thanks!

* Thomas Henkel (mypiandme at gmail.com) for the idea and [the
  original code][0]; he was generous enough to let me base my code on his.

* The Random [Javascript Project Name Generator][2] for the name "leption"

[0]: https://myraspberryandme.wordpress.com/2013/06/26/soundbridge-information-display/
[1]: http://mrsharpoblunto.github.io/foswig.js/
[2]: https://pypi.python.org/pypi/python-mpd2
[3]: http://www.voidspace.org.uk/python/configobj.html
