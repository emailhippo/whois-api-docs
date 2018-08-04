.. _account: https://www.emailhippo.com/contact/
.. _portal: https://portal.emailhippo.com

Quick Start
===========

This quick start guide is designed to get you up and running as fast as possible.

Please follow the steps below in sequence:

1) Create Account
-----------------
Create your `account`_.

2) Try it
---------
Plug your license key into the following 

::

	https://api.whoishippo.com/v1/INSERTYOURLICENSEKEY/microsoft.com
		
Paste the url above into your browser and watch the response come back as in the example below:

::

	{
	  "version": {
		"v": "Enterprise-(1.0.17)",
		"doc": ""
	  },
	  "meta": {
		"recordCreatedDate": "2018-07-20T13:27:04Z",
		"recordUpdatedDate": "2018-07-20T13:27:04Z",
		"recordAge": "0 year(s), 0 months, 2 week(s), 0 day(s), 22 hour(s), 5 minute(s)",
		"recordAgeIso8601": "P14DT22H5M30.7779301S",
		"timeToExpiry": "2 year(s), 8 months, 4 week(s), 1 day(s)",
		"timeToExpirySeconds": 86632045,
		"timeToExpiryIso8601": "P2Y8M29D",
		"tld": "com",
		"domain": "microsoft.com",
		"domainAge": "27 year(s), 3 month(s), 0 week(s), 2 day(s)",
		"domainAgeSeconds": 860225554,
		"domainAgeIso8601": "P27Y3M2D",
		"parseCode": "Success",
		"executionTime": 611
	  },
	  "whoisServerRecord": {
		"recordFound": true,
		"registrar": {
		  "registrarId": "292",
		  "name": "MarkMonitor, Inc.",
		  "whois": "whois.markmonitor.com",
		  "url": "http://www.markmonitor.com",
		  "abuseEmail": "abusecomplaints@markmonitor.com",
		  "abusePhone": "+1.2083895740"
		},
		"dnsSec": "unsigned",
		"domainName": "microsoft.com",
		"tld": "com",
		"domainHandle": "2724960_DOMAIN_COM-VRSN",
		"domainOwnerContact": {
		  "userId": "",
		  "name": "Domain Administrator",
		  "organization": "Microsoft Corporation",
		  "street1": "One Microsoft Way,",
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": "Redmond",
		  "state": "WA",
		  "postalCode": "98052",
		  "country": "US",
		  "phoneNumber": "+1.4258828080",
		  "phoneNumberExt": "",
		  "faxNumber": "+1.4259367329",
		  "faxNumberExt": "",
		  "email": "domains@microsoft.com"
		},
		"adminContact": {
		  "userId": "",
		  "name": "Domain Administrator",
		  "organization": "Microsoft Corporation",
		  "street1": "One Microsoft Way,",
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": "Redmond",
		  "state": "WA",
		  "postalCode": "98052",
		  "country": "US",
		  "phoneNumber": "+1.4258828080",
		  "phoneNumberExt": "",
		  "faxNumber": "+1.4259367329",
		  "faxNumberExt": "",
		  "email": "domains@microsoft.com"
		},
		"billingContact": {
		  "userId": null,
		  "name": null,
		  "organization": null,
		  "street1": null,
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": null,
		  "state": null,
		  "postalCode": null,
		  "country": null,
		  "phoneNumber": null,
		  "phoneNumberExt": null,
		  "faxNumber": null,
		  "faxNumberExt": null,
		  "email": null
		},
		"techContact": {
		  "userId": "",
		  "name": "MSN Hostmaster",
		  "organization": "Microsoft Corporation",
		  "street1": "One Microsoft Way,",
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": "Redmond",
		  "state": "WA",
		  "postalCode": "98052",
		  "country": "US",
		  "phoneNumber": "+1.4258828080",
		  "phoneNumberExt": "",
		  "faxNumber": "+1.4259367329",
		  "faxNumberExt": "",
		  "email": "msnhst@microsoft.com"
		},
		"registrarContact": {
		  "userId": null,
		  "name": null,
		  "organization": null,
		  "street1": null,
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": null,
		  "state": null,
		  "postalCode": null,
		  "country": null,
		  "phoneNumber": null,
		  "phoneNumberExt": null,
		  "faxNumber": null,
		  "faxNumberExt": null,
		  "email": null
		},
		"zoneContact": {
		  "userId": null,
		  "name": null,
		  "organization": null,
		  "street1": null,
		  "street2": null,
		  "street3": null,
		  "street4": null,
		  "city": null,
		  "state": null,
		  "postalCode": null,
		  "country": null,
		  "phoneNumber": null,
		  "phoneNumberExt": null,
		  "faxNumber": null,
		  "faxNumberExt": null,
		  "email": null
		},
		"nameServers": [
		  {
			"Address": "ns3.msft.net"
		  },
		  {
			"Address": "ns1.msft.net"
		  },
		  {
			"Address": "ns2.msft.net"
		  },
		  {
			"Address": "ns4.msft.net"
		  }
		],
		"domainStati": [
		  "clientUpdateProhibited (https://www.icann.org/epp#clientUpdateProhibited)",
		  "clientTransferProhibited (https://www.icann.org/epp#clientTransferProhibited)",
		  "clientDeleteProhibited (https://www.icann.org/epp#clientDeleteProhibited)",
		  "serverUpdateProhibited (https://www.icann.org/epp#serverUpdateProhibited)",
		  "serverTransferProhibited (https://www.icann.org/epp#serverTransferProhibited)",
		  "serverDeleteProhibited (https://www.icann.org/epp#serverDeleteProhibited)"
		],
		"remarks": null,
		"reseller": "",
		"created": "1991-05-02T04:00:00Z",
		"changed": "2014-10-15T11:00:12Z",
		"expiry": "2021-05-03T04:00:00Z",
		"rawResponse": "   Domain Name: MICROSOFT.COM\r\n   Registry Domain ID: 2724960_DOMAIN_COM-VRSN\r\n   Registrar WHOIS Server: whois.markmonitor.com\r\n   Registrar URL: http://www.markmonitor.com\r\n   Updated Date: 2014-10-09T16:28:25Z\r\n   Creation Date: 1991-05-02T04:00:00Z\r\n   Registry Expiry Date: 2021-05-03T04:00:00Z\r\n   Registrar: MarkMonitor Inc.\r\n   Registrar IANA ID: 292\r\n   Registrar Abuse Contact Email: abusecomplaints@markmonitor.com\r\n   Registrar Abuse Contact Phone: +1.2083895740\r\n   Domain Status: clientDeleteProhibited https://icann.org/epp#clientDeleteProhibited\r\n   Domain Status: clientTransferProhibited https://icann.org/epp#clientTransferProhibited\r\n   Domain Status: clientUpdateProhibited https://icann.org/epp#clientUpdateProhibited\r\n   Domain Status: serverDeleteProhibited https://icann.org/epp#serverDeleteProhibited\r\n   Domain Status: serverTransferProhibited https://icann.org/epp#serverTransferProhibited\r\n   Domain Status: serverUpdateProhibited https://icann.org/epp#serverUpdateProhibited\r\n   Name Server: NS1.MSFT.NET\r\n   Name Server: NS2.MSFT.NET\r\n   Name Server: NS3.MSFT.NET\r\n   Name Server: NS4.MSFT.NET\r\n   DNSSEC: unsigned\r\n   URL of the ICANN Whois Inaccuracy Complaint Form: https://www.icann.org/wicf/\r\n>>> Last update of whois database: 2018-07-20T13:26:49Z <<<\r\n\r\nFor more information on Whois status codes, please visit https://icann.org/epp\r\n\r\nNOTICE: The expiration date displayed in this record is the date the\r\nregistrar's sponsorship of the domain name registration in the registry is\r\ncurrently set to expire. This date does not necessarily reflect the expiration\r\ndate of the domain name registrant's agreement with the sponsoring\r\nregistrar.  Users may consult the sponsoring registrar's Whois database to\r\nview the registrar's reported date of expiration for this registration.\r\n\r\nTERMS OF USE: You are not authorized to access or query our Whois\r\ndatabase through the use of electronic processes that are high-volume and\r\nautomated except as reasonably necessary to register domain names or\r\nmodify existing registrations; the Data in VeriSign Global Registry\r\nServices' (\"VeriSign\") Whois database is provided by VeriSign for\r\ninformation purposes only, and to assist persons in obtaining information\r\nabout or related to a domain name registration record. VeriSign does not\r\nguarantee its accuracy. By submitting a Whois query, you agree to abide\r\nby the following terms of use: You agree that you may use this Data only\r\nfor lawful purposes and that under no circumstances will you use this Data\r\nto: (1) allow, enable, or otherwise support the transmission of mass\r\nunsolicited, commercial advertising or solicitations via e-mail, telephone,\r\nor facsimile; or (2) enable high volume, automated, electronic processes\r\nthat apply to VeriSign (or its computer systems). The compilation,\r\nrepackaging, dissemination or other use of this Data is expressly\r\nprohibited without the prior written consent of VeriSign. You agree not to\r\nuse electronic processes that are automated and high-volume to access or\r\nquery the Whois database except as reasonably necessary to register\r\ndomain names or modify existing registrations. VeriSign reserves the right\r\nto restrict your access to the Whois database in its sole discretion to ensure\r\noperational stability.  VeriSign may restrict or terminate your access to the\r\nWhois database for failure to abide by these terms of use. VeriSign\r\nreserves the right to modify these terms at any time.\r\n\r\nThe Registry database contains ONLY .COM, .NET, .EDU domains and\r\nRegistrars.",
		"customFields": null
	  }
	}

.. note:: 	Internet Explorer may prompt to download the file instead of simply displaying it on screen. 
			This is a quirk of Internet Explorer and not an issue with the :term:`API`.
			We do not recommend Internet Explorer for testing with the :term:`API`. Instead, use
			Chrome or Firefox - both will display the results on screen correctly!
