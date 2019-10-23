# travis_qmake_gcc_cpp17_deploy

Branch   |[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---------|---------------------------------------------------------
`master` |[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_deploy.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_deploy)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_deploy.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_deploy)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++17`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`
 * Deploy: create the executables for multiple OSes and chip architecture

Less complex builds:

 * Use C++17, without a deploy step: [travis_qmake_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17)
