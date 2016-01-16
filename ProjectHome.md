## News ##

  * 2013-06-19: [pyev-0.9.0](http://pypi.python.org/pypi/pyev/0.9.0) released. See the [release notes](http://pythonhosted.org/pyev/changes.html#release-0-9-0) for more informations.

  * 2012-01-07: [pyev-0.8.1-4.04](http://pypi.python.org/pypi/pyev/0.8.1-4.04) released. See the [release notes](http://packages.python.org/pyev/changes.html#release-0-8-1-4-04) for more informations.

---


## About pyev ##

Python libev interface.

libev is an event loop: you register interest in certain events (such as a file descriptor being readable or a timeout occurring), and it will manage these event sources and provide your program with events.
To do this, it must take more or less complete control over your process (or thread) by executing the event loop handler, and will then communicate events via a callback mechanism.
You register interest in certain events by registering so-called event watchers, which you initialise with the details of the event, and then hand over to libev by starting the watcher.

libev supports `select`, `poll`, the Linux-specific `epoll`, the BSD-specific `kqueue` and the Solaris-specific `event port` mechanisms for file descriptor events (:py:class:`Io`), Linux `eventfd`/`signalfd` (for faster and cleaner inter-thread wakeup (Async)/signal handling (Signal)), relative timers (Timer), absolute timers (Periodic), timers with customised rescheduling (Scheduler), synchronous signals (Signal), process status change events (Child), and event watchers dealing with the event loop mechanism itself (Idle, Embed, Prepare and Check watchers) and even limited support for fork events (Fork).

It also is quite [fast](http://libev.schmorp.de/bench.html).

libev is written and maintained by Marc Lehmann.

See also: [libev's homepage](http://software.schmorp.de/pkg/libev).


Useful links:

  * [Latest release](http://pypi.python.org/pypi/pyev/)
  * [Documentation](http://pythonhosted.org/pyev/)
  * [Bug reports and feature requests](http://code.google.com/p/pyev/issues/list)
  * [pyev's source code](http://pyev.googlecode.com/) is currently hosted by [Google code](http://code.google.com/) and kept in a [Subversion](http://subversion.apache.org/) repository:
    * [Subversion instructions](http://code.google.com/p/pyev/source/checkout)
    * [Subversion browser](http://code.google.com/p/pyev/source/browse/)