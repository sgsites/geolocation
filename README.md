SGSITES Geolocation API
===========
IP Geolocation API

Provides the ability to get the location of an IP address.

Base API Url:	http://api.sgsites.net/
Secure API Url:	https://sgsites.net/api/


Prefix:	geolocation/ [GET: { Optional: IP }]


GET values

[ IP ]	Optional attribute. The following GET value specifies the IP address, for which SGSITES will make a lookup. If left blank, SGSITES will use the remote IP address. Note: Information for private IPs and localhost IPs cannot be retrieved.


Output

The service will output as a xml document and will return a <error> tag with description on error.

Example

With the following example, we will retrieve information about 204.202.20.2:
http://api.sgsites.net/geolocation/?IP=204.202.20.2.

Limitations

Access to this API is provided unrestricted, without the use access tokens. Unlimited requests are served.

Copyright

Attribution to the SGSITES Technologies or to the EOHP Corporation is required in accordance with the Terms of Use. The service can be used for informational purposes only.
