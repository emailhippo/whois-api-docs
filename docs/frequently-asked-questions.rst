.. _Click here to signup: https://www.emailhippo.com/contact/
.. _Email Hippo: https://www.emailhippo.com
.. _CloudFlare: https://www.cloudflare.com/
.. _Microsoft Azure: https://azure.microsoft.com

Frequently Asked Questions
==========================

Can I trust you with my data?
-----------------------------
Great question. See :doc:`data-privacy` for more information.

How can I get a key?
--------------------
`Click here to signup`_.

How do I call the API?
----------------------
For a :term:`JSON` response, make a simple GET request to the endpoint. For example, to query domain *microsoft.com* with license key *ABCD1234* call:

::
	
	https://api.whoishippo.com/v1/json/ABCD1234/microsoft.com
	

What comes back from the API?
-----------------------------
:term:`JSON` formatted text over HTTPS.

How reliable is the API?
------------------------
> 99.9% average availability with a defined :term:`SLA`.

Does the system get slower when it's busy?
------------------------------------------
No. All infrastructure is hosted in cloud based platforms with automatic scaling enabled. Automatic scaling kicks in at busy times to provide more hardware resources to meet demand.

Do you cache results?
---------------------
To deliver the speed and reliability demanded by our customers, verification results are cached as follows:

 * **Level 1 cache**: `CloudFlare`_ based. Cache expiration 2 hours.
 * **Level 2 cache**: `Microsoft Azure`_ based. Cache expiration up to 90 days (depends on domain expiry in the :term:`WHOIS` record).

Can I get My Usage in Real-Time?
--------------------------------
Not yet. This feature is in the development pipeline.

How does it work?
-----------------
At a basic conceptual level, the process of querying :term:`WHOIS` services is very simple. First, find the authoritive WHOIS server for a particular :term:`TLD`. Next, connect to the server on port 43, query the domain and capture the response.

The hard bit is dealing with :term:`WHOIS` services that are intrinsically configured to work against the process of querying domains in any form large volume scale. Additionally, the :term:`WHOIS` system does not follow one, unified standard which means that the data 
returned from :term:`WHOIS` services is very difficult to :term:`parse` to anything that is useful for automation or integration purposes.

`Email Hippo`_'s strength in dealing with the \"hard bit\" of the WHOIS system comes from years of experience in solving similar challenges in email verification.

Can I get blacklisted using this API?
-------------------------------------
No. It's `Email Hippo`_ infrastructure that does the work.

Will anyone know that I am quering a domain?
--------------------------------------------
No. It's `Email Hippo`_ infrastructure that does the work.