# To Do

* What if Mountebank is installed elsewhere? We should emit better messages if starting the mb server fails, and make the location configurable. This could be as simple as parameterising it. 
* Does the TCP protocol stuff work? I need to add `endOfRequestResolver` I think, at least.
* Proxy record/playback
* [`https`](http://www.mbtest.org/docs/protocols/https) test - might not work yet! Try [trustme](https://github.com/python-trio/trustme) for the certs.
* Tutorial & guide
* `had_request()` matcher for imposters - deprecate server version?
* CONTRIBUTING.md
