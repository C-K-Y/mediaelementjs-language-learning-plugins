Mediaelementjs language learning plugins
========================================

A set of plugins for MediaElement (https://github.com/johndyer/mediaelement/) providing tools for language learning sites. The main aim of this project is to create a video player with the same (or better) features as Yabla player (http://www.yabla.com/).

All plugins are based on MediaElement core plugins.

* Trackprogress - advanced progressbar which allows to navigate through the timeline by blocks, where every block is a  sentence retrieved from subtitles.
* Nextprev - navigation between sentences.
* Duration2 - this plugin shows current time and numder of block (sentence).
* Doublesubtitles - shows subtitles for video and allows to interact with each word (see translation).
* Dictionary - allows to translate words from subtitles by clicking on them.

To use plugins just include js and css files to the page and put them to MediaElement settings:

features: ['playpause','timecaption','duration2','trackprogress','prev','next','volume','doublesubtitles','dictionary'],

Demo version is here: http://lang.kece.ru/series/introducing-artifical-intelligence/video/course-welcome
