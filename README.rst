========================================
Regular Expression Features Table
========================================

[WIP]


Goal
========================================

Generate a website to show
regular expression features support status in different engines,
and the website can display the usage in different engines.

Furthermore,
add support for benchmarking to compare different engines'
performance and memory usage.



Possible Engines
========================================

* `PCRE (PCRE, PCRE-DFA, PCRE-sljit) <http://www.pcre.org/>`_
* `RE2 <https://github.com/google/re2/>`_
* `sregex <https://github.com/openresty/sregex>`_
* `Boost.Regex <http://www.boost.org/doc/libs/release/libs/regex/>`_
* `TRE <https://github.com/laurikari/tre/>`_
* `Oniguruma <https://github.com/kkos/oniguruma>`_
* `Onigmo <https://github.com/k-takata/Onigmo>`_
* CPython - Secret Labs' Regular Expression Engine
* WebKit - `YARR (Yet Another Regex Runtime) <http://trac.webkit.org/browser/trunk/Source/JavaScriptCore/yarr>`_
* V8 - `irregexp <https://chromium.googlesource.com/external/v8/+/master/src>`_
* `hyperscan <https://github.com/01org/hyperscan>`_
* Thompson's NFA VM
* Pike's NFA VM



Performance Comparison
========================================

* `sljit - Performance comparison of regular expression engines <http://sljit.sourceforge.net/regex_perf.html>`_



Regular Expression Engine Technology
========================================

* DFA
* NFA
* SIMD
* Bit-Parallel Glushkov NFA



Articles
========================================

* `Russ Cox - Implementing Regular Expressions <https://swtch.com/~rsc/regexp/>`_
