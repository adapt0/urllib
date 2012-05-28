# urllib

[![Build Status](https://secure.travis-ci.org/TBEDP/urllib.png?branch=master)](http://travis-ci.org/TBEDP/urllib)

Help in opening URLs (mostly HTTP) in a complex world — basic and digest authentication, redirections, cookies and more. Like python  _urllib_ module.

## Install

```bash
$ npm install urllib
```

## Usage

### urllib.request()

```
var urllib = require('urllib');

urllib.request('http://cnodejs.org/', { wd: 'nodejs' }, function (err, data, res) {
  console.log(res.statusCode);
  console.log(res.headers);
  console.log(data.toString());
});
```

## TODO

* Upload file.
* Auto redirect handle.
* Bash auth support.

# Authors

Below is the output from `git-summary`.

```
 project: urllib
 commits: 17
 files  : 9
 authors: 
    13	fengmk2                 76.5%
     3	Jackson Tian            17.6%
     1	aleafs                  5.9%
```

## License 

(The MIT License)

Copyright (c) 2011-2012 fengmk2 &lt;fengmk2@gmail.com&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
