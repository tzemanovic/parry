<p align="center">
    <a href="https://discord.gg/vt9DJSW">
        <img src="https://img.shields.io/discord/507548572338880513.svg?logo=discord&colorB=7289DA">
    </a>
    <a href="https://crates.io/crates/cdl2d">
         <img src="http://meritbadge.herokuapp.com/cdl2d?style=flat-square" alt="crates.io">
    </a>
    <a href="https://crates.io/crates/cdl3d">
         <img src="http://meritbadge.herokuapp.com/cdl3d?style=flat-square" alt="crates.io">
    </a>
    <a href="https://circleci.com/gh/dimforge/cdl">
        <img src="https://circleci.com/gh/dimforge/cdl.svg?style=svg" alt="Build status">
    </a>
</p>
<p align = "center">
    <strong>
        <a href="http://cdl.org/rustdoc/cdl2d">2D Documentation</a> | <a href="http://cdl.org/rustdoc/cdl3d">3D Documentation</a> | <a href="http://cdl.org">User Guide</a> | <a href="https://discourse.nphysics.org">Forum</a>
    </strong>
</p>

cdl
========

**cdl** is a 2 and 3-dimensional collision detection library written with
the rust programming language.

The official user guide is available [here](http://cdl.org).
The rustdoc documentation is available [for 3D](http://cdl.org/rustdoc/cdl3d) and [for 2D](http://cdl.org/rustdoc/cdl2d).

## Compilation
You will need the last stable build of the [rust compiler](http://www.rust-lang.org)
and the official package manager: [cargo](https://github.com/rust-lang/cargo).

Simply add one the following (or both) to your `Cargo.toml` file:

```
[dependencies]
cdl2d = "0.23" # For 2D collision detection.
cdl3d = "0.23" # For 3D collision detection.
```


## Features
- dynamic bounding volume tree based broad phase
- ball vs. ball collision detection,
- plane vs. any convex object collision detection.
- collision detection between arbitrary convex objects
- compound geometries
- ray-casting
- time of impact computation  for objects without rotational movement (compound vs. compound is not
  yet implemented)

And various traits for collision detectors and broad phase collision detection.
