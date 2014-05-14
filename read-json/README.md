# read-json

A Clojure library designed to ... well, that part is up to you.

## Usage

user> (require '[clojure.data.json :as json])
user> (use 'incanter.core)
user> (to-dataset (json/read-json (slurp "resources/small-sample.json")))


FIXME

## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
