Universal text formatter for the command line. fmt is a working title, but it's already taken. lazyformat? lzyfmt? zormat? lazmat? fm2? 

Basically just does its best to detect what format your text is in. Add new text formats with python scripts.

```bash

$ cat json | fmt
    { 
        "this": "is"
        "neat" : []
    }

$ px aux | grep nobody | fmt

       really cool
       tables line up
       nicely neat

```


