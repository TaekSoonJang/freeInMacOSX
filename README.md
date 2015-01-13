# Linux style 'free' command on Mac OS X
---
Currently there is no *free* command on Mac OS X.

But sometimes, you have scripts running on Linux and you want to run it on your local Mac machine.

If those scripts have a part that parses some words from *free* command, you are in trouble.

In that situation, you can use it.

-----
# Requirements

* Python 3
* psutil (which is python module)

-----
# How to use
* After downloading this script in your loacl machine, run below line.

```
$ ln -s path/to/free /usr/local/bin/free
```