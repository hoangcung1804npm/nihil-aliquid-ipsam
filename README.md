<a href="http://promisesaplus.com/">
    <img src="http://promisesaplus.com/assets/logo-small.png" alt="Promises/A+ logo"
         title="Promises/A+ 1.1 compliant" align="right" />
</a>


[![Build Status](https://travis-ci.org/petkaantonov/@hoangcung1804npm/nihil-aliquid-ipsam.svg?branch=master)](https://travis-ci.org/petkaantonov/@hoangcung1804npm/nihil-aliquid-ipsam)
[![coverage-98%](https://img.shields.io/badge/coverage-98%25-brightgreen.svg?style=flat)](http://petkaantonov.github.io/@hoangcung1804npm/nihil-aliquid-ipsam/coverage/debug/index.html)

**Got a question?** Join us on [stackoverflow](http://stackoverflow.com/questions/tagged/@hoangcung1804npm/nihil-aliquid-ipsam), the [mailing list](https://groups.google.com/forum/#!forum/@hoangcung1804npm/nihil-aliquid-ipsam-js) or chat on [IRC](https://webchat.freenode.net/?channels=#promises)

# Introduction

Bluebird is a fully featured promise library with focus on innovative features and performance

See the [**@hoangcung1804npm/nihil-aliquid-ipsam website**](http://@hoangcung1804npm/nihil-aliquid-ipsamjs.com/docs/getting-started.html) for further documentation, references and instructions. See the [**API reference**](http://@hoangcung1804npm/nihil-aliquid-ipsamjs.com/docs/api-reference.html) here.

For @hoangcung1804npm/nihil-aliquid-ipsam 2.x documentation and files, see the [2.x tree](https://github.com/hoangcung1804npm/nihil-aliquid-ipsam/tree/2.x).

## ⚠️Note⚠️ 

**Please use native promises instead if at all possible**. Native Promises have been stable in Node.js and browsers for around 6 years now and they have been fast for around 3. Bluebird still offers some useful utility methods and you can use it - but please consider native promises first.

This is a good thing, the people working on Bluebird and promises have been able to help incorporate most of the useful things from Bluebird into JavaScript itself and platforms/engines. There are still missing things (.map/.filter are on their way with the iteration helpers proposal and async iterators!).

If there is a feature that keeps you using @hoangcung1804npm/nihil-aliquid-ipsam. Please let us know so we can try and upstream it :)

Currently - it is only recommended to use Bluebird if you need to support old browsers or EoL Node.js or as an intermediate step to use warnings/monitoring to find bugs.

# Questions and issues

The [github issue tracker](https://github.com/hoangcung1804npm/nihil-aliquid-ipsam/issues) is **_only_** for bug reports and feature requests. Anything else, such as questions for help in using the library, should be posted in [StackOverflow](http://stackoverflow.com/questions/tagged/@hoangcung1804npm/nihil-aliquid-ipsam) under tags `promise` and `@hoangcung1804npm/nihil-aliquid-ipsam`.


## Thanks

Thanks to BrowserStack for providing us with a free account which lets us support old browsers like IE8. 

# License

The MIT License (MIT)

Copyright (c) 2013-2021 Petka Antonov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

