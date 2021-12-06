# h-event
h-event is a simple, open format for events on the web. h-event is often used with both event listings and individual event pages. h-event is one of several open microformat draft standards suitable for embedding data in HTML.

h-event is the microformats2 update to hCalendar 1.0.

The class h-event is a root class name that indicates the presence of an h-event.

p-name, dt-start, dt-end, p-location, p-summary, and the other h-event property class names listed below define properties of the h-event.

### Properties
* p-name - event name (or title)
* p-summary - short summary of the event
* dt-start - datetime the event starts
* dt-end - datetime the event ends
* dt-duration - duration of the event
* p-description - more detailed description of the event
* WARNING: Proposed to be replaced by e-content (re-used from h-entry)
* u-url - permalink for the event
* p-category - event category(ies)/tag(s)
* p-location - where the event takes place, optionally embedded h-card, h-adr, or h-geo