# hcalendar
The hCalendar Microformat is closest in terms of usage and, arguably, usefulness to hCard. Just as you may like to keep your contacts’ details up to date and synchronized between your various devices (phone, PDA, and your desktop or laptop computer) and online services (web-based email, contact and calendar services, and so on), you probably feel the same way about calendar events. As with hCard, there’s an existing standard for calendar events, namely the IETF iCalendar standard. This standard underpins calendar applications such as Google Calendar, Lotus Notes, and Apple’s iCal, to name but a few. If you were to save one of these events from your calendar application and view it in a text editor, you’d see the data marked up quite clearly. Let’s see this in action.

### Property list 


Required:
* dtstart
* summary

Optional
* location
* url
* dtend (ISO date), duration (ISO date duration)
* rdate, rrule
* category, description
* uid
* geo (latitude, longitude)
* attendee (partstat, role), contact, organizer
* attach
* status