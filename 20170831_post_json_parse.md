when you send with post method, note that the data is treated as string.  
if ever you put the data like this -{"name": "taro", "age": 20} - that is normaly recognized as dict in python, server usually recevie the data as string "{"name": "taro", "age": 20}" .  

you can use "ast", python library that parse string.

https://docs.python.jp/3/library/ast.html
