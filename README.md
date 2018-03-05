
Lab 8
=====

Building and running instructions can be found online [here][opengl-build-instructions]
and a local offline version is included in this repo here: [build-instructions.md](build-instructions.md)

Assignment details can be found [here][assignment-details].

[opengl-build-instructions]: https://iondune.github.io/csc471/references/opengl-build
[assignment-details]: https://iondune.github.io/csc471/assignments/lab08



Known Issues
------------

* Resizing the window currently breaks the framebuffer effect.
  * To fix, the framebuffers would need to be resized in the resize callback,
    and the framebuffer size would need to be passed as a uniform to the blur shader.

