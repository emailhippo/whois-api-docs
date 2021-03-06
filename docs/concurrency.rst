.. _contact us: https://help.emailhippo.com

Concurrency
===========

To preserve the operational integrity of the service to all of our customers, there is a maximum concurrency enforced by our systems.

Limits
------
Allowed throughput is **50 WHOIS queries per second**. 

Throughput exceeding these limits will receive HTTP response code 429 (too many request) for subsequent requests for a duration of one minute.


Suggestions on how to manage throughput
---------------------------------------
There are several things that it may be helpful to think about to control throughput so as not to exceed the maximum limits described above such as:

* Test your integration with representative production loads over a period of time. Monitor response codes for any 429's. If you see any 429's please reduce the rate at which your application is querying our servers.
* For applications that can tolerate slight delays in your data processing mesh, consider using queuing infrastructure with a rate controllable processor. Your 'processor' can then schedule picking work of of the queue and submitting requests to our systems at a controllable rate.

Large throughput requirements
-----------------------------
For sustained throughput more than **50 domain queries per second**, please `contact us`_ for options on private, dedicated service.