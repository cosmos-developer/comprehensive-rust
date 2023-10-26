# Summary

<!-- Keep first page as index.md to avoid giving it two names. -->
[Welcome to Comprehensive Rust 🦀](index.md)
- [Running the Course](running-the-course.md)
  - [Course Structure](running-the-course/course-structure.md)
  - [Keyboard Shortcuts](running-the-course/keyboard-shortcuts.md)
  - [Translations](running-the-course/translations.md)
  - [Session 1 & 2](running-the-course/welcome-1.md)
  - [Session 3 & 4](running-the-course/welcome-2.md)
  - [Session 5 & 6](running-the-course/welcome-3.md)
- [Using Cargo](cargo.md)
  - [Rust Ecosystem](cargo/rust-ecosystem.md)
  - [Code Samples](cargo/code-samples.md)
  - [Running Cargo Locally](cargo/running-locally.md)
  


# Session 1

----

- [What is Rust?](welcome-1/what-is-rust.md)
- [Hello World!](hello-world.md)
  - [Small Example](hello-world/small-example.md)
- [Why Rust?](why-rust.md)
  - [An Example in C](why-rust/an-example-in-c.md)
  - [Compile Time Guarantees](why-rust/compile-time.md)
  - [Runtime Guarantees](why-rust/runtime.md)
  - [Modern Features](why-rust/modern.md)
- [Basic Syntax](basic-syntax.md)
  - [Scalar Types](basic-syntax/scalar-types.md)
  - [Compound Types](basic-syntax/compound-types.md)
  - [References](basic-syntax/references.md)
    - [Dangling References](basic-syntax/references-dangling.md)
  - [Slices](basic-syntax/slices.md)
    - [String vs str](basic-syntax/string-slices.md)
  - [Functions](basic-syntax/functions.md)
    - [Rustdoc](basic-syntax/rustdoc.md)
    - [Methods](basic-syntax/methods.md)
    - [Overloading](basic-syntax/functions-interlude.md)
- [Exercises](exercises/day-1/morning.md)
  - [Implicit Conversions](exercises/day-1/implicit-conversions.md)
  - [Arrays and for Loops](exercises/day-1/for-loops.md)

# Session 2

- [Control Flow](control-flow.md)
  - [Blocks](control-flow/blocks.md)
  - [if expressions](control-flow/if-expressions.md)
  - [for expressions](control-flow/for-expressions.md)
  - [while expressions](control-flow/while-expressions.md)
  - [break & continue](control-flow/break-continue.md)
  - [loop expressions](control-flow/loop-expressions.md)

- [Variables](basic-syntax/variables.md)
  - [Type Inference](basic-syntax/type-inference.md)
  - [static & const](basic-syntax/static-and-const.md)
  - [Scopes and Shadowing](basic-syntax/scopes-shadowing.md)
- [Enums](enums.md)
  - [Variant Payloads](enums/variant-payloads.md)
  - [Enum Sizes](enums/sizes.md)

- [Novel Control Flow](control-flow/novel.md)
  - [if let expressions](control-flow/if-let-expressions.md)
  - [while let expressions](control-flow/while-let-expressions.md)
  - [match expressions](control-flow/match-expressions.md)

- [Pattern Matching](pattern-matching.md)
  - [Destructuring Enums](pattern-matching/destructuring-enums.md)
  - [Destructuring Structs](pattern-matching/destructuring-structs.md)
  - [Destructuring Arrays](pattern-matching/destructuring-arrays.md)
  - [Match Guards](pattern-matching/match-guards.md)

- [Exercises](exercises/day-1/afternoon.md)
  - [Luhn Algorithm](exercises/day-1/luhn.md)
  - [Pattern Matching](exercises/day-1/pattern-matching.md)

# Session 3

----

- [Memory Management](memory-management.md)
  - [Stack vs Heap](memory-management/stack-vs-heap.md)
  - [Stack Memory](memory-management/stack.md)
  - [Manual Memory Management](memory-management/manual.md)
  - [Scope-Based Memory Management](memory-management/scope-based.md)
  - [Garbage Collection](memory-management/garbage-collection.md)
  - [Rust Memory Management](memory-management/rust.md)
- [Ownership](ownership.md)
  - [Move Semantics](ownership/move-semantics.md)
  - [Moved Strings in Rust](ownership/moved-strings-rust.md)
    - [Double Frees in Modern C++](ownership/double-free-modern-cpp.md)
  - [Moves in Function Calls](ownership/moves-function-calls.md)
  - [Copying and Cloning](ownership/copy-clone.md)
  - [Borrowing](ownership/borrowing.md)
    - [Shared and Unique Borrows](ownership/shared-unique-borrows.md)
  - [Lifetimes](ownership/lifetimes.md)
  - [Lifetimes in Function Calls](ownership/lifetimes-function-calls.md)
  - [Lifetimes in Data Structures](ownership/lifetimes-data-structures.md)
