# Benchmark Comparison of TypeScript Runtime Type Support Modules

> Write up coming soon...

Compares run time type validation of the following packages:

* [class-validator](https://github.com/typestack/class-validator) + [class-transformer](https://github.com/typestack/class-transformer)
* [io-ts](https://github.com/gcanti/io-ts)
* [runtypes](https://github.com/pelotom/runtypes)
* [ts-json-validator](https://github.com/ostrowr/ts-json-validator)
* [toi](https://github.com/hf/toi)

Note that, "JSON Encode Decode" method is not truly a runtime type checker,
but it is included simply for a sort-of benchmark against other JS operations. It encodes and decodes
the same data object and returns it, without any validation.

## Node 8.x

![Bar Graph - Node 8.x](./results/bar-graph-8.x.svg)

## Node 10.x

![Bar Graph - Node 10.x](./results/bar-graph-10.x.svg)

## Node 12.x

![Bar Graph - Node 12.x](./results/bar-graph-12.x.svg)
