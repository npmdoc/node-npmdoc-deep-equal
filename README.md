# api documentation for  [deep-equal (v1.0.1)](https://github.com/substack/node-deep-equal#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-deep-equal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-deep-equal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-deep-equal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-deep-equal)
#### node's assert.deepEqual algorithm

[![NPM](https://nodei.co/npm/deep-equal.png?downloads=true)](https://www.npmjs.com/package/deep-equal)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deep-equal/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-deep-equal_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deep-equal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-deep-equal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-deep-equal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "James Halliday",
        "email": "mail@substack.net",
        "url": "http://substack.net"
    },
    "bugs": {
        "url": "https://github.com/substack/node-deep-equal/issues"
    },
    "dependencies": {},
    "description": "node's assert.deepEqual algorithm",
    "devDependencies": {
        "tape": "^3.5.0"
    },
    "directories": {
        "lib": ".",
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "f5d260292b660e084eff4cdbc9f08ad3247448b5",
        "tarball": "https://registry.npmjs.org/deep-equal/-/deep-equal-1.0.1.tgz"
    },
    "gitHead": "59c511f5aeae19e3dd1de054077a789d7302be34",
    "homepage": "https://github.com/substack/node-deep-equal#readme",
    "keywords": [
        "equality",
        "equal",
        "compare"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "substack",
            "email": "mail@substack.net"
        }
    ],
    "name": "deep-equal",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/substack/node-deep-equal.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": {
            "ie": [
                6,
                7,
                8,
                9
            ],
            "ff": [
                3.5,
                10,
                15
            ],
            "chrome": [
                10,
                22
            ],
            "safari": [
                5.1
            ],
            "opera": [
                12
            ]
        }
    },
    "version": "1.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module deep-equal](#apidoc.module.deep-equal)
1.  [function <span class="apidocSignatureSpan">deep-equal.</span>is_arguments (object)](#apidoc.element.deep-equal.is_arguments)
1.  [function <span class="apidocSignatureSpan">deep-equal.</span>keys ()](#apidoc.element.deep-equal.keys)

#### [module deep-equal.is_arguments](#apidoc.module.deep-equal.is_arguments)
1.  [function <span class="apidocSignatureSpan">deep-equal.</span>is_arguments (object)](#apidoc.element.deep-equal.is_arguments.is_arguments)
1.  [function <span class="apidocSignatureSpan">deep-equal.is_arguments.</span>supported (object)](#apidoc.element.deep-equal.is_arguments.supported)
1.  [function <span class="apidocSignatureSpan">deep-equal.is_arguments.</span>unsupported (object)](#apidoc.element.deep-equal.is_arguments.unsupported)

#### [module deep-equal.keys](#apidoc.module.deep-equal.keys)
1.  [function <span class="apidocSignatureSpan">deep-equal.</span>keys ()](#apidoc.element.deep-equal.keys.keys)
1.  [function <span class="apidocSignatureSpan">deep-equal.keys.</span>shim (obj)](#apidoc.element.deep-equal.keys.shim)



# <a name="apidoc.module.deep-equal"></a>[module deep-equal](#apidoc.module.deep-equal)

#### <a name="apidoc.element.deep-equal.is_arguments"></a>[function <span class="apidocSignatureSpan">deep-equal.</span>is_arguments (object)](#apidoc.element.deep-equal.is_arguments)
- description and source-code
```javascript
function supported(object) {
  return Object.prototype.toString.call(object) == '[object Arguments]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.deep-equal.keys"></a>[function <span class="apidocSignatureSpan">deep-equal.</span>keys ()](#apidoc.element.deep-equal.keys)
- description and source-code
```javascript
function keys() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.deep-equal.is_arguments"></a>[module deep-equal.is_arguments](#apidoc.module.deep-equal.is_arguments)

#### <a name="apidoc.element.deep-equal.is_arguments.is_arguments"></a>[function <span class="apidocSignatureSpan">deep-equal.</span>is_arguments (object)](#apidoc.element.deep-equal.is_arguments.is_arguments)
- description and source-code
```javascript
function supported(object) {
  return Object.prototype.toString.call(object) == '[object Arguments]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.deep-equal.is_arguments.supported"></a>[function <span class="apidocSignatureSpan">deep-equal.is_arguments.</span>supported (object)](#apidoc.element.deep-equal.is_arguments.supported)
- description and source-code
```javascript
function supported(object) {
  return Object.prototype.toString.call(object) == '[object Arguments]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.deep-equal.is_arguments.unsupported"></a>[function <span class="apidocSignatureSpan">deep-equal.is_arguments.</span>unsupported (object)](#apidoc.element.deep-equal.is_arguments.unsupported)
- description and source-code
```javascript
function unsupported(object){
  return object &&
    typeof object == 'object' &&
    typeof object.length == 'number' &&
    Object.prototype.hasOwnProperty.call(object, 'callee') &&
    !Object.prototype.propertyIsEnumerable.call(object, 'callee') ||
    false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.deep-equal.keys"></a>[module deep-equal.keys](#apidoc.module.deep-equal.keys)

#### <a name="apidoc.element.deep-equal.keys.keys"></a>[function <span class="apidocSignatureSpan">deep-equal.</span>keys ()](#apidoc.element.deep-equal.keys.keys)
- description and source-code
```javascript
function keys() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.deep-equal.keys.shim"></a>[function <span class="apidocSignatureSpan">deep-equal.keys.</span>shim (obj)](#apidoc.element.deep-equal.keys.shim)
- description and source-code
```javascript
function shim(obj) {
  var keys = [];
  for (var key in obj) keys.push(key);
  return keys;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
