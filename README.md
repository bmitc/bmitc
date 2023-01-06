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
* [Custom impelementation of the code in *Functional Web Development with Elixir, OTP, and Phoenix*](https://github.com/bmitc/functional-web-development-with-elixir). The Elixir code in the book is modernized, documented and typespecced, and is Dialyzer and Credo compliant.
* [Some Advent of Code solutions in Elixir Livebook notebooks](https://github.com/bmitc/advent-of-code)
* [Private, work in progress] Elixir library to allowing interfacing between Elixir and F# using an Elixir `Port`
  * Effectively turns an F# `MailboxProcessor` into an Elixir `GenServer`, using an Elixir `Port` (not a NIF)
  * Define messages in Elixir with automatic F# message generation and marshalling back and forth
  * Developed an F# library that implements encoding and decoding of the Erlang External Term Format
* [Private, work in progress] A home operating and automation system built with Elixir. It's early days and currently consists of a Philips Hue API client.

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
