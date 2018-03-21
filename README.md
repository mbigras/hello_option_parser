# Hello OptionParser

>Hacking on Ruby's OptionParser

## Usage example

Type coercion!

```
./somecli -s -f cats -t 2:30 -n 42 foo bar baz
{:switch=>true, :flag=>"cats", :time=>2018-03-21 02:30:00 -0700, :ndays=>42}
["foo", "bar", "baz"]
```