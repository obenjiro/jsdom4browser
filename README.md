jsdom4browser
=============

A javascript implementation of the DOM, for use with WebWorkers and browsers

# Warning

**Use this in production on your own risk! This examples work quite stable but still - it's a beta!**

This is a modifed fork of https://github.com/tmpvar/jsdom ( all credits goes to author of jsdom! ) created to show that there is a use cases for custom DOM implementation in the browser. 

My role is to create usable examples and to show that it's possible.

(TODO: Add more examples, right now there is only D3 + WebWorker example)

# Known Problems

Since i done this in one night there is some problems that i didn't solve yet.

1) No canvas 
2) No Contextify ( we don't actually need it for webworkers )
3) Problmes with loading js with jsdom.
4) If you work in WebWorker - everythign is fine. In browsers - we have some additional weird problems.


# License

The MIT License (MIT)

Copyright (c) 2013 Ai_boy

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
