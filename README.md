# [meta] [![Clojars Project][7]][8][![CircleCI][9]][10][![Downloads][13]][14]
<!---[![Dependencies Status][11]][12]--->
A stack.

<img src="https://raw.githubusercontent.com/cljs/logo/master/cljs.png" width="100" alt="CLJS Logo">
<img src="http://boot-clj.com/assets/images/logos/boot-logo-3.png" width="100" alt="Boot Logo">
<img src="http://hoplon.io/images/logos/hoplon-logo.png" width="100" alt="Hoplon Logo">
<img src="http://s32.postimg.org/4k9q912x1/aar_QEIys.jpg" width="100" alt="Feathers.js Logo">
<img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="90" alt="Node.js Logo">
<img src="https://camo.githubusercontent.com/79904b8ba0d1bce43022bbd5710f0ea1db33f54f/68747470733a2f2f7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652d656c656374726f6e2f6d61737465722f656c656374726f6e2d6c6f676f2e737667" width="90" alt="Electron Logo">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Atom_editor_logo.svg/2000px-Atom_editor_logo.svg.png" width="100" alt="Atom Logo">
<img src="https://cdn.worldvectorlogo.com/logos/docker.svg" width="100" alt="Docker Logo">

***

## What is [meta]?
[meta] is a stack for building tech startups using Clojure(Script).

## Why [meta]?
We built [meta] out of the idea that an Open Source stack could be used to build a startup. We named it [meta] as a reminder that software does not take one form and like ideas, should continuously evolve. [meta] is an attempt at building the quickest path from idea to startup.

<img src="https://raw.githubusercontent.com/cljs/logo/master/cljs.png" width="240" alt="CLJS Logo" align="left">
## [meta] Internals
[meta] is written in Clojure(Script) and built using: 
- [Boot][1] - Build tooling for Clojure.
- [Hoplon][2] - ClojureScript Web Framework.
- [Feathers.js][3] - An open source REST and realtime API layer for modern applications.
- [Node.js][4] - JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Electron][5] - Build cross platform desktop apps with JavaScript, HTML, and CSS.
- [Atom][6] - A hackable text editor for the 21st Century.

***

<img src="http://boot-clj.com/assets/images/logos/boot-logo-3.png" width="180" alt="Boot Logo" align="right">
## Using [meta] ... with Boot
[meta] is powered by Boot, an environment for building applications using clojure.
To use [meta] `require` it in your build.boot file. Thanks to Boot, [meta] is built with itself.

```clojure
(set-env! :dependencies '[[degree9/meta "0.0.0"]])
(require '[meta.boot :as meta])

(meta/init!)
```

***

<img src="http://hoplon.io/images/logos/hoplon-logo.png" width="220" alt="Hoplon Logo" align="left">
## ClojureScript in the Browser ... with Hoplon
We believe in building universal technologies and the web is the most accessible platform available. [meta] builds upon Hoplon to provide abstractions for the DOM.

```clojure
(page "index.html")

(html
  (head
    (title "[meta]"))
  (body
    (p "Hello!")))
```

***

<img src="http://s32.postimg.org/4k9q912x1/aar_QEIys.jpg" width="180" alt="Feathers.js Logo" align="right">
## Realtime Communication ... with Feathers.js
[meta] provides both REST and Realtime communication via FeatherScript, a wrapper around Feathers.js implemented in ClojureScript. Feathers enables event-based communication between clients and servers and other API's including persistent data stores.
```clojure
```

***

<img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="180" alt="Node.js Logo" align="left">
## ClojureScript on the Server ... with Node.js
[meta] is built entirely out of Clojure(Script) including the backend. This means compiling to JavaScript and running on Node.js.
```clojure
```

***

<img src="https://camo.githubusercontent.com/79904b8ba0d1bce43022bbd5710f0ea1db33f54f/68747470733a2f2f7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652d656c656374726f6e2f6d61737465722f656c656374726f6e2d6c6f676f2e737667" width="180" alt="Electron Logo" align="right">
## ClojureScript on the Client ... with Electron
[meta] can package Client/Server applications with Electron. Building cross-platform Clojure(Script) applications.
```clojure
```

***

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Atom_editor_logo.svg/2000px-Atom_editor_logo.svg.png" width="180" alt="Atom Logo" align="left">
## Developed ... with Atom
[meta] is being cultivated within the Atom text editor.
```clojure
```

***

<img src="https://cdn.worldvectorlogo.com/logos/docker.svg" width="180" alt="Docker Logo" align="right">
## Containerization ... with Docker
[meta] server applications can be containerized for scalability through docker.
```clojure
```

***

[1]: http://boot-clj.com
[2]: http://hoplon.io
[3]: http://feathersjs.com
[4]: http://nodejs.org
[5]: http://electron.atom.io
[6]: http://atom.io
[7]: https://img.shields.io/clojars/v/degree9/meta.svg
[8]: https://clojars.org/degree9/meta
[9]: https://circleci.com/gh/degree9/meta.svg?style=svg
[10]: https://circleci.com/gh/degree9/meta
[11]: https://jarkeeper.com/degree9/meta/status.svg
[12]: https://jarkeeper.com/degree9/meta
[13]: https://jarkeeper.com/degree9/meta/downloads.svg
[14]: https://jarkeeper.com/degree9/meta