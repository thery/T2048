<!---
This file was generated from `meta.yml`, please do not edit manually.
Follow the instructions on https://github.com/coq-community/templates to regenerate.
--->
# T2048

[![Docker CI][docker-action-shield]][docker-action-link]

[docker-action-shield]: https://github.com/thery/T2048/actions/workflows/docker-action.yml/badge.svg?branch=master
[docker-action-link]: https://github.com/thery/T2048/actions/workflows/docker-action.yml




# T2048
a version of the 2048 game for Rocq

![2048](./2048.png)

## Meta

- Author(s):
  - Laurent Théry
- License: [MIT License](LICENSE)
- Additional dependencies: none
- Rocq/Coq namespace: `T2048`
- Related publication(s): none

## Building and installation instructions

To build and install manually, do:

``` shell
git clone https://github.com/thery/T2048.git
cd T2048
make   # or make -j <number-of-cores-on-your-machine> 
make install
```



