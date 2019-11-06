addu
====

Description
-----------

This will add a task only if it doesn't already exist.

Usage
-----

```bash
$ todo.sh addu "sell my bitcoins"
30 sell my bitcoins
TODO: 30 added.
$ todo.sh addu "sell my bitcoins"
30 sell my bitcoins
Already exists.
```

Installation
------------

```bash
cd ~/.todo.actions.d && \
    wget https://raw.githubusercontent.com/markcaudill/todo.txt-addu/master/addu && \
    chmod +x addu
```

