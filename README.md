<a href="https://marked.js.org">
  <img width="60px" height="60px" src="https://marked.js.org/img/logo-black.svg" align="right" />
</a>

# Marked Clone – TSIS 1 Subtask 2

This project was created by **Zhumanova Zhanel (ID: 22B030544)** as part of the *Introduction to Open Source* course, TSIS 1 Subtask 2.  
It is a student clone of **Marked**, a lightweight open-source Markdown parser written in JavaScript.  
The goal of this task is to demonstrate understanding of open-source project documentation and contribution guidelines.

---

## Prompt
A clone of “Marked” — a lightweight, open-source Markdown parser written in JavaScript with a simple web interface, README, and contribution guideline.



---

## Project Description
**Marked Clone** is a simplified educational version of the original open-source project *Marked*.  
It allows users to write Markdown text and instantly see it rendered into HTML, directly in the browser.  
The project demonstrates the use of open-source tools, documentation standards, and contribution processes.

---

## Features
- ⚡ Built for speed and simplicity  
- 🧩 Parses Markdown and outputs HTML instantly  
- 🌐 Works directly in the browser  
- 🎨 Minimal and lightweight design  

---

## Demo
You can try the original [Marked demo page](https://marked.js.org/demo/)  
or test this clone by opening the included `index.html` file in your browser.

---

## Installation
You can install the original **Marked** package using npm:

```bash
npm install marked

```

## Usage

<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Marked Clone Demo</title>
  </head>
  <body>
    <div id="content"></div>
    <script src="https://cdn.jsdelivr.net/npm/marked/lib/marked.umd.js"></script>
    <script>
      document.getElementById('content').innerHTML =
        marked.parse('# Hello from Marked Clone!\\n\\nThis text is **rendered** by our open-source project.');
    </script>
  </body>
</html>


**CLI**

``` bash
# Example with stdin input
$ marked -o hello.html
hello world
^D
$ cat hello.html
<p>hello world</p>
```

```bash
# Print all options
$ marked --help
```

**Project Structure**

/src             → JavaScript source files
/public          → Static assets (HTML, CSS)
/README.md       → Documentation file
/CONTRIBUTING.md → Guidelines for contributors
/package.json    → NPM configuration file

# Contributing to this project

Thanks for your interest! This is a small student project clone for a class task.

How you can help:
- **Testers / non-coders:** Open the site, try features, and post bugs in Issues.
- **Coders:** Look for issues labeled `good first issue`. Please open a PR with a clear description.
- **Translators:** Help translate README or UI strings.

Getting started:
1. Fork the repo and open a PR.
2. Write a short description of your change.
3. Keep changes small and focused.

Please keep license and attribution intact.

## License


---

# LICENSE (MIT) — copy & paste as `LICENSE`
```text
MIT License

Copyright (c) 2011-2024 Christopher Jeffrey
Copyright (c) 2025 Zhumanova Zhanel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

