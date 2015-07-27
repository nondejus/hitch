hitch TLS proxy
===============

[![Build Status](https://travis-ci.org/varnish/hitch.svg?branch=master)](https://travis-ci.org/varnish/hitch)

`hitch` is a network proxy that terminates TLS/SSL connections and forwards the
unencrypted traffic to some backend. It's designed to handle 10s of thousands of
connections efficiently on multicore machines.

See the [web page](https://hitch-tls.org) for more information.


