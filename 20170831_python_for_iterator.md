in python, you can use "for" command to loope some process.  
you should usually use the case below.

```
greetings = ["hello", "hi", "good morning"]
for greet in greetings :
    print(greet)
```

but when you want to use with iterator, write like below.

```
greetings = ["hello", "hi", "good morning"]
for i, greet in enumerate(greetings) :
    if i % 2 == 0 :
        print(greet)
```
