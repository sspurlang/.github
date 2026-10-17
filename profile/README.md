<p align="center"><img src="https://sspurlang.github.io/sspur/assets/logo/sspur.svg" width="96" height="96" alt="SSPUR"></p>

<h3 align="center">SSPUR, a programming language for AI agents to write, read and maintain</h3>

<p align="center">
  <a href="https://sspurlang.github.io/"><b>sspurlang.github.io</b></a> ·
  <a href="https://sspurlang.github.io/sspur/">Docs</a> ·
  <a href="https://sspurlang.github.io/sspur/play/">Playground</a> ·
  <a href="https://sspurlang.github.io/sspur-packages/">Packages</a> ·
  <a href="https://sspurlang.github.io/sspur/pulse/">Pulse</a> ·
  <a href="https://github.com/sspurlang/sspur/releases/latest">Download</a>
</p>

SSPUR compiles to native code and checks effects and contracts at compile time, so a program says what it may do (network, files, database) and the compiler holds it to that. It comes with an HTTP client and server, SQLite, crypto, a debugger, a formatter, editor support and a package registry that runs entirely on GitHub.

```
brew install sspurlang/sspur/sspur      # or: curl -fsSL https://github.com/sspurlang/sspur/releases/latest/download/install.sh | sh
sspur new web-app notes && cd notes && sspur run
```

**Repositories**

- [sspurlang.github.io](https://github.com/sspurlang/sspurlang.github.io): SSPUR's home page, rebuilt every day by an SSPUR program.

- [sspur](https://github.com/sspurlang/sspur): the compiler, standard library, tools and docs.
- [sspur-packages](https://github.com/sspurlang/sspur-packages): the package registry's index; publish from the [Publish page](https://sspurlang.github.io/sspur-packages/publish/) or with `sspur publish`.
- `sspur-*`: packages published to the registry, such as [strings](https://github.com/sspurlang/sspur-strings), [jwt](https://github.com/sspurlang/sspur-jwt) and [jobs](https://github.com/sspurlang/sspur-jobs).

Created by [Utkarsha Vardhana](https://utkarshavardhana.github.io/). SSPUR is free and open source, under MIT or Apache 2.0.
