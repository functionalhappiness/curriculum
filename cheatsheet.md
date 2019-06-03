# Functions

# Conditionals

# Advanced Datatypes
Vector: `[ 1 2 3 4 ]`

Accessing a Vector:
```clj
(let [my-vector [1 2 3 4]]
 (first my-vector) ; will result in 1
)

(let [my-vector [1 2 3 4]]
 (nth 2 my-vector) ; will result in 3
)
```

Map: `{:key 'value' :second-key 2}`

Accessing a Map:
```clj
(let [my-map {:key 'foo'}]
 (:key my-map) ; will result in 'foo'
)
```

Functions for advanced Datatypes
* [assoc](https://clojuredocs.org/clojure.core/assoc)
* [dissoc](https://clojuredocs.org/clojure.core/dissoc)
* [merge](https://clojuredocs.org/clojure.core/merge)
* [conj](https://clojuredocs.org/clojure.core/conj)
* [concat](https://clojuredocs.org/clojure.core/concat)
* [get-in](https://clojuredocs.org/clojure.core/get-in)

# Creating logic
* map
* reduce
