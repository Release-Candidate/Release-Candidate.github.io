+++
title = 'About'
date = 2024-02-10T16:20:24+01:00
+++

- [About Me](#about-me)
- [Projects](#projects)
  - [VS Code and VSCodium Extensions (TypeScript)](#vs-code-and-vscodium-extensions-typescript)
    - [Chez Scheme REPL](#chez-scheme-repl)
    - [OCaml Test Extensions](#ocaml-test-extensions)
  - [PureScript Projects (PureScript)](#purescript-projects-purescript)
  - [Program To Convert A Directory Of Obsidian Notes To Org-Mode Notes (Python)](#program-to-convert-a-directory-of-obsidian-notes-to-org-mode-notes-python)
  - [Browser Extensions (JavaScript)](#browser-extensions-javascript)
  - [Buck 2 Build System (Starlark, Python)](#buck-2-build-system-starlark-python)
  - [Python Converter for Maya Tzolk’in Dates (Python)](#python-converter-for-maya-tzolkin-dates-python)
  - [Smartphone Apps and a Cross-Platform GUI App (F#)](#smartphone-apps-and-a-cross-platform-gui-app-f)
  - [Go Projects (Go)](#go-projects-go)
  - [Performance Optimizations (Go, Haskell, C)](#performance-optimizations-go-haskell-c)
  - [Flix (Programming Language) Projects (Flix)](#flix-programming-language-projects-flix)
  - [WASM (Web Assembly) GC Project (WASM)](#wasm-web-assembly-gc-project-wasm)

## About Me

Hi!

My name is Roland Csaszar (pronouns: he/him/his) and I'm getting paid as a Linux C++ developer for almost 20 years now.

As an Emacs user of more than 20 years I made the switch to VS Code some time in fall of 2021.<br>
*How is that in line with being a proponent of "free as in speech"?*
Yes, it's complicated.[^1].

[^1]: Actions by Microsoft like in this PR [https://github.com/dotnet-foundation/Home/discussions/40](https://github.com/dotnet-foundation/Home/discussions/40) leading to this discussion [https://github.com/dotnet-foundation/Home/discussions/60](https://github.com/dotnet-foundation/Home/discussions/60) or (temporary) removing hot-reload in the OSS .Net 6 in favour of Visual Studio [https://github.com/dotnet/sdk/pull/22217](https://github.com/dotnet/sdk/pull/22217) were reasons why I stopped using .Net and F# at all. And important extensions like the remote development stuff (SSH, Docker, ...) Python and C# LSPs and extensions being closed source does not help me liking MS' way either.

## Projects

All open source projects are hosted on [https://github.com/Release-Candidate/](https://github.com/Release-Candidate/).
I also use a GitLab account, which is mainly used to file bug reports and make merge requests: [https://gitlab.com/ReleaseCandidate](https://gitlab.com/ReleaseCandidate).

The list of my "most important" (whatever that means) open source projects, roughly in order of number of users is below. Smaller stuff that isn't being mentioned below can by found at [GitHub - List of my Repositories](https://github.com/Release-Candidate?tab=repositories).

### VS Code and VSCodium Extensions (TypeScript)

#### Chez Scheme REPL

An extension for Chez Scheme, it uses the REPL for auto-completions and to evaluate expressions. The extension does syntax highlighting, shows the documentation on hover, provides auto-completion, marks errors and multiple ways to interact with the Chez Scheme REPL.

- [Chez Scheme REPL GitHub](https://github.com/Release-Candidate/vscode-scheme-repl)
- [Chez Scheme REPL - Open VSX Registry](https://open-vsx.org/extension/Release-Candidate/vscode-scheme-repl)
- [Chez Scheme REPL - VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=release-candidate.vscode-scheme-repl)

#### OCaml Test Extensions

Extension to run OCaml Alcotest tests, both inline and "normal", in VS Code's Test Explorer Panel:

- [OCaml Alcotest Test Explorer GitHub](https://github.com/Release-Candidate/vscode-ocaml-alcotest-test-adapter)
- [OCaml Alcotest Test Explorer - Open VSX Registry](https://open-vsx.org/extension/Release-Candidate/vscode-ocaml-alcotest-test-adapter)
- [OCaml Alcotest Test Explorer - VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=release-candidate.vscode-ocaml-alcotest-test-adapter)

Extension to run OCaml inline and inline expect tests in VS Code's Test Explorer Panel:

- [OCaml Expect and Inline Test Explorer for Visual Studio Code GitHub](https://github.com/Release-Candidate/vscode-ocaml-expect-inline)
- [OCaml Expect and Inline Test Explorer for Visual Studio Code - Open VSX Registry](https://open-vsx.org/extension/Release-Candidate/vscode-ocaml-expect-inline)
- [OCaml Expect and Inline Test Explorer for Visual Studio Code- VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=release-candidate.vscode-ocaml-expect-inline)

### PureScript Projects (PureScript)

Notoy is web app to save notes of a website as a markdown, Org-Mode or plain text file on a mobile device. See also the [Notoy Browser Extension](#browser-extensions-javascript):

- [Notoy Progressive Web App - GitHub Sources](https://github.com/Release-Candidate/Notoy-PWA)
- [Notoy Progressive Web App - Website](https://release-candidate.github.io/Notoy-PWA/http/index.html)

A PureScript library packaging `DateTimeFormat` for usage with PureScript:

- [purescript-datetimeformat GitHub](https://github.com/Release-Candidate/purescript-datetimeformat)

### Program To Convert A Directory Of Obsidian Notes To Org-Mode Notes (Python)

Obs2Org is a cross platform command (works on *BSD, Linux, OS X and Windows) line program to convert Obsidian style Markdown files to Org-Mode files for Emacs and other Editors that support Org-Mode.

It converts the Markdown files using Pandoc and afterwards corrects the links to headings in other Org-Mode files, converts the hash-tag style Obsidian tags to Org-Mode style tags and puts angle brackets around dates.

- [Obs2Org GitHub](https://github.com/Release-Candidate/Obs2Org)

### Browser Extensions (JavaScript)

Browser extensions to save the current page's URL with comments to a markdown, org-mode or plain text file:

- [Notoy-BrowserExtensions GitHub](https://github.com/Release-Candidate/Notoy-BrowserExtensions)
- [Notoy - Firefox Add-Ons](https://addons.mozilla.org/de/firefox/addon/roland-csaszar/)
- [Notoy - Chrome Web Store](https://chromewebstore.google.com/detail/notoy/ejmcdafpeijhmmmfebmdpcmgaaoaminc)
- [Notoy - Microsoft Edge Add-Ons](https://microsoftedge.microsoft.com/addons/detail/notoy/nnocnobndadkcpggkegckgcnehmnohbl)

Browser extensions to go through all bookmarks and be able to visit and delete each one:

- [Bookmark-Visitor GitHub](https://github.com/Release-Candidate/Bookmark-Visitor)
- [Bookmark-Visitor - Firefox Add-Ons](https://addons.mozilla.org/en-US/firefox/addon/bookmark-visitor/)
- [Bookmark-Visitor - Chrome Web Store](https://chromewebstore.google.com/detail/bookmark-visitor/jhbibokejcdmofiiiakbobcpeefjeoeb)

### Buck 2 Build System (Starlark, Python)

The Python script named `dromedary.py` (in analogy to [Reindeer](https://github.com/facebookincubator/reindeer), which enables using Cargo packages in Rust Buck 2 projects), that I made for Meta, which helps using OCaml packages with Buck 2.

- [ocaml-scripts by Meta, GitHub](https://github.com/facebook/ocaml-scripts)

Example OCaml project on how to use the above Buck 2 integration of Opam (the OCaml package manager) and build OCaml using Buck 2:

- [OCaml Buck2 Examples GitHub](https://github.com/Release-Candidate/OCaml-Buck-2-Examples)

Two example projects on how to use Buck 2 to build and test C++, using VCPKG or Conan as package manager:

- [C++ Buck2 Vcpkg Examples GitHub](https://github.com/Release-Candidate/Cxx-Buck2-vcpkg-Examples)
- [C++ Buck2 Conan Examples GitHub](https://github.com/Release-Candidate/Cxx-Buck2-Conan-Examples)

### Python Converter for Maya Tzolk’in Dates (Python)

This converts mayan Tzolk’in dates to Gregorian dates and vice versa:

- [tzolkin-calendar GitHub](https://github.com/Release-Candidate/tzolkin-calendar)
- [tzolkin-calendar - PyPI](https://pypi.org/project/tzolkin-calendar/)

### Smartphone Apps and a Cross-Platform GUI App (F#)

Three smartphone apps using Fabulous, an Elm-MVU framework for F# using Xamarin:

- [Tzolkin GitHub](https://github.com/Release-Candidate/Tzolkin)
- [NineWaves Github](https://github.com/Release-Candidate/NineWaves)
- [LunaZodiaco](https://github.com/Release-Candidate/LunaZodiaco)

A combination of all of the above NuGet packages in a single window desktop app using Avalonia via Avalonia FuncUI:

- [TzolkinWaves](https://github.com/Release-Candidate/TzolkinWaves)

### Go Projects (Go)

A gap buffer implementation in Go, which is a data structure used to hold editable text:

- [go-gap-buffer GitHub](https://github.com/Release-Candidate/go-gap-buffer)
- [go-gap-buffer - pkg.go.dev](https://pkg.go.dev/github.com/Release-Candidate/go-gap-buffer)

### Performance Optimizations (Go, Haskell, C)

This has been my go [*Oh, what a pun!*] at [The One Billion Row Challenge](https://github.com/gunnarmorling/1brc?tab=readme-ov-file#rules-and-limits). There you can see the step-by-step iterations I used to optimize a Go program from taking 100s to 3.2s for the parsing of 1 billion rows of data. And Haskell and C versions of the same program too.

- [1 Billion Row Challenge GitHub](https://github.com/Release-Candidate/1-billion-row-challenge)

### Flix (Programming Language) Projects (Flix)

Flix assertions is a package for the Flix language which contains additional test assertions to use with Flix' integrated tests:

- [Flix Assertions GitHub](https://github.com/Release-Candidate/flix-assertions)

And some source code in Flix, an implementation of parser combinators.

- [Flix Test GitHub](https://github.com/Release-Candidate/flix-test)

### WASM (Web Assembly) GC Project (WASM)

WASM assembly programs using the WASM GC (and other related) extension in the WASM text format (WAT).

- [WASM-stuff GitHub](https://github.com/Release-Candidate/WASM-stuff)
