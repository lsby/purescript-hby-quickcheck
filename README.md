#

## 使用

```
in  upstream
  with hby-quickcheck =
      { dependencies =
          [ "arrays"
          , "assert"
          , "console"
          , "control"
          , "effect"
          , "either"
          , "enums"
          , "exceptions"
          , "foldable-traversable"
          , "gen"
          , "identity"
          , "integers"
          , "lazy"
          , "lcg"
          , "lists"
          , "math"
          , "maybe"
          , "newtype"
          , "nonempty"
          , "numbers"
          , "partial"
          , "prelude"
          , "psci-support"
          , "record"
          , "st"
          , "strings"
          , "tailrec"
          , "transformers"
          , "tuples"
          ]
      , repo =
          "https://github.com/lsby/purescript-hby-quickcheck"
      , version =
          "ls_v1.0.0"
      }
```

```
spago install hby-quickcheck
```
