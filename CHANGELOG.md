# Changelog

## 0.7.1
* Bump `geo-types` to [0.5](https://github.com/georust/polyline/pull/21)

## 0.7.0

* [Relicense to MIT / Apache v2](https://github.com/georust/polyline/pull/18)

## 0.6.0

* [Mark `rand` as a dev-dependency.](https://github.com/georust/polyline/pull/12)
* [Switch to criterion to enable stable benchmarks](https://github.com/georust/polyline/pull/15)

## 0.5.0

* [`decode_polyline()` now accepts a string slice instead of a `String`](https://github.com/georust/polyline/pull/10).

## 0.4.0

* Now accepts either a slice or a vec as argument to encode_polyline.

## 0.3.0

* [Now tests for invalid coordinates in decoded strings](https://github.com/georust/polyline/pull/4)

## 0.2.0

* [Basic error handling for en– and decoding](https://github.com/tmcw/polyline/pull/3): rust-polyline
  now returns a `Result` object, allowing it to handle incorrectly
  encoded polylines.
