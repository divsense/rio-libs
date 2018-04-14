# rio-libs
Divsense Common Rio Libs

* **parser.rio**

  Parser monad

  *Usage*

  ```javascript

  export x
  import 'https://mart.divsense.com/divsense/rio/parser'

  w = some(letter) >>= pure . join('')
  d = some(digit) >>= pure . join('')

  x = w <|> d

  ```

