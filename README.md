purescript-strictlypositiveint
==============================

Strictly positive integers (1,2,3,...).

## Usage examples

```purescript
import StrictlyPositiveInt as SPI

a = SPI.fromInt 5
b = a `SPI.plus` (SPI.fromInt 6)
c = b `SPI.minus` SPI.one
d = SPI.toInt c -- 10
```

## Developing

1. Install purescript: `npm install -g purescript`
2. Install  bower: `npm install -g bower`
3. Install pulp: `npm install -g pulp`
4. Install dependencies: `npm install && bower install`
5. Run tests: `pulp test`

## License

Licensed under a MIT license

## Documentation

- Module documentation is [published on Pursuit](https://pursuit.purescript.org/packages/purescript-strictlypositiveint).

