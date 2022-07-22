### Hello :wave:

```racket
(define bmitc me)
```

### Summary

```fsharp
type Human = struct end
type Me = Me of Human * seed: int64

Me(Human(), -3581020800L)
|> Knowledge.add ["mathematics"; "physics"; "electrical engineering"]
|> ProgrammingLanguage.add ["LabVIEW"; "F#"; "Racket"; "Elixir"; "Clojure"; "VHDL"]
|> Interest.add ["systems"; "design"; "art"; "thinking"; "FPGA"; "orcas"; "black holes"]
|> Status.add "thinking about thinking"
|> Wonder.direction "the fuzzier stuff in life"
```

![image](https://user-images.githubusercontent.com/65685447/151491530-e9a01eb0-4b97-410c-8cf5-c2eea62f651c.png)

### Repository highlights

#### Elixir projects
* [Simple blockchain implementation from *Introducing Blockchain with Lisp*](https://github.com/bmitc/introducing-blockchain-with-elixir). The Racket code was ported to Elixir and made idiomatic to Elixir.
* [Custom impelementation of the code in *Functional Web Development with Elixir, OTP, and Phoenix](https://github.com/bmitc/functional-web-development-with-elixir). The Elixir code in the book is modernized, documented and typespecced, and is Dialyzer and Credo compliant.
* An, at present private, Elixir library to allowing interfacing between Elixir and F# using an Elixir `Port`
  * Allows developer to define messages in Elixir that are then compiled to F# such that:
    * On the Elixir side, processes send messages to the `GenServer` without knowledge that inside the GenServer, it is marshalling messages back and forth between Elixir and F#
    * On the F# side, a `MailboxProcessor` receives messages from Elixir, which can then be processed in F#
    * Messages can be defined as asynchronous or synchronous
    * The message compiler handles all F# code generation of messages as discriminated unions and also the parsing logic in F#
    * The message compiler also handles code generation on the Elixir side to send and receive messages from F#
  * Send an Elixir `Port` is used, crashes in F# (although unlikely) will never reach Elixir or the BEAM VM since the Port runs F# as a separate OS process
  * Allows one to treat an F# program as if it was any other process or `GenServer` in Elixir
  * Allows Elixir developers to interface with .NET through F# and also write more robust and performant code in F# similar to how the code would be written in Elixir (functional programming with pattern matching)

#### F# projects
* [Functional-first implementation of the ray tracer in *The Ray Tracer Challenge*](https://github.com/bmitc/the-ray-tracer-challenge-fsharp)
* [Nand to Tetris / *Elements of Computing Systems* implementations](https://github.com/bmitc/nand2tetris). This includes:
  * HDL solutions in the book's custom HDL language
  * In progress implementation of the hardware chips and CPU in VHDL, intended to be a starting ground for learning VHDL and implementing the HACK CPU on an FPGA
  * F# implementations of the assembler and virtual machine, the latter still in work
  * F# implementation of a HACK CPU simulator, which is intended to serve as a test fixture for verifying the virtual machine implementation and is still in work
* A cross-platform, desktop-only GUI framework using F#, GLFW, and SkiaSharp
  * F# GLFW bindings and wrappers
  * Currently working on fleshing out the windowing framework to allow for multiple windows and functional event handlers
  * Repository is private for now
* [F# annotations for the book *The Little MLer*](https://github.com/bmitc/the-little-fsharper)

#### Various other projects
* [LabVIEW libraries and frameworks publiched for the JKI VI Package Manager (VIPM)](https://github.com/slo-systems). Includes:
  * [Implementaiton of a forward-mode automatic differentiation library](https://github.com/slo-systems/labview-automatic-differentiation)
  * [Functional array processing library](https://github.com/slo-systems/labview-functional-array)
  * [Finished but yet to be published] Finite-state machine actor compatible with the LabVIEW Actor Framework
* [Implementation of `async/await` and an actor framework in MIT/GNU Scheme](https://github.com/bmitc/mit-6.945-project). This was completed as an end-of-semester project for the MIT 6.945 Large-scale Symbolic Systems course with Gerald Sussman.
* [Notes and implementations from Racket School 2019 for the "How to Design Languages" track](https://github.com/bmitc/racket-school-2019)
* [Standard ML (SML) and Racket solutions for the Course course *Programming Languages* by Dan Grossman](https://github.com/bmitc/coursera-programming-languages)
* [Racket annotations and implementations for *The Little Schemer*](https://github.com/bmitc/the-little-schemer)
* [Beginnings of a Racket implementation for *The Ray Tracer Challenge*](https://github.com/bmitc/the-ray-tracer-challenge-racket)
* [Prolog solutions for the book *Thinking as Computation*](https://github.com/bmitc/thinking-as-computation/tree/main/prolog)

<!--
**bmitc/bmitc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
