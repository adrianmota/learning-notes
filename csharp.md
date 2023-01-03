# C# Programming Language

## What is C#?

C# is a general-purpose, multi-paradigm, high-level programming language developed by Microsoft.

It supports static typing, strong typing, lexical scope, functional and object oriented programming.
This language can be used to develop desktop apps, web apps and web services.

C# runs in the .NET Framework, but now it is supported by other platforms that implement the CLI (Common Language Infrastructure), like .NET and Mono.

## Characteristics

C# is a portable language, due to the technical standard and specification called Common Language Infrastructure (CLI), which allows the
language and others to be run in any platform without being rewritten for specific architectures. .NET Framework, .NET and Mono are implementations 
of the CLI.

## Hello World Example

Here is a basic example of a Hello World program in C#

```
using System;

namespace HelloWorld {
    public class Program {
        public static void Main(string[] args) {
            Console.WriteLine("Hello, World!");
        }
    }
}
```
