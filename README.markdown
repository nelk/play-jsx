# JSX plugin for the Play framework 2.2.x

## Prerequisites

Play-JSX plugin only supports a native compiler.
The JSX compiler needs to be installed for this plugin to work.
Refer to the site of JSX for more information.

[JSX - a faster, safer, easier JavaScript](http://jsx.github.com/ "JSX - a faster, safer, easier JavaScript")

## Installation

To build and install this into your local ivy repository, you can run `sbt publishLocal` or `./activator publishLocal`

Add following to your projects `project/plugins.sbt`

    addSbtPlugin("com.github.hexx" % "play-jsx" % "0.0.3-SNAPSHOT")

After Installation, this plugin works like the built-in CoffeeScript compiler.

[Documentation: AssetsCoffeeScript - Playframework](http://www.playframework.org/documentation/latest/AssetsCoffeeScript "Documentation: AssetsCoffeeScript - Playframework")
