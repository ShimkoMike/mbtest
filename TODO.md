# To Do

* [Mountebank 2.6](https://www.mbtest.org/releases/v2.6.0) `PredicateGenerator` [ignore feature](https://www.mbtest.org/docs/api/proxies#proxy-predicate-generators). `PredicateGenerator` needs some love in general.
* What if Mountebank is installed elsewhere? We should emit better messages if starting the mb server fails.
* Does the [TCP](http://www.mbtest.org/docs/protocols/tcp) protocol stuff work? I need to add `endOfRequestResolver` I think, at least.
* Proxy record/playback
* Tutorial & guide
* `had_request()` matcher for imposters - deprecate server version?
* Write a CONTRIBUTING.md
* Builders for Impostors etc.

## CI

* Publish coverage
* Automate Release process

## For 3.0

* Make lots of arguments keyword only.
* Remove anything deprecated.
