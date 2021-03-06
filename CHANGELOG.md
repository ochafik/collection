## 1.4.0

* Add a `new PriorityQueue()` constructor that forwards to `new
  HeapPriorityQueue()`.

* Deprecate top-level libraries other than `package:collection/collection.dart`,
  which exports these libraries' interfaces.

## 1.3.0

* Add `lowerBound` to binary search for values that might not be present.

* Verify that the is valid for `CanonicalMap.[]`.

## 1.2.0

* Add string comparators that ignore ASCII case and sort numbers numerically.

## 1.1.3

* Fix type inconsistencies with `Map` and `Set`.

## 1.1.2

* Export `UnmodifiableMapView` from the Dart core libraries.

## 1.1.1

* Bug-fix for signatures of `isValidKey` arguments of `CanonicalizedMap`.

## 1.1.0

* Add a `QueueList` class that implements both `Queue` and `List`.

## 0.9.4

* Add a `CanonicalizedMap` class that canonicalizes its keys to provide a custom
  equality relation.

## 0.9.3+1

* Fix all analyzer hints.

## 0.9.3

* Add a `MapKeySet` class that exposes an unmodifiable `Set` view of a `Map`'s
  keys.

* Add a `MapValueSet` class that takes a function from values to keys and uses
  it to expose a `Set` view of a `Map`'s values.