- [Structs](structs.md)
  - [Tuple Structs](structs/tuple-structs.md)
  - [Field Shorthand Syntax](structs/field-shorthand.md)
- [Methods](methods.md)
  - [Method Receiver](methods/receiver.md)
  - [Example](methods/example.md)
- [Exercises](exercises/day-2/morning.md)
  - [Storing Books](exercises/day-2/book-library.md)
  - [Health Statistics](exercises/day-2/health-statistics.md)

# Session 4

- [Standard Library](std.md)
  - [Option and Result](std/option-result.md)
  - [String](std/string.md)
  - [Vec](std/vec.md)
  - [HashMap](std/hashmap.md)
  - [Box](std/box.md)
    - [Recursive Data Types](std/box-recursive.md)
    - [Niche Optimization](std/box-niche.md)
  - [Rc](std/rc.md)
  - [Cell/RefCell](std/cell.md)
- [Modules](modules.md)
  - [Visibility](modules/visibility.md)
  - [Paths](modules/paths.md)
  - [Filesystem Hierarchy](modules/filesystem.md)
- [Exercises](exercises/day-2/afternoon.md)
  - [Iterators and Ownership](exercises/day-2/iterators-and-ownership.md)
  - [Strings and Iterators](exercises/day-2/strings-iterators.md)


# Session 5

----

- [Generics](generics.md)
  - [Generic Data Types](generics/data-types.md)
  - [Generic Methods](generics/methods.md)
  - [Monomorphization](generics/monomorphization.md)
- [Traits](traits.md)
  - [Trait Objects](traits/trait-objects.md)
  - [Deriving Traits](traits/deriving-traits.md)
  - [Default Methods](traits/default-methods.md)
  - [Trait Bounds](traits/trait-bounds.md)
  - [impl Trait](traits/impl-trait.md)
- [Important Traits](traits/important-traits.md)
  - [Iterator](traits/iterator.md)
  - [FromIterator](traits/from-iterator.md)
  - [From and Into](traits/from-into.md)
  - [Read and Write](traits/read-write.md)
  - [Drop](traits/drop.md)
  - [Default](traits/default.md)
  - [Operators: Add, Mul, ...](traits/operators.md)
  - [Closures: Fn, FnMut, FnOnce](traits/closures.md)
- [Exercises](exercises/day-3/morning.md)
  - [A Simple GUI Library](exercises/day-3/simple-gui.md)
  - [Points and Polygons](exercises/day-3/points-polygons.md)

# Session 6

- [Error Handling](error-handling.md)
  - [Panics](error-handling/panics.md)
    - [Catching Stack Unwinding](error-handling/panic-unwind.md)
  - [Structured Error Handling](error-handling/result.md)
  - [Propagating Errors with ?](error-handling/try-operator.md)
    - [Converting Error Types](error-handling/converting-error-types.md)
      - [Example](error-handling/converting-error-types-example.md)
    - [Deriving Error Enums](error-handling/deriving-error-enums.md)
    - [Dynamic Error Types](error-handling/dynamic-errors.md)
    - [Adding Context to Errors](error-handling/error-contexts.md)
- [Testing](testing.md)
  - [Unit Tests](testing/unit-tests.md)
  - [Test Modules](testing/test-modules.md)
  - [Documentation Tests](testing/doc-tests.md)
  - [Integration Tests](testing/integration-tests.md)
  - [Useful crates](testing/useful-crates.md)
- [Unsafe Rust](unsafe.md)
  - [Dereferencing Raw Pointers](unsafe/raw-pointers.md)
  - [Mutable Static Variables](unsafe/mutable-static-variables.md)
  - [Unions](unsafe/unions.md)
  - [Calling Unsafe Functions](unsafe/calling-unsafe-functions.md)
    - [Writing Unsafe Functions](unsafe/writing-unsafe-functions.md)
    - [Extern Functions](unsafe/extern-functions.md)
  - [Implementing Unsafe Traits](unsafe/unsafe-traits.md)
- [Contract introduction](contract/contract.md)
  - [Introduction to Solana contract](contract/solana.md)
  - [Introduction to Cosmos contract](contract/cosmos.md)
  - [Introduction to Polkadot contract](contract/polkadot.md)
- [Exercises](exercises/day-3/afternoon.md)
  - [Safe FFI Wrapper](exercises/day-3/safe-ffi-wrapper.md)


# Final Words

----

- [Thanks!](thanks.md)
- [Glossary](glossary.md)
- [Other Resources](other-resources.md)
- [Credits](credits.md)


# Solutions

----

- [Solutions](exercises/solutions.md)
  - [Day 1 Morning](exercises/day-1/solutions-morning.md)
  - [Day 1 Afternoon](exercises/day-1/solutions-afternoon.md)
  - [Day 2 Morning](exercises/day-2/solutions-morning.md)
  - [Day 2 Afternoon](exercises/day-2/solutions-afternoon.md)
  - [Day 3 Morning](exercises/day-3/solutions-morning.md)
  - [Day 3 Afternoon](exercises/day-3/solutions-afternoon.md)
