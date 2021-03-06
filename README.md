# HOGEMONITOR
- A simple system monitor for Linux written in Python3.

![](screenshot.png)

- The default is battery, memory, CPU, GPU, date and time monitor.
  - Battery and GPU status will not displayed if it is unavailable.

## REQUIREMENTS
- python-xlib (https://pypi.org/project/python-xlib/)
- X window system
- Linux kernel (for CPU and memory status)
- nvidia-smi (for GPU status)

## INSTALLATION
```
$ pip3 install python-xlib
$ git clone https://github.com/void-hoge/hogemonitor.git
$ cp hogemonitor/hogemonitor /a/directory/added/to/the/PATH
```

## OPTION
- `hogemonitor <num>`: Monitor number to display.

## SEE ALSO
- hogewm (https://github.com/void-hoge/hogewm.git )
  - You can toggle hogemonitor with ctrl+alt+v.

## AUTHER
- void-hoge

## LICENSE
- GPLv3