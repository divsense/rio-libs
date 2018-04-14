# rio-libs
Divsense Common Rio Libs

* **parser.rio**

  Parser monad

  *Usage*

  ```javascript

  export x
  import 'mart::divsense/rio/src/parser'

  w = some(letter) >>= pure . join('')
  d = some(digit) >>= pure . join('')

  x = w <|> d

  ```

