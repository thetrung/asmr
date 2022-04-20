# asmr
A high level, platform-independent, assembly-like language written in Rust. That you can jump everywhere and use code as data as you like.

### stage
It's still pretty early stage, base on some concepts learned from my `fib` repo experiments on various type of expression evaluation. 

### goal
- An interpreter will be there first, with the same speed with `LuaJIT` or near native code.
- A following compiler may be next, based on `inkwell` to build IR for LLVM, or just another bytecode compiler with VM to execute compiled source.
- It could be loosely or strong-typed inference, based on the experience we may have on actual interpreter performance.
- Also, it's because I like how we can control a program by every line with a pointer and manipulate its stack.

### purpose
- Clearly, it's for fun, usecase later.
- Also I want to attempt building up "flow" concept again with this.
- As said, I like to control the execution, i.e: we can debug easily in runtime with stack inspector, metaprogramming new keywords, interact with Rust libs.. etc 
