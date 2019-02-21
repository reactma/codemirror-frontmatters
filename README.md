# CodeMirror

## Frontmatters fork

This is a fork of CodeMirror with yaml ( original CodeMirror ), toml and json ( this fork ) front matters.

**CodeMirror main repository won't accept new mode anymore.**

## Usage

### Recommended - just use the frontmatter mode source code

For yaml-frontmatter mode, follow CodeMirror main site instruction

For toml-frontmatter & json-frontmatter mode, just download the source code and require them locally.

[tom-frontmatter source](https://github.com/reactma/codemirror-frontmatters/tree/master/mode/toml-frontmatter)
[json-frontmatter source](https://github.com/reactma/codemirror-frontmatters/tree/master/mode/json-frontmatter)

Code sample
```
import 'codemirror/mode/markdown/markdown'
import 'codemirror/mode/gfm/gfm'
import 'codemirror/mode/yaml/yaml'
import 'codemirror/mode/toml/toml'
import 'codemirror/mode/javascript/javascript'


import '/path/to/toml-frontmatter'
import '/path/to/json-frontmatter'

const codemirrorOption = {
    mode: 'yaml-frontmatter' // toml-frontmatter or json-frontmatter
}

```

### Not recommended 

Use this fork as CodeMirror repo at your risk. It will NOT be SYNCED with CodeMirror in time.

--

CodeMirror is a versatile text editor implemented in JavaScript for
the browser. It is specialized for editing code, and comes with over
100 language modes and various addons that implement more advanced
editing functionality. Every language comes with fully-featured code
and syntax highlighting to help with reading and editing complex code.

A rich programming API and a CSS theming system are available for
customizing CodeMirror to fit your application, and extending it with
new functionality.

You can find more information (and the
[manual](https://codemirror.net/doc/manual.html)) on the [project
page](https://codemirror.net). For questions and discussion, use the
[discussion forum](https://discuss.codemirror.net/).

See
[CONTRIBUTING.md](https://github.com/codemirror/CodeMirror/blob/master/CONTRIBUTING.md)
for contributing guidelines.

The CodeMirror community aims to be welcoming to everybody. We use the
[Contributor Covenant
(1.1)](http://contributor-covenant.org/version/1/1/0/) as our code of
conduct.

### Installation

Either get the [zip file](https://codemirror.net/codemirror.zip) with
the latest version, or make sure you have [Node](https://nodejs.org/)
installed and run:

    npm install codemirror

**NOTE**: This is the source repository for the library, and not the
distribution channel. Cloning it is not the recommended way to install
the library, and will in fact not work unless you also run the build
step.

### Quickstart

To build the project, make sure you have Node.js installed (at least version 6)
and then `npm install`. To run, just open `index.html` in your
browser (you don't need to run a webserver). Run the tests with `npm test`.
