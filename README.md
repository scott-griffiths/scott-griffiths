## About me

I started programming with Basic on a ZX81 (who needs more than a kilobyte of memory?) before moving to a C64 then Atari ST before learing the 'proper languages' of Fortran and C++ while studying physics. My career has included a lot of video compression and baseband analysis, but lately more AI algorithms, training and performance optimisations.

I'm currently working at [Graphcore](https://www.graphcore.ai) in Bristol. We're making chips for AI. It's a cool place to be.

----

<a href="https://github.com/scott-griffiths/bitstring">
  <img src="https://raw.githubusercontent.com/scott-griffiths/bitstring/main/doc/bitstring_logo_small.png" alt="bitstring Logo" width="250px">
</a>

A long time ago I wanted to do some quick tasks with compressed video streams, and I couldn't find an easy way to do this in Python. So I wrote my own library, which I later made open source and put on PyPI. 
I'm still maintaining and improving the [bitstring](https://github.com/scott-griffiths/bitstring) library. If you need to mess about with bits and bytes in Python then it's a reasonable choice to make things easier.

It's quite widely used, and gets several million downloads each month.

[![PyPI - Version](https://img.shields.io/pypi/v/bitstring?label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/bitstring/)
[![CI badge](https://github.com/scott-griffiths/bitstring/actions/workflows/.github/workflows/ci.yml/badge.svg)](https://github.com/scott-griffiths/bitstring/actions/workflows/ci.yml)
[![Docs](https://img.shields.io/readthedocs/bitstring?logo=readthedocs&logoColor=white)](https://bitstring.readthedocs.io/en/latest/)
[![Codacy Badge](https://img.shields.io/codacy/grade/8869499b2eed44548fa1a5149dd451f4?logo=codacy)](https://app.codacy.com/gh/scott-griffiths/bitstring/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Dependents (via libraries.io)](https://img.shields.io/librariesio/dependents/pypi/bitstring?logo=libraries.io&logoColor=white)](https://libraries.io/pypi/bitstring)
&nbsp; &nbsp;
[![Pepy Total Downlods](https://img.shields.io/pepy/dt/bitstring?logo=python&logoColor=white&labelColor=blue&color=blue)](https://www.pepy.tech/projects/bitstring)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/bitstring?label=%40&labelColor=blue&color=blue)](https://pypistats.org/packages/bitstring)

----

<a href="https://github.com/scott-griffiths/bitformat">
  <img src="https://raw.githubusercontent.com/scott-griffiths/bitformat/main/doc/bitformat_logo.png" alt="bitformat Logo" width="250px">
</a>


My new project is a bitwise format parsing and building library called [bitformat](https://github.com/scott-griffiths/bitformat). It is already pretty solid in terms of bitwise creation and interpretation, covering much of the same ground as bitstring but with a new and more efficient API. Future work will expand the format specification and parsing features. The core of it is written in Rust and it's already (mostly) quite fast.

It is currently in beta with plenty more planned for 2026. Please try it out and let me know what you think. 


[![PyPI - Version](https://img.shields.io/pypi/v/bitformat?label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/bitformat/)
[![CI badge](https://github.com/scott-griffiths/bitformat/actions/workflows/.github/workflows/test.yml/badge.svg)](https://github.com/scott-griffiths/bitformat/actions/workflows/test.yml)
[![Docs](https://img.shields.io/readthedocs/bitformat?logo=readthedocs&logoColor=white)](https://bitformat.readthedocs.io/en/latest/)
[![Codacy Badge](https://img.shields.io/codacy/grade/b61ae16cc6404d0da5dbcc21ee19ddda?logo=codacy)](https://app.codacy.com/gh/scott-griffiths/bitformat/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![Dependents (via libraries.io)](https://img.shields.io/librariesio/dependents/pypi/bitformat?logo=libraries.io&logoColor=white)](https://libraries.io/pypi/bitformat)
&nbsp; &nbsp;
[![Pepy Total Downlods](https://img.shields.io/pepy/dt/bitformat?logo=python&logoColor=white&labelColor=blue&color=blue)](https://www.pepy.tech/projects/bitformat)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/bitformat?label=%40&labelColor=blue&color=blue)](https://pypistats.org/packages/bitformat)

----

<a href="https://github.com/scott-griffiths/tibs">
  <img src="https://raw.githubusercontent.com/scott-griffiths/tibs/main/doc/tibs.png" alt="tibs Logo" width="150px">
</a>

My even-newer project takes the core that I've been working on for bitformat and makes it into a stand-alone library, written entirely in Rust. 
The idea is that this core is very useful by itself and can be used for projects that don't need all the more advanced pieces of bitstring and bitformat.
I plan to use tibs as a dependency for both bitformat and bitstring.

The performance is now quite reasonable, with the simple API and documentation mostly complete.

[![PyPI - Version](https://img.shields.io/pypi/v/tibs?label=PyPI&logo=pypi&logoColor=white)](https://pypi.org/project/tibs/)
[![CI badge](https://github.com/scott-griffiths/tibs/actions/workflows/.github/workflows/test.yml/badge.svg)](https://github.com/scott-griffiths/tibs/actions/workflows/test.yml)
[![Docs](https://img.shields.io/readthedocs/mutibs?logo=readthedocs&logoColor=white)](https://mutibs.readthedocs.io/en/latest/)
![PyPI - License](https://img.shields.io/pypi/l/tibs)
&nbsp; &nbsp;
[![Pepy Total Downlods](https://img.shields.io/pepy/dt/tibs?logo=python&logoColor=white&labelColor=blue&color=blue)](https://www.pepy.tech/projects/tibs)

----

## The Go Clock

I've not got much else public on GitHub except my quixotic idea of [a clock based on a Go board](http://scott-griffiths.github.io/go-clock/).
It's quite possibly the best go-board based clock ever constructed on the web.

[![The Go Clock](https://github.com/scott-griffiths/go-clock/blob/d6e971af31662fb1da5acbeaf193b16f514b07c1/resources/Go_clock_small.jpeg)](http://scott-griffiths.github.io/go-clock/)

