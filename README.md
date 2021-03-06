# KrakenD-contrib

A list of awesome modules and adaptors for the [KrakenD](https://github.com/devopsfaith/krakend) framework.

## Encoding

1. [krakend-xml](https://github.com/devopsfaith/krakend-xml)
2. [krakend-rss](https://github.com/devopsfaith/krakend-rss)

## Service Discovery

1. [krakend-etcd](https://github.com/devopsfaith/krakend-etcd) is an etcd client and subscriber for the KrakenD framework.

## Circuit Breaker

1. [gobreaker](https://github.com/devopsfaith/krakend-circuitbreaker/tree/master/gobreaker) contains an adaptor over the github.com/sony/gobreaker lib
2. [eapache](https://github.com/devopsfaith/krakend-circuitbreaker/tree/master/eapache) is a simple proxy adaptor for the github.com/eapache/go-resiliency/breaker circuit breaker implementation

## Rate-limit

1. [rate](https://github.com/devopsfaith/krakend-ratelimit/tree/master/rate) embeds the golang.org/x/time/rate token bucket implementation into the proxy and router layers
2. [juju](https://github.com/devopsfaith/krakend-ratelimit/tree/master/juju) implements a rate limiter proxy and router using the github.com/juju/ratelimit lib

## Request and response manipulation

1. [krakend-martian](https://github.com/devopsfaith/krakend-martian) injects martian modifiers into the KrakenD proxy pipe

## Caching

1. [krakend-httpcache](https://github.com/devopsfaith/krakend-httpcache) embeds an in-memory caching system that keeps the responses using the time specified in the Cache HTTP headers.

## Security

### OAuth2 client credentials

1. [krakend-oauth2-clientcredentialst](https://github.com/devopsfaith/krakend-oauth2-clientcredentials) offers a proxy.HTTPClientFactory implementation wrapping the golang.org/x/oauth2/clientcredentials lib

### HTTP

1. [krakend-httpsecure](https://github.com/devopsfaith/krakend-httpsecure) wraps the [github.com/unrolled/secure](http://github.com/unrolled/secure) package

## Log

1. [krakend-gologging](https://github.com/devopsfaith/krakend-gologging) offers an improved logger for the [KrakenD](https://github.com/devopsfaith/krakend) framework by adapting the github.com/op/go-logging lib

## Config parser

1. [krakend-viper](https://github.com/devopsfaith/krakend-viper) parse config files from multiple formats

## Metrics and instrumentation

1. [krakend-metrics](https://github.com/devopsfaith/krakend-metrics) contains a set of middlewares for the [KrakenD](https://github.com/devopsfaith/krakend) framework for instrumenting different parts of the pipes.

## CLI

1. [krakend-cobra](https://github.com/devopsfaith/krakend-cobra) integrates the [cobra](github.com/spf13/cobra) lib into the [KrakenD](https://github.com/devopsfaith/krakend) framework
