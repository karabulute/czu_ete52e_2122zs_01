# hReview
This document represents a draft microformat specification. Although drafts are somewhat mature in the development process, the stability of this document cannot be guaranteed, and implementers should be prepared to keep abreast of future developments and changes. Watch this wiki page, or follow discussions on the #microformats Freenode IRC channel to stay up-to-date.

hReview is a simple, open, distributed format, suitable for embedding reviews (of products, services, businesses, events, etc.) in HTML, XHTML, Atom, RSS, and arbitrary XML. hReview is one of several microformats open standards.

### Property list 

* summary. optional. text.
* item type. optional. product | business | event | person | place | website | url.
* item info. required. fn (url || photo ) | hCard (for person or business) | hCalendar (for event)
* reviewer. optional. hCard.
* dtreviewed. optional. ISO8601 absolute date or date time. Use Value Class Pattern if necessary especially for accessibility. (http://www.w3.org/TR/NOTE-datetime)
* rating. optional. fixed point integer [1.0-5.0], with optional alternate worst (default:1.0) and/or best (default:5.0), also fixed point integers, and explicit value.
* description. optional. text with optional valid HTML markup.
* tags. optional. keywords or phrases, using rel="tag", each with optional rating.
* permalink. optional, using rel-design-pattern and rel-self.
* license. optional, using rel="license".