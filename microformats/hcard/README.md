# hCard

Whenever you need to display the contact details of an individual or an organisation, you can use a special set of HTML class attributes defined in a microformat known as h-card.

h-card provides a standardized set of values for the class attribute, used to convey contact information such as names, addresses, telephone numbers, email addresses, IM names, and organisation names (such as work places). It is based on vCard, which is a popular format for contact information used in software such as Microsoft Outlook and the Apple address book.

### Properties
* p-name - The full/formatted name of the person or organization
* p-honorific-prefix - e.g. Mrs., Mr. or Dr.
* p-given-name - given (often first) name
* p-additional-name - other (e.g. middle) name
* p-family-name - family (often last) name
* p-sort-string - string to sort by
* p-honorific-suffix - e.g. Ph.D, Esq.
* p-nickname - nickname/alias/handle
* u-email - email address
* u-logo - a logo representing the person or organization (e.g. a face icon)
* u-photo - a photo of the person or organization
* u-url - home page or other URL representing the person or organization
* u-uid - universally unique identifier, preferably canonical URL
* p-category - category/tag
* p-adr - postal address, optionally embed an h-adr
* Main article: h-adr
* p-post-office-box - post office box description if any
* p-extended-address - apartment/suite/room name/number if any
* p-street-address - street number + name
* p-locality - city/town/village
* p-region - state/county/province
* p-postal-code - postal code, e.g. US ZIP
* p-country-name - country name
* p-label
* p-geo or u-geo, optionally embed an h-geo
* Main article: h-geo
* p-latitude - decimal latitude
* p-longitude - decimal longitude
* p-altitude - decimal altitude
* p-tel - telephone number
* p-note - additional notes
* dt-bday - birth date
* u-key - cryptographic public key e.g. SSH or GPG
* p-org - affiliated organization, optionally embed an h-card
* p-job-title - job title, previously 'title' in hCard 1.0, disambiguated.
* p-role - description of role
* u-impp per RFC4770, new in vCard4 (RFC 6350)
* p-sex - biological sex, new in vCard4 (RFC 6350)
* p-gender-identity - gender identity, new in vCard4 (RFC 6350)
* dt-anniversary