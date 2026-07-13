<p align="center">
  <img src="https://raw.githubusercontent.com/dfkup/dfkup/main/.github/dfkup.png" alt="DFkup" width="80px" height="80px"><br>
  <strong>DFkup</strong> &mdash; <em>/diː ɛf kʌp/</em><br>
  VSCode Syntax Highlighting<br>
  A fast scripting language &bullet; Typed &bullet; Stack-based VM &bullet; JIT Compiler
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=openpeeps.dfkup-vscode">Install from VSCode Marketplace</a> &bull;
  <a href="https://dfkup.github.io/dfkup/">API Reference</a>
</p>

### About
This is a Visual Studio Code extension that provides syntax highlighting for **DFkup**, a functional, indent-based scripting language designed to be enjoyable, easy to learn and work with so you **don't f\*ck up!**

DFkup is built on top of [VanCode](https://github.com/openpeeps/vancode), a modular CodeGen, VM and JIT compiler written in Nim. The JIT compiler is powered by [DynASM](https://staff.fnwi.uva.nl/h.vandermeer/docs/lua/luajit/dynasm_features.html), assembling code at runtime.

### Features
- Full syntax highlighting for `.dfkup` files
- Support for:
  - **Control flow**: `if`/`elif`/`else`, `for` loops, `while` loops
  - **Variable declarations**: `var` (mutable), `const` (compile-time)
  - **Function definitions** with named parameters, return types, and generics
  - **Data literals**: integers, floats, strings (single/double/triple-quoted, backtick)
  - **String interpolation** with `$var` syntax
  - **Array and object** literals (JSON-like)
  - **Built-in JSON** support
  - **Doc comments** (`##`) and **line comments** (`#`)

### Installation
Install from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=openpeeps.dfkup-vscode) or search for "DFkup" in the Extensions tab.

### Release Notes
See [CHANGELOG.md](./CHANGELOG.md) for release history.

---

LGPL-3.0-or-later | Copyright OpenPeeps & Contributors &mdash; All rights reserved.

