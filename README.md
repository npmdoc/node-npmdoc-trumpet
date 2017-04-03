# api documentation for  [trumpet (v1.7.2)](https://github.com/substack/node-trumpet#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-trumpet.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-trumpet) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-trumpet.svg)](https://travis-ci.org/npmdoc/node-npmdoc-trumpet)
#### parse and transform streaming html using css selectors

[![NPM](https://nodei.co/npm/trumpet.png?downloads=true)](https://www.npmjs.com/package/trumpet)

[![apidoc](https://npmdoc.github.io/node-npmdoc-trumpet/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-trumpet_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-trumpet/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-trumpet/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-trumpet/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "email": "mail@substack.net",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/node-trumpet/issues"
    },
    "dependencies": {
        "duplexer2": "~0.0.2",
        "html-select": "^2.3.5",
        "html-tokenize": "^1.1.1",
        "inherits": "^2.0.0",
        "readable-stream": "^1.0.27-1",
        "through2": "^1.0.0"
    },
    "description": "parse and transform streaming html using css selectors",
    "devDependencies": {
        "concat-stream": "~1.4.5",
        "tape": "~2.12.3",
        "through": "~2.3.4"
    },
    "directories": {},
    "dist": {
        "shasum": "b02c69e465d171f55e44924bf9b5bdd20974c830",
        "tarball": "https://registry.npmjs.org/trumpet/-/trumpet-1.7.2.tgz"
    },
    "engine": {
        "node": ">=0.4"
    },
    "gitHead": "bacb8c0254f3e26a3401ff8411c3d01b427cbcde",
    "homepage": "https://github.com/substack/node-trumpet#readme",
    "keywords": [
        "html",
        "streaming",
        "parser",
        "transform",
        "selectors",
        "css"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack",
            "email": "mail@substack.net"
        }
    ],
    "name": "trumpet",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/substack/node-trumpet.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "1.7.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module trumpet](#apidoc.module.trumpet)
1.  [function <span class="apidocSignatureSpan">trumpet.</span>super_ (options)](#apidoc.element.trumpet.super_)
1.  [function <span class="apidocSignatureSpan">trumpet.</span>super_.super_ (options)](#apidoc.element.trumpet.super_.super_)
1.  object <span class="apidocSignatureSpan">trumpet.</span>super_.prototype
1.  object <span class="apidocSignatureSpan">trumpet.</span>super_.super_.PassThrough.prototype
1.  object <span class="apidocSignatureSpan">trumpet.</span>super_.super_.Transform.prototype
1.  object <span class="apidocSignatureSpan">trumpet.</span>super_.super_.Writable.prototype
1.  object <span class="apidocSignatureSpan">trumpet.</span>super_.super_.prototype

#### [module trumpet.super_](#apidoc.module.trumpet.super_)
1.  [function <span class="apidocSignatureSpan">trumpet.</span>super_ (options)](#apidoc.element.trumpet.super_.super_)

#### [module trumpet.super_.prototype](#apidoc.module.trumpet.super_.prototype)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype._write)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>cork ()](#apidoc.element.trumpet.super_.prototype.cork)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype.end)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>uncork ()](#apidoc.element.trumpet.super_.prototype.uncork)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype.write)
1.  object <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>_writev

#### [module trumpet.super_.super_](#apidoc.module.trumpet.super_.super_)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.</span>super_ ()](#apidoc.element.trumpet.super_.super_.super_)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Duplex (options)](#apidoc.element.trumpet.super_.super_.Duplex)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>PassThrough (options)](#apidoc.element.trumpet.super_.super_.PassThrough)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Readable (options)](#apidoc.element.trumpet.super_.super_.Readable)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>ReadableState (options, stream)](#apidoc.element.trumpet.super_.super_.ReadableState)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Stream ()](#apidoc.element.trumpet.super_.super_.Stream)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Transform (options)](#apidoc.element.trumpet.super_.super_.Transform)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Writable (options)](#apidoc.element.trumpet.super_.super_.Writable)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>_fromList (n, state)](#apidoc.element.trumpet.super_.super_._fromList)

#### [module trumpet.super_.super_.PassThrough.prototype](#apidoc.module.trumpet.super_.super_.PassThrough.prototype)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.PassThrough.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.PassThrough.prototype._transform)

#### [module trumpet.super_.super_.Transform.prototype](#apidoc.module.trumpet.super_.super_.Transform.prototype)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_read (n)](#apidoc.element.trumpet.super_.super_.Transform.prototype._read)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Transform.prototype._transform)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Transform.prototype._write)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>push (chunk, encoding)](#apidoc.element.trumpet.super_.super_.Transform.prototype.push)

#### [module trumpet.super_.super_.Writable.prototype](#apidoc.module.trumpet.super_.super_.Writable.prototype)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype._write)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>cork ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.cork)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype.end)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>pipe ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>uncork ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.uncork)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype.write)
1.  object <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>_writev

#### [module trumpet.super_.super_.prototype](#apidoc.module.trumpet.super_.super_.prototype)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>_read (n)](#apidoc.element.trumpet.super_.super_.prototype._read)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.trumpet.super_.super_.prototype.addListener)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.trumpet.super_.super_.prototype.on)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>pause ()](#apidoc.element.trumpet.super_.super_.prototype.pause)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.trumpet.super_.super_.prototype.pipe)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.trumpet.super_.super_.prototype.push)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>read (n)](#apidoc.element.trumpet.super_.super_.prototype.read)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>resume ()](#apidoc.element.trumpet.super_.super_.prototype.resume)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.trumpet.super_.super_.prototype.setEncoding)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.trumpet.super_.super_.prototype.unpipe)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.trumpet.super_.super_.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.trumpet.super_.super_.prototype.wrap)



# <a name="apidoc.module.trumpet"></a>[module trumpet](#apidoc.module.trumpet)

#### <a name="apidoc.element.trumpet.super_"></a>[function <span class="apidocSignatureSpan">trumpet.</span>super_ (options)](#apidoc.element.trumpet.super_)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex))
    return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false)
    this.readable = false;

  if (options && options.writable === false)
    this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false)
    this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_"></a>[function <span class="apidocSignatureSpan">trumpet.</span>super_.super_ (options)](#apidoc.element.trumpet.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  var Duplex = require('./_stream_duplex');

  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.trumpet.super_"></a>[module trumpet.super_](#apidoc.module.trumpet.super_)

#### <a name="apidoc.element.trumpet.super_.super_"></a>[function <span class="apidocSignatureSpan">trumpet.</span>super_ (options)](#apidoc.element.trumpet.super_.super_)
- description and source-code
```javascript
function Readable(options) {
  var Duplex = require('./_stream_duplex');

  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.trumpet.super_.prototype"></a>[module trumpet.super_.prototype](#apidoc.module.trumpet.super_.prototype)

#### <a name="apidoc.element.trumpet.super_.prototype._write"></a>[function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('not implemented'));

}
```
- example usage
```shell
...
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
return this._tokenize._write(buf, enc, next);
};

Trumpet.prototype.select = function (str, cb) {
var self = this;
var first = true;

var res = self._selectAll(str, function (elem) {
...
```

#### <a name="apidoc.element.trumpet.super_.prototype.cork"></a>[function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>cork ()](#apidoc.element.trumpet.super_.prototype.cork)
- description and source-code
```javascript
cork = function () {
  var state = this._writableState;

  state.corked++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.prototype.end"></a>[function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (util.isFunction(chunk)) {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (util.isFunction(encoding)) {
    cb = encoding;
    encoding = null;
  }

  if (!util.isNullOrUndefined(chunk))
    this.write(chunk, encoding);

  // .end() fully uncorks
  if (state.corked) {
    state.corked = 1;
    this.uncork();
  }

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished)
    endWritable(this, state, cb);
}
```
- example usage
```shell
...
    this._writing = false;
    this._piping = false;
    this._select = this._tokenize.pipe(select());
    this._select.once('end', function () {
        self.emit('_end');
        self.push(null)
    });
    this.once('finish', function () { self._tokenize.end() });
}

Trumpet.prototype.pipe = function () {
    this._piping = true;
    return Duplex.prototype.pipe.apply(this, arguments);
};
...
```

#### <a name="apidoc.element.trumpet.super_.prototype.uncork"></a>[function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>uncork ()](#apidoc.element.trumpet.super_.prototype.uncork)
- description and source-code
```javascript
uncork = function () {
  var state = this._writableState;

  if (state.corked) {
    state.corked--;

    if (!state.writing &&
        !state.corked &&
        !state.finished &&
        !state.bufferProcessing &&
        state.buffer.length)
      clearBuffer(this, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.prototype.write"></a>[function <span class="apidocSignatureSpan">trumpet.super_.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;

  if (util.isFunction(encoding)) {
    cb = encoding;
    encoding = null;
  }

  if (util.isBuffer(chunk))
    encoding = 'buffer';
  else if (!encoding)
    encoding = state.defaultEncoding;

  if (!util.isFunction(cb))
    cb = function() {};

  if (state.ended)
    writeAfterEnd(this, state, cb);
  else if (validChunk(this, state, chunk, cb)) {
    state.pendingcb++;
    ret = writeOrBuffer(this, state, chunk, encoding, cb);
  }

  return ret;
}
```
- example usage
```shell
...

welem.createWriteStream = function (opts) {
    if (!opts) opts = {};

    var ws = elem.createWriteStream({ inner: !opts.outer });
    var w = new Writable;
    w._write = function (buf, enc, next) {
        ws.write([ 'data', buf ]);
        next();
    };
    w.on('finish', function () { ws.end() });

    return w;
};
...
```



# <a name="apidoc.module.trumpet.super_.super_"></a>[module trumpet.super_.super_](#apidoc.module.trumpet.super_.super_)

#### <a name="apidoc.element.trumpet.super_.super_.super_"></a>[function <span class="apidocSignatureSpan">trumpet.super_.</span>super_ ()](#apidoc.element.trumpet.super_.super_.super_)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Duplex"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Duplex (options)](#apidoc.element.trumpet.super_.super_.Duplex)
- description and source-code
```javascript
function Duplex(options) {
  if (!(this instanceof Duplex))
    return new Duplex(options);

  Readable.call(this, options);
  Writable.call(this, options);

  if (options && options.readable === false)
    this.readable = false;

  if (options && options.writable === false)
    this.writable = false;

  this.allowHalfOpen = true;
  if (options && options.allowHalfOpen === false)
    this.allowHalfOpen = false;

  this.once('end', onend);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.PassThrough"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>PassThrough (options)](#apidoc.element.trumpet.super_.super_.PassThrough)
- description and source-code
```javascript
function PassThrough(options) {
  if (!(this instanceof PassThrough))
    return new PassThrough(options);

  Transform.call(this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Readable"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Readable (options)](#apidoc.element.trumpet.super_.super_.Readable)
- description and source-code
```javascript
function Readable(options) {
  var Duplex = require('./_stream_duplex');

  if (!(this instanceof Readable))
    return new Readable(options);

  this._readableState = new ReadableState(options, this);

  // legacy
  this.readable = true;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.ReadableState"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>ReadableState (options, stream)](#apidoc.element.trumpet.super_.super_.ReadableState)
- description and source-code
```javascript
function ReadableState(options, stream) {
  var Duplex = require('./_stream_duplex');

  options = options || {};

  // the point at which it stops calling _read() to fill the buffer
  // Note: 0 is a valid value, means "don't call _read preemptively ever"
  var hwm = options.highWaterMark;
  var defaultHwm = options.objectMode ? 16 : 16 * 1024;
  this.highWaterMark = (hwm || hwm === 0) ? hwm : defaultHwm;

  // cast to ints.
  this.highWaterMark = ~~this.highWaterMark;

  this.buffer = [];
  this.length = 0;
  this.pipes = null;
  this.pipesCount = 0;
  this.flowing = null;
  this.ended = false;
  this.endEmitted = false;
  this.reading = false;

  // a flag to be able to tell if the onwrite cb is called immediately,
  // or on a later tick.  We set this to true at first, because any
  // actions that shouldn't happen until "later" should generally also
  // not happen before the first write call.
  this.sync = true;

  // whenever we return null, then we set a flag to say
  // that we're awaiting a 'readable' event emission.
  this.needReadable = false;
  this.emittedReadable = false;
  this.readableListening = false;


  // object stream flag. Used to make read(n) ignore n and to
  // make all the buffer merging and length checks go away
  this.objectMode = !!options.objectMode;

  if (stream instanceof Duplex)
    this.objectMode = this.objectMode || !!options.readableObjectMode;

  // Crypto is kind of old and crusty.  Historically, its default string
  // encoding is 'binary' so we have to make this configurable.
  // Everything else in the universe uses 'utf8', though.
  this.defaultEncoding = options.defaultEncoding || 'utf8';

  // when piping, we only care about 'readable' events that happen
  // after read()ing all the bytes and not getting any pushback.
  this.ranOut = false;

  // the number of writers that are awaiting a drain event in .pipe()s
  this.awaitDrain = 0;

  // if true, a maybeReadMore has been scheduled
  this.readingMore = false;

  this.decoder = null;
  this.encoding = null;
  if (options.encoding) {
    if (!StringDecoder)
      StringDecoder = require('string_decoder/').StringDecoder;
    this.decoder = new StringDecoder(options.encoding);
    this.encoding = options.encoding;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Stream"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Stream ()](#apidoc.element.trumpet.super_.super_.Stream)
- description and source-code
```javascript
function Stream() {
  EE.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Transform"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Transform (options)](#apidoc.element.trumpet.super_.super_.Transform)
- description and source-code
```javascript
function Transform(options) {
  if (!(this instanceof Transform))
    return new Transform(options);

  Duplex.call(this, options);

  this._transformState = new TransformState(options, this);

  // when the writable side finishes, then flush out anything remaining.
  var stream = this;

  // start out asking for a readable event once data is transformed.
  this._readableState.needReadable = true;

  // we have implemented the _read method, and done the other things
  // that Readable wants before the first _read call, so unset the
  // sync guard flag.
  this._readableState.sync = false;

  this.once('prefinish', function() {
    if (util.isFunction(this._flush))
      this._flush(function(er) {
        done(stream, er);
      });
    else
      done(stream);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>Writable (options)](#apidoc.element.trumpet.super_.super_.Writable)
- description and source-code
```javascript
function Writable(options) {
  var Duplex = require('./_stream_duplex');

  // Writable ctor is applied to Duplexes, though they're not
  // instanceof Writable, they're instanceof Readable.
  if (!(this instanceof Writable) && !(this instanceof Duplex))
    return new Writable(options);

  this._writableState = new WritableState(options, this);

  // legacy.
  this.writable = true;

  Stream.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_._fromList"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.</span>_fromList (n, state)](#apidoc.element.trumpet.super_.super_._fromList)
- description and source-code
```javascript
function fromList(n, state) {
  var list = state.buffer;
  var length = state.length;
  var stringMode = !!state.decoder;
  var objectMode = !!state.objectMode;
  var ret;

  // nothing in the list, definitely empty.
  if (list.length === 0)
    return null;

  if (length === 0)
    ret = null;
  else if (objectMode)
    ret = list.shift();
  else if (!n || n >= length) {
    // read it all, truncate the array.
    if (stringMode)
      ret = list.join('');
    else
      ret = Buffer.concat(list, length);
    list.length = 0;
  } else {
    // read just some of it.
    if (n < list[0].length) {
      // just take a part of the first list item.
      // slice is the same for buffers and strings.
      var buf = list[0];
      ret = buf.slice(0, n);
      list[0] = buf.slice(n);
    } else if (n === list[0].length) {
      // first list is a perfect match
      ret = list.shift();
    } else {
      // complex case.
      // we have enough to cover it, but it spans past the first buffer.
      if (stringMode)
        ret = '';
      else
        ret = new Buffer(n);

      var c = 0;
      for (var i = 0, l = list.length; i < l && c < n; i++) {
        var buf = list[0];
        var cpy = Math.min(n - c, buf.length);

        if (stringMode)
          ret += buf.slice(0, cpy);
        else
          buf.copy(ret, c, 0, cpy);

        if (cpy < buf.length)
          list[0] = buf.slice(cpy);
        else
          list.shift();

        c += cpy;
      }
    }
  }

  return ret;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.trumpet.super_.super_.PassThrough.prototype"></a>[module trumpet.super_.super_.PassThrough.prototype](#apidoc.module.trumpet.super_.super_.PassThrough.prototype)

#### <a name="apidoc.element.trumpet.super_.super_.PassThrough.prototype._transform"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.PassThrough.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.PassThrough.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  cb(null, chunk);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.trumpet.super_.super_.Transform.prototype"></a>[module trumpet.super_.super_.Transform.prototype](#apidoc.module.trumpet.super_.super_.Transform.prototype)

#### <a name="apidoc.element.trumpet.super_.super_.Transform.prototype._read"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_read (n)](#apidoc.element.trumpet.super_.super_.Transform.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  var ts = this._transformState;

  if (!util.isNull(ts.writechunk) && ts.writecb && !ts.transforming) {
    ts.transforming = true;
    this._transform(ts.writechunk, ts.writeencoding, ts.afterTransform);
  } else {
    // mark that we need a transform, so that any data that comes in
    // will get processed, now that we've asked for it.
    ts.needTransform = true;
  }
}
```
- example usage
```shell
...
        read ++
    }
    else if (row[1] && row[1].length) {
        this.push(row[1]);
        read ++;
    }
}
if (read === 0) s.once('readable', function () { self._read(n) });
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
...
```

#### <a name="apidoc.element.trumpet.super_.super_.Transform.prototype._transform"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_transform (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Transform.prototype._transform)
- description and source-code
```javascript
_transform = function (chunk, encoding, cb) {
  throw new Error('not implemented');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Transform.prototype._write"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Transform.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  var ts = this._transformState;
  ts.writecb = cb;
  ts.writechunk = chunk;
  ts.writeencoding = encoding;
  if (!ts.transforming) {
    var rs = this._readableState;
    if (ts.needTransform ||
        rs.needReadable ||
        rs.length < rs.highWaterMark)
      this._read(rs.highWaterMark);
  }
}
```
- example usage
```shell
...
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
return this._tokenize._write(buf, enc, next);
};

Trumpet.prototype.select = function (str, cb) {
var self = this;
var first = true;

var res = self._selectAll(str, function (elem) {
...
```

#### <a name="apidoc.element.trumpet.super_.super_.Transform.prototype.push"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Transform.prototype.</span>push (chunk, encoding)](#apidoc.element.trumpet.super_.super_.Transform.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  this._transformState.needTransform = false;
  return Duplex.prototype.push.call(this, chunk, encoding);
}
```
- example usage
```shell
...
Duplex.call(this);
this._tokenize = tokenize();
this._writing = false;
this._piping = false;
this._select = this._tokenize.pipe(select());
this._select.once('end', function () {
    self.emit('_end');
    self.push(null)
});
this.once('finish', function () { self._tokenize.end() });
}

Trumpet.prototype.pipe = function () {
this._piping = true;
return Duplex.prototype.pipe.apply(this, arguments);
...
```



# <a name="apidoc.module.trumpet.super_.super_.Writable.prototype"></a>[module trumpet.super_.super_.Writable.prototype](#apidoc.module.trumpet.super_.super_.Writable.prototype)

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype._write"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>_write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype._write)
- description and source-code
```javascript
_write = function (chunk, encoding, cb) {
  cb(new Error('not implemented'));

}
```
- example usage
```shell
...
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
return this._tokenize._write(buf, enc, next);
};

Trumpet.prototype.select = function (str, cb) {
var self = this;
var first = true;

var res = self._selectAll(str, function (elem) {
...
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype.cork"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>cork ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.cork)
- description and source-code
```javascript
cork = function () {
  var state = this._writableState;

  state.corked++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype.end"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>end (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype.end)
- description and source-code
```javascript
end = function (chunk, encoding, cb) {
  var state = this._writableState;

  if (util.isFunction(chunk)) {
    cb = chunk;
    chunk = null;
    encoding = null;
  } else if (util.isFunction(encoding)) {
    cb = encoding;
    encoding = null;
  }

  if (!util.isNullOrUndefined(chunk))
    this.write(chunk, encoding);

  // .end() fully uncorks
  if (state.corked) {
    state.corked = 1;
    this.uncork();
  }

  // ignore unnecessary end() calls.
  if (!state.ending && !state.finished)
    endWritable(this, state, cb);
}
```
- example usage
```shell
...
    this._writing = false;
    this._piping = false;
    this._select = this._tokenize.pipe(select());
    this._select.once('end', function () {
        self.emit('_end');
        self.push(null)
    });
    this.once('finish', function () { self._tokenize.end() });
}

Trumpet.prototype.pipe = function () {
    this._piping = true;
    return Duplex.prototype.pipe.apply(this, arguments);
};
...
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype.pipe"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>pipe ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.pipe)
- description and source-code
```javascript
pipe = function () {
  this.emit('error', new Error('Cannot pipe. Not readable.'));
}
```
- example usage
```shell
...
function Trumpet () {
    var self = this;
    if (!(this instanceof Trumpet)) return new Trumpet;
    Duplex.call(this);
    this._tokenize = tokenize();
    this._writing = false;
    this._piping = false;
    this._select = this._tokenize.pipe(select());
    this._select.once('end', function () {
        self.emit('_end');
        self.push(null)
    });
    this.once('finish', function () { self._tokenize.end() });
}
...
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype.uncork"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>uncork ()](#apidoc.element.trumpet.super_.super_.Writable.prototype.uncork)
- description and source-code
```javascript
uncork = function () {
  var state = this._writableState;

  if (state.corked) {
    state.corked--;

    if (!state.writing &&
        !state.corked &&
        !state.finished &&
        !state.bufferProcessing &&
        state.buffer.length)
      clearBuffer(this, state);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.Writable.prototype.write"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.Writable.prototype.</span>write (chunk, encoding, cb)](#apidoc.element.trumpet.super_.super_.Writable.prototype.write)
- description and source-code
```javascript
write = function (chunk, encoding, cb) {
  var state = this._writableState;
  var ret = false;

  if (util.isFunction(encoding)) {
    cb = encoding;
    encoding = null;
  }

  if (util.isBuffer(chunk))
    encoding = 'buffer';
  else if (!encoding)
    encoding = state.defaultEncoding;

  if (!util.isFunction(cb))
    cb = function() {};

  if (state.ended)
    writeAfterEnd(this, state, cb);
  else if (validChunk(this, state, chunk, cb)) {
    state.pendingcb++;
    ret = writeOrBuffer(this, state, chunk, encoding, cb);
  }

  return ret;
}
```
- example usage
```shell
...

welem.createWriteStream = function (opts) {
    if (!opts) opts = {};

    var ws = elem.createWriteStream({ inner: !opts.outer });
    var w = new Writable;
    w._write = function (buf, enc, next) {
        ws.write([ 'data', buf ]);
        next();
    };
    w.on('finish', function () { ws.end() });

    return w;
};
...
```



# <a name="apidoc.module.trumpet.super_.super_.prototype"></a>[module trumpet.super_.super_.prototype](#apidoc.module.trumpet.super_.super_.prototype)

#### <a name="apidoc.element.trumpet.super_.super_.prototype._read"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>_read (n)](#apidoc.element.trumpet.super_.super_.prototype._read)
- description and source-code
```javascript
_read = function (n) {
  this.emit('error', new Error('not implemented'));
}
```
- example usage
```shell
...
        read ++
    }
    else if (row[1] && row[1].length) {
        this.push(row[1]);
        read ++;
    }
}
if (read === 0) s.once('readable', function () { self._read(n) });
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.addListener"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>addListener (ev, fn)](#apidoc.element.trumpet.super_.super_.prototype.addListener)
- description and source-code
```javascript
addListener = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  // If listening to data, and it has not explicitly been paused,
  // then call resume to start the flow of data on the next tick.
  if (ev === 'data' && false !== this._readableState.flowing) {
    this.resume();
  }

  if (ev === 'readable' && this.readable) {
    var state = this._readableState;
    if (!state.readableListening) {
      state.readableListening = true;
      state.emittedReadable = false;
      state.needReadable = true;
      if (!state.reading) {
        var self = this;
        process.nextTick(function() {
          debug('readable nexttick read 0');
          self.read(0);
        });
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.on"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>on (ev, fn)](#apidoc.element.trumpet.super_.super_.prototype.on)
- description and source-code
```javascript
on = function (ev, fn) {
  var res = Stream.prototype.on.call(this, ev, fn);

  // If listening to data, and it has not explicitly been paused,
  // then call resume to start the flow of data on the next tick.
  if (ev === 'data' && false !== this._readableState.flowing) {
    this.resume();
  }

  if (ev === 'readable' && this.readable) {
    var state = this._readableState;
    if (!state.readableListening) {
      state.readableListening = true;
      state.emittedReadable = false;
      state.needReadable = true;
      if (!state.reading) {
        var self = this;
        process.nextTick(function() {
          debug('readable nexttick read 0');
          self.read(0);
        });
      } else if (state.length) {
        emitReadable(this, state);
      }
    }
  }

  return res;
}
```
- example usage
```shell
...
            if (row[1].length) {
                r.push(row[1]);
                reads ++;
            }
        }
        if (reads === 0) rs.once('readable', read);
    };
    rs.on('end', function () { r.push(null) });

    return r;
};

welem.createWriteStream = function (opts) {
    if (!opts) opts = {};
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.pause"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>pause ()](#apidoc.element.trumpet.super_.super_.prototype.pause)
- description and source-code
```javascript
pause = function () {
  debug('call pause flowing=%j', this._readableState.flowing);
  if (false !== this._readableState.flowing) {
    debug('pause');
    this._readableState.flowing = false;
    this.emit('pause');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.pipe"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>pipe (dest, pipeOpts)](#apidoc.element.trumpet.super_.super_.prototype.pipe)
- description and source-code
```javascript
pipe = function (dest, pipeOpts) {
  var src = this;
  var state = this._readableState;

  switch (state.pipesCount) {
    case 0:
      state.pipes = dest;
      break;
    case 1:
      state.pipes = [state.pipes, dest];
      break;
    default:
      state.pipes.push(dest);
      break;
  }
  state.pipesCount += 1;
  debug('pipe count=%d opts=%j', state.pipesCount, pipeOpts);

  var doEnd = (!pipeOpts || pipeOpts.end !== false) &&
              dest !== process.stdout &&
              dest !== process.stderr;

  var endFn = doEnd ? onend : cleanup;
  if (state.endEmitted)
    process.nextTick(endFn);
  else
    src.once('end', endFn);

  dest.on('unpipe', onunpipe);
  function onunpipe(readable) {
    debug('onunpipe');
    if (readable === src) {
      cleanup();
    }
  }

  function onend() {
    debug('onend');
    dest.end();
  }

  // when the dest drains, it reduces the awaitDrain counter
  // on the source.  This would be more elegant with a .once()
  // handler in flow(), but adding and removing repeatedly is
  // too slow.
  var ondrain = pipeOnDrain(src);
  dest.on('drain', ondrain);

  function cleanup() {
    debug('cleanup');
    // cleanup event handlers once the pipe is broken
    dest.removeListener('close', onclose);
    dest.removeListener('finish', onfinish);
    dest.removeListener('drain', ondrain);
    dest.removeListener('error', onerror);
    dest.removeListener('unpipe', onunpipe);
    src.removeListener('end', onend);
    src.removeListener('end', cleanup);
    src.removeListener('data', ondata);

    // if the reader is waiting for a drain event from this
    // specific writer, then it would cause it to never start
    // flowing again.
    // So, if this is awaiting a drain, then we just call it now.
    // If we don't know, then assume that we are waiting for one.
    if (state.awaitDrain &&
        (!dest._writableState || dest._writableState.needDrain))
      ondrain();
  }

  src.on('data', ondata);
  function ondata(chunk) {
    debug('ondata');
    var ret = dest.write(chunk);
    if (false === ret) {
      debug('false write response, pause',
            src._readableState.awaitDrain);
      src._readableState.awaitDrain++;
      src.pause();
    }
  }

  // if the dest has an error, then stop piping into it.
  // however, don't suppress the throwing behavior for this.
  function onerror(er) {
    debug('onerror', er);
    unpipe();
    dest.removeListener('error', onerror);
    if (EE.listenerCount(dest, 'error') === 0)
      dest.emit('error', er);
  }
  // This is a brutally ugly hack to make sure that our error handler
  // is attached before any userland ones.  NEVER DO THIS.
  if (!dest._events || !dest._events.error)
    dest.on('error', onerror);
  else if (isArray(dest._events.error))
    dest._events.error.unshift(onerror);
  else
    dest._events.error = [onerror, dest._events.error];



  // Both close and finish should trigger unpipe, but only once.
  function onclose() {
    dest.removeListener('finish', onfinish);
    unpipe();
  }
  dest.once('close', onclose);
  function onfinish() {
    debug('onfinish');
    dest.removeListener('close', onclose);
    unpipe();
  }
  dest.once('finish', onfinish);

  function unpipe() {
    debug('unpipe');
    src.unpipe(dest);
  }

  // tell the dest that it's being piped to
  dest.emit('pipe', src);

  // start the flow if it hasn't been started already.
  if (!state.flowing) {
    debug('pipe resume');
    src.resume();
  }

  return dest;
}
```
- example usage
```shell
...
function Trumpet () {
    var self = this;
    if (!(this instanceof Trumpet)) return new Trumpet;
    Duplex.call(this);
    this._tokenize = tokenize();
    this._writing = false;
    this._piping = false;
    this._select = this._tokenize.pipe(select());
    this._select.once('end', function () {
        self.emit('_end');
        self.push(null)
    });
    this.once('finish', function () { self._tokenize.end() });
}
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.push"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>push (chunk, encoding)](#apidoc.element.trumpet.super_.super_.prototype.push)
- description and source-code
```javascript
push = function (chunk, encoding) {
  var state = this._readableState;

  if (util.isString(chunk) && !state.objectMode) {
    encoding = encoding || state.defaultEncoding;
    if (encoding !== state.encoding) {
      chunk = new Buffer(chunk, encoding);
      encoding = '';
    }
  }

  return readableAddChunk(this, state, chunk, encoding, false);
}
```
- example usage
```shell
...
Duplex.call(this);
this._tokenize = tokenize();
this._writing = false;
this._piping = false;
this._select = this._tokenize.pipe(select());
this._select.once('end', function () {
    self.emit('_end');
    self.push(null)
});
this.once('finish', function () { self._tokenize.end() });
}

Trumpet.prototype.pipe = function () {
this._piping = true;
return Duplex.prototype.pipe.apply(this, arguments);
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.read"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>read (n)](#apidoc.element.trumpet.super_.super_.prototype.read)
- description and source-code
```javascript
read = function (n) {
  debug('read', n);
  var state = this._readableState;
  var nOrig = n;

  if (!util.isNumber(n) || n > 0)
    state.emittedReadable = false;

  // if we're doing read(0) to trigger a readable event, but we
  // already have a bunch of data in the buffer, then just trigger
  // the 'readable' event and move on.
  if (n === 0 &&
      state.needReadable &&
      (state.length >= state.highWaterMark || state.ended)) {
    debug('read: emitReadable', state.length, state.ended);
    if (state.length === 0 && state.ended)
      endReadable(this);
    else
      emitReadable(this);
    return null;
  }

  n = howMuchToRead(n, state);

  // if we've ended, and we're now clear, then finish it up.
  if (n === 0 && state.ended) {
    if (state.length === 0)
      endReadable(this);
    return null;
  }

  // All the actual chunk generation logic needs to be
  // *below* the call to _read.  The reason is that in certain
  // synthetic stream cases, such as passthrough streams, _read
  // may be a completely synchronous operation which may change
  // the state of the read buffer, providing enough data when
  // before there was *not* enough.
  //
  // So, the steps are:
  // 1. Figure out what the state of things will be after we do
  // a read from the buffer.
  //
  // 2. If that resulting state will trigger a _read, then call _read.
  // Note that this may be asynchronous, or synchronous.  Yes, it is
  // deeply ugly to write APIs this way, but that still doesn't mean
  // that the Readable class should behave improperly, as streams are
  // designed to be sync/async agnostic.
  // Take note if the _read call is sync or async (ie, if the read call
  // has returned yet), so that we know whether or not it's safe to emit
  // 'readable' etc.
  //
  // 3. Actually pull the requested chunks out of the buffer and return.

  // if we need a readable event, then we need to do some reading.
  var doRead = state.needReadable;
  debug('need readable', doRead);

  // if we currently have less than the highWaterMark, then also read some
  if (state.length === 0 || state.length - n < state.highWaterMark) {
    doRead = true;
    debug('length less than watermark', doRead);
  }

  // however, if we've ended, then there's no point, and if we're already
  // reading, then it's unnecessary.
  if (state.ended || state.reading) {
    doRead = false;
    debug('reading or ended', doRead);
  }

  if (doRead) {
    debug('do read');
    state.reading = true;
    state.sync = true;
    // if the length is currently zero, then we *need* a readable event.
    if (state.length === 0)
      state.needReadable = true;
    // call internal read method
    this._read(state.highWaterMark);
    state.sync = false;
  }

  // If _read pushed data synchronously, then 'reading' will be false,
  // and we need to re-evaluate how much data we can return to the user.
  if (doRead && !state.reading)
    n = howMuchToRead(nOrig, state);

  var ret;
  if (n > 0)
    ret = fromList(n, state);
  else
    ret = null;

  if (util.isNull(ret)) {
    state.needReadable = true;
    n = 0;
  }

  state.length -= n;

  // If we have nothing in the buffer, then we want to know
  // as soon as we *do* get something into the buffer.
  if (state.length === 0 && !state.ended)
    state.needReadable = true;

  // If we tried to read() past the EOF, then emit end on the next tick.
  if (nOrig !== n && state.ended && state.length === 0)
    endReadable(this);

  if (!util.isNull(ret))
    this.emit('data', ret);

  return ret;
}
```
- example usage
```shell
...
};

Trumpet.prototype._read = function (n) {
var row;
var self = this;
var buf, read = 0;
var s = this._select;
while ((row = s.read()) !== null) {
    if (row[0] === 'END') {
        this.push(row[1][1])
        read ++
    }
    else if (row[1] && row[1].length) {
        this.push(row[1]);
        read ++;
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.resume"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>resume ()](#apidoc.element.trumpet.super_.super_.prototype.resume)
- description and source-code
```javascript
resume = function () {
  var state = this._readableState;
  if (!state.flowing) {
    debug('resume');
    state.flowing = true;
    if (!state.reading) {
      debug('resume read 0');
      this.read(0);
    }
    resume(this, state);
  }
  return this;
}
```
- example usage
```shell
...
}
if (read === 0) s.once('readable', function () { self._read(n) });
};

Trumpet.prototype._write = function (buf, enc, next) {
if (!this._writing && !this._piping) {
    this._piping = true;
    this.resume();
}
return this._tokenize._write(buf, enc, next);
};

Trumpet.prototype.select = function (str, cb) {
var self = this;
var first = true;
...
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.setEncoding"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>setEncoding (enc)](#apidoc.element.trumpet.super_.super_.prototype.setEncoding)
- description and source-code
```javascript
setEncoding = function (enc) {
  if (!StringDecoder)
    StringDecoder = require('string_decoder/').StringDecoder;
  this._readableState.decoder = new StringDecoder(enc);
  this._readableState.encoding = enc;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.unpipe"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>unpipe (dest)](#apidoc.element.trumpet.super_.super_.prototype.unpipe)
- description and source-code
```javascript
unpipe = function (dest) {
  var state = this._readableState;

  // if we're not piping anywhere, then do nothing.
  if (state.pipesCount === 0)
    return this;

  // just one destination.  most common case.
  if (state.pipesCount === 1) {
    // passed in one, but it's not the right one.
    if (dest && dest !== state.pipes)
      return this;

    if (!dest)
      dest = state.pipes;

    // got a match.
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;
    if (dest)
      dest.emit('unpipe', this);
    return this;
  }

  // slow case. multiple pipe destinations.

  if (!dest) {
    // remove all.
    var dests = state.pipes;
    var len = state.pipesCount;
    state.pipes = null;
    state.pipesCount = 0;
    state.flowing = false;

    for (var i = 0; i < len; i++)
      dests[i].emit('unpipe', this);
    return this;
  }

  // try to find the right one.
  var i = indexOf(state.pipes, dest);
  if (i === -1)
    return this;

  state.pipes.splice(i, 1);
  state.pipesCount -= 1;
  if (state.pipesCount === 1)
    state.pipes = state.pipes[0];

  dest.emit('unpipe', this);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.unshift"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>unshift (chunk)](#apidoc.element.trumpet.super_.super_.prototype.unshift)
- description and source-code
```javascript
unshift = function (chunk) {
  var state = this._readableState;
  return readableAddChunk(this, state, chunk, '', true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.trumpet.super_.super_.prototype.wrap"></a>[function <span class="apidocSignatureSpan">trumpet.super_.super_.prototype.</span>wrap (stream)](#apidoc.element.trumpet.super_.super_.prototype.wrap)
- description and source-code
```javascript
wrap = function (stream) {
  var state = this._readableState;
  var paused = false;

  var self = this;
  stream.on('end', function() {
    debug('wrapped end');
    if (state.decoder && !state.ended) {
      var chunk = state.decoder.end();
      if (chunk && chunk.length)
        self.push(chunk);
    }

    self.push(null);
  });

  stream.on('data', function(chunk) {
    debug('wrapped data');
    if (state.decoder)
      chunk = state.decoder.write(chunk);
    if (!chunk || !state.objectMode && !chunk.length)
      return;

    var ret = self.push(chunk);
    if (!ret) {
      paused = true;
      stream.pause();
    }
  });

  // proxy all the other methods.
  // important when wrapping filters and duplexes.
  for (var i in stream) {
    if (util.isFunction(stream[i]) && util.isUndefined(this[i])) {
      this[i] = function(method) { return function() {
        return stream[method].apply(stream, arguments);
      }}(i);
    }
  }

  // proxy certain important events.
  var events = ['error', 'close', 'destroy', 'pause', 'resume'];
  forEach(events, function(ev) {
    stream.on(ev, self.emit.bind(self, ev));
  });

  // when we try to consume some more bytes, simply unpause the
  // underlying stream.
  self._read = function(n) {
    debug('wrapped _read', n);
    if (paused) {
      paused = false;
      stream.resume();
    }
  };

  return self;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
