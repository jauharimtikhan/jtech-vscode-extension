# JTech Framework Support

<p align="center">
  <img src="./logo-jtech.png" alt="JTech Logo" width="128" height="128">
</p>

<p align="center">
    <strong>The official Visual Studio Code extension for the JTech Framework.</strong><br>
    Supercharge your development workflow with rich syntax highlighting, intelligent snippets, and dedicated file icons for <code>.jtech.php</code> files.
</p>

<p align="center">
    <a href="https://github.com/jauharimtikhan/jtech-vscode-extension/blob/main/LICENSE">
        <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="JTech License">
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=jauhar-jtech.jtech-framework-support">
        <img src="https://img.shields.io/badge/version-1.0.0-green.svg" alt="Version">
    </a>
</p>

---

## 🚀 Features

This extension provides a complete tooling ecosystem for JTech Framework developers:

- **🎨 Syntax Highlighting**: Full colorization for `.jtech.php` files. It intelligently distinguishes between HTML, native PHP code, and JTech Blade-like directives (e.g., `@if`, `@foreach`, `{{ $var }}`).
- **⚡ Smart Snippets**: A comprehensive collection of snippets for rapid development. Type `foreach`, `section`, or `auth` and hit Tab to generate complex blocks instantly.
- **🏠 Emmet Support**: Integrated HTML expansion. Type `div.container>ul>li*3` inside a JTech file and expand it seamlessly.
- **✨ File Icons**: Distinguish your JTech views instantly in the file explorer with the custom JTech icon set.
- **🛠️ HTML5 Boilerplate**: Type `!` to generate a standard HTML5 structure ready for JTech views.

---

## 📸 Preview

_(Place a GIF or Screenshot of your syntax highlighting here to show off the colors)_

---

## 📝 Snippets Cheat Sheet

Here are some of the most useful snippets included in this extension:

### Logic & Control Flow

| Prefix    | Output                                | Description                    |
| :-------- | :------------------------------------ | :----------------------------- |
| `if`      | `@if (...) ... @endif`                | Basic If block                 |
| `ifelse`  | `@if ... @else ... @endif`            | If-Else block                  |
| `foreach` | `@foreach (...) ... @endforeach`      | Iterate over collections       |
| `forelse` | `@forelse ... @empty ... @endforelse` | Loop with empty fallback       |
| `auth`    | `@auth ... @endauth`                  | Check if user is authenticated |
| `guest`   | `@guest ... @endguest`                | Check if user is a guest       |

### Layouts & Components

| Prefix    | Output                             | Description              |
| :-------- | :--------------------------------- | :----------------------- |
| `extends` | `@extends('layout')`               | Extend a master layout   |
| `section` | `@section('name') ... @endsection` | Define a content section |
| `yield`   | `@yield('content')`                | Display section content  |
| `include` | `@include('view.name')`            | Include a partial view   |
| `x`       | `<x-component />`                  | Insert a component       |

### Data Display

| Prefix | Output         | Description                |
| :----- | :------------- | :------------------------- |
| `echo` | `{{ $var }}`   | Echo data (escaped)        |
| `raw`  | `{!! $var !!}` | Echo raw data (unescaped)  |
| `dd`   | `@dd($var)`    | Dump and Die for debugging |

### HTML Helpers

| Prefix | Output               | Description                |
| :----- | :------------------- | :------------------------- |
| `!`    | `<!DOCTYPE html>...` | Complete HTML5 Boilerplate |
| `php`  | `<?php ... ?>`       | Inline PHP tag             |

---

## ⚙️ Installation

### Via Marketplace

1. Open **Visual Studio Code**.
2. Go to the **Extensions** view (`Ctrl+Shift+X`).
3. Search for **"JTech Framework Support"**.
4. Click **Install**.

### Via VSIX (Manual)

1. Download the `.vsix` file from the repository releases.
2. In VS Code, open the Command Palette (`Ctrl+Shift+P`).
3. Type **"Install from VSIX"** and select the file.

---

## 🎨 Theme Support

This extension is designed to work seamlessly with standard VS Code themes.

- **Directives** (`@if`, `@section`) follow the _Keyword/Control_ color scheme (usually Purple/Red).
- **PHP Variables** inside `{{ }}` follow your theme's PHP color settings.
- **HTML Tags** follow your theme's standard HTML colors.

---

## 🤝 Contributing

Found a bug or want to add a new snippet? Contributions are welcome!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/NewSnippet`).
3. Commit your changes.
4. Push to the branch and open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
    Built with ❤️ by <strong>JTech Forge</strong>.
</p>
