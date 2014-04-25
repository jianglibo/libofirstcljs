# libofirstcljs

FIXME: description

## Installation

Download from http://example.com/FIXME.

## Usage

lein ring server-headless 3000 &
lein trampoline cljsbuild repl-listen


# cljsbuild-example-simple

This is an example web application that uses [lein-cljsbuild][1],
[Ring][2], and [Compojure][3].  It demonstrates the use of
lein-cljsbuild to build ClojureScript into JavaScript.

To play around with this example project, you will first need
[Leiningen][4] installed.

## Running the App

Set up and start the server like this:

    $ cd example-projects/simple
    $ lein cljsbuild once
    $ lein ring server-headless 3000

Now, point your web browser at `http://localhost:3000`, and see the web app in action!

[1]: https://github.com/emezeske/lein-cljsbuild
[2]: https://github.com/mmcgrana/ring
[3]: https://github.com/weavejester/compojure
[4]: https://github.com/technomancy/leiningen


FIXME: explanation

    $ java -jar libofirstcljs-0.1.0-standalone.jar [args]

## Options

FIXME: listing of options this app accepts.

## Examples

...

### Bugs

...

### Any Other Sections
### That You Think
### Might be Useful

## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
