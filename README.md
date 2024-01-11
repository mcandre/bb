# bb: the awk build system

> Your scientists were so preoccupied with whether they could, they didn’t stop to think if they should.

# ABOUT

`bb` demonstrates a working build system written in GNU awk, to organize build steps for awk projects.

# EXAMPLE

```console
$ cd example

$ ./bb
bzz bzz

$ ./bb help
Usage: bb [<task> [<task> [<task> ...]]]

Tasks:

* all
* help
* test
```

# CONFIGURATION

Tasks are implemented with awk functions.

Task trees are implemented with functions that call other functions.

That's it.

# REQUIREMENTS

* a UNIX environment with [coreutils](https://www.gnu.org/software/coreutils/) / [base](http://ftp.freebsd.org/pub/FreeBSD/releases/) / [macOS](https://www.apple.com/macos) / [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) / etc.
* GNU [awk](https://www.gnu.org/software/gawk/manual/gawk.html) v5+

# SEE ALSO

* Inspiration from [nobuild](https://github.com/tsoding/nobuild), a convention for C/C++ build systems
* [bashate](https://github.com/openstack/bashate), a shell script style linter
* [beltaloada](https://github.com/mcandre/beltaloada), a guide to writing build systems for (POSIX) sh
* [dale](https://github.com/mcandre/dale) builds D projects
* [Gradle](https://gradle.org/), a build system for JVM projects
* [jelly](https://github.com/mcandre/jelly), a JSON task runner
* [lake](https://luarocks.org/modules/steved/lake), a Lua task runner
* [Leiningen](https://leiningen.org/) + [lein-exec](https://github.com/kumarshantanu/lein-exec), a Clojure task runner
* [lichen](https://github.com/mcandre/lichen), a sed task runner
* [Mage](https://magefile.org/), a task runner for Go projects
* [mian](https://github.com/mcandre/mian), a task runner for (Chicken) Scheme Lisp
* [npm](https://www.npmjs.com/), [Grunt](https://gruntjs.com/), Node.js task runners
* [POSIX make](https://pubs.opengroup.org/onlinepubs/009695299/utilities/make.html), a task runner standard for C/C++ and various other software projects
* [Rake](https://ruby.github.io/rake/), a task runner for Ruby projects
* [Rebar3](https://www.rebar3.org/), a build system for Erlang projects
* [rez](https://github.com/mcandre/rez) builds C/C++ projects
* [Shake](https://shakebuild.com/), a task runner for Haskell projects
* [ShellCheck](https://www.shellcheck.net/), a shell script linter with a rich collection of rules for promoting safer scripting
* [slick](https://github.com/mcandre/slick), a linter to enforce stricter, unextended POSIX sh syntax compliance
* [stank](https://github.com/mcandre/stank), a collection of POSIX-y shell script linters
* [tinyrick](https://github.com/mcandre/tinyrick) for Rust projects

🐝
