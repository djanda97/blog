+++
title = "[WIP] Getting out of your way: Go and Zig"
date = 2023-08-09
+++

## "The art of art, the glory of expression and the sunshine of the light of letters, is simplicity."  - Walt Whitman

**Note:** This post is a work-in-progress and content will be updated as I continue researching.

Go and Zig can be characterized as spritual successors to C due to having a minimal amount of keywords and concepts, allowing the constructs of the language to stay out of the developer's way so that they can focus on writing application logic.
While there are use cases why someone would want to use a programming language that offers more advanced features (e.g. Rust, C++, Haskell), the purpose of this post is to compare the following topics between Go and Zig:

- [Memory Management](#memory-management)
- [Concurrency](#concurrency)
- [Performance](#performance)
- [Interoperability with C](#interoperability-with-c)

---

### Memory Management

- Go
  - Garbage collection
- Zig
  - Manual memory management
  - Custom allocators

### Concurrency

- Go
  - Builtin primitives for concurrency
  - `go` keyword
  - Channels
- Zig
  - TODO

### Performance

- Go
  - TODO
- Zig
  - TODO

### Interoperability with C

- Go
  - Cgo
- Zig
  - `translate-c` command
  - Namespaced C code using builtin functions such as `@cImport`, `@cInclude`, and `@cDefine`

### Unique Features

- Go
  - Interfaces - Any struct that has all methods declared in an interface implicity satifies the interface.
- Zig
  - Comptime - Alternative to macros, can be used for generic programming
  - Build system

### Similarities

- TODO
