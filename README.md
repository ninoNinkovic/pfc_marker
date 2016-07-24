# pfc_marker

http://suminus.github.io/pfc_marker

pfc_marker imports edls (cmx3600),csv, dvs clipster-timelines and avid mediacomposer-markers as clip-frame-markers into a existing pfclean-timeline.

```
edl: source- or record-tc only, dissolves are filterd out, tapename mapped as notes

clipster: timeline-markers including names and comments

csv-text: one marker-event per line, timecode separated by the first comma

avid mediacomposer: uses markers exported as textfile, last number shows markerrange
```
timecode-math done with: https://github.com/eoyilmaz/timecode

tc drop/non-drop handling is not implemented, yet.

written in python3.4 and qt5, tested with the pixelfarm pfclean 2014-2015 on windows 7/8/10


