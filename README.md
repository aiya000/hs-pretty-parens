```shell-session
$ echo '(foo (bar baz))' | ./pretty-parens
(foo
  (bar baz))

$ echo '(foo (bar [baz {aaa bbb}]))' | ./pretty-parens
(foo
  (bar
    [baz
      {aaa bbb}]))
```
