# Australian Information Sources & Collection

A focus on Australian specific information sources in the following areas:

 ------------------------------------------------------------------
 ## People

 ### Person Lookup
 https://personlookup.com.au
 - 8 million records
 - Historic address information
   - No Dates as when data was collected
 - Search by name, telephone, street, suburb, post code

### Reverse Australia
https://www.reverseaustralia.com
- Reverse phone number lookup including mobiles
- Allows comments to identify spam callers
- Provider
- Last found

### Whitepages
https://www.whitepages.com.au
- Australian only dataset
- requires vpn if outside of Australia
- Can easily Opt out

### Resumes
- Advanced google search for resume information
- Correlative leads and background locations may be relevan
- "subject" (ext:pfd OR ext:docx) (intitle:"Resume" OR intitle:"CV") (intext:"location" OR intext:"location")
  - E.g. "Andrew Smith" (ext:pfd OR ext:docx) (intitle:"Resume" OR intitle:"CV") (intext:"Sydney" OR intext:"Melbourne")
 
https://exif.regex.info/exif.cgi
- Metadata viewer to identify:
  - Author
  - Creation Location (using timezones)
  - Creation date
- Compare UTC time(z) to timezone map

 ------------------------------------------------------------------
## Travel history

### TripAdvisor
https://www.tripadvisor.com
- Travel Activity
- Pivot on profiles and reviews
  - site:tripadvisor.com/Profile/* "John Doe"
  - site:tripadvisor.com/ShowUserReviews "John Doe"
- Identify others who visited a known location at a correlated time

### Foursquare
https://foresquare.com/explore

https://foresquare.com/search

- Correlate with other travel activity for possible person identification
- Browser photos of user: https://foresquare.com/user/<userid>/photos
 - copy htmp code with the inspect key F12
 - dump into https://codebeautify.org/
  
 ------------------------------------------------------------------
## Assets (vehicles, property)

### Vehicle Searches
- Verify number place to vehicle type
- Identify vehicle type from plate number
- Understand Vehicle rego expiry
- Identify insurance providers for pivoting

https://www.service.nsw.gov.au/transaction/check-vehicle-registration
- Provides:
  - Vehicle type
  - Last 4 of Vin
  - Rego Expiry
  - Insurer & expiry
 
https://www.vicroads.vic.gov.au/registration/buy-sell-or-transfer-a-vehicle/check-vehicle-registration/vehicle-registration-enquiry
- Provides:
  - Vehicle type
  - Full Vin
  - Engine number
  - Rego Expiry
  - Compliance plate date

https://www.service.transport.qld.gov.au/checkrego/application/VehicleSearch.xhtml?dswid=-8228
- Provides:
  - Vehicle type
  - Vehicle Purpose
  - Expiry
  - Full Vin
 
### Property
https://www.realestate.com.au
- Find old listing of subjects property
- Internal imagery
- Hobbies, Siblings, Relationships from photos and Objects
- site:realestate.com.au<address>

https://www.onthehouse.com.au
- Estimated property value
- Analysis for asset ownership and possible financial capability
- Historical sale prices and dates

 ------------------------------------------------------------------
## Judicial

https://cda.courtdata.com.au/login
- National
- Historical criminal court records
- Limited details

https://web.archive.org/web/20201023055056/https://db.ccrau.com/free
- National
- Historical court records and details

https://web.archive.org/web/20200306215203/https://db.socr.com.au/free
- Vic, Tas, SA, WA & NT
- Limited details

https://web.archive.org/web/20230302114651/https://www.courtdata.com.au/
- National
- Provide listing type (i.e AVO)
- Location & case information

Daily Court Lists websites exist and are different for each state

 ------------------------------------------------------------------
## Imagery
https://soar.earth/
- Brings together available free resources
- Excellent interface
- Pivot for paid satellite imagery

https://www.windy.com
- Fixed public cameras
- Comprehensive weather data
- overlays for area awareness
