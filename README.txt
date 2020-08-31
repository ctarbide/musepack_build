# -*- mode:org; coding:utf-8-unix -*-

#+STARTUP: indent

* How Build
#+BEGIN_SRC sh
  git clone --recursive https://github.com/ctarbide/musepack_build.git
  cmake -DCMAKE_INSTALL_PREFIX=/opt/musepack .
  make
  sudo make install
#+END_SRC
