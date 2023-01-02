# GHC

## BASIC

compile one file basically 
`ghc main.hs`

Compile and run instantly :
`runghc main.hs`

runghc interprets the source file instead of compiling it and does not create build artifacts. This makes it very useful when developing programs and can help accelerate the feedback loop. 

command line interactive interpreter (like python):
`ghci` 

## FLAGS

`-Wall`
The -Wall flag will enable GHC to emit warnings about our code.

`-O`
An `optimising' package of compiler flags, for faster code

`-o`
Output name for the binary ex (`ghc -o my_app main.hs`)


## FILE SUFFIXES

`.hs`
A Haskell module.

`.lhs`
A “literate Haskell” module.

`.hspp`
A file created by the preprocessor.

`.hi`
A Haskell interface file, probably compiler-generated.

`.hie`
An extended Haskell interface file, produced by the Haskell compiler.

`.hc`
Intermediate C file produced by the Haskell compiler.

`.c`
A C file not produced by the Haskell compiler.

`.ll`
An llvm-intermediate-language source file, usually produced by the compiler.

`.bc`
An llvm-intermediate-language bitcode file, usually produced by the compiler.

`.s`
An assembly-language soure file, usually produced by the compiler.

`.o`
An object file, produced by an assembler.
Files with other suffixes (or without suffixes) are passed straight to the linker.

