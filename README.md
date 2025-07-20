# Browser Exploration

Honestly, I believe that the most powerful software is the browser. It’s a fascinating piece of technology with millions of things to learn. I truly enjoy researching these topics, and here I’ve gathered some useful links that are important and will help you understand browsers better.

A curated, step-by-step roadmap for understanding browser internals, the V8 JavaScript engine, JavaScript compilation, and advanced exploitation topics. **Follow the links in order for the best learning experience:** the first links are beginner-friendly, while the last are highly advanced. Also, the last step is to implement a simple browser, and this is so exciting. Enjoy it!

If you find this project helpful, please consider giving it a ⭐ star! Your support means a lot and helps others discover these resources.

---

## 📚 Learning Path (Follow in Order)

### 🟢 Browser Internals & Foundations
1) [Inside look at modern web browsers (Part 1)](https://developer.chrome.com/blog/inside-browser-part1)
2) [Inside look at modern web browsers (Part 2)](https://developer.chrome.com/blog/inside-browser-part2)
3) [Inside look at modern web browsers (Part 3)](https://developer.chrome.com/blog/inside-browser-part3)
4) [Inside look at modern web browsers (Part 4)](https://developer.chrome.com/blog/inside-browser-part4)

### 🟡 V8 Engine Basics & JavaScript Fundamentals
5) [Inside the V8 Engine (Plain English, ~5 min read)](https://javascript.plainenglish.io/inside-the-v8-engine-3795e56ead4b)
6) [YouTube: Shapes and Caches Inside the Engine](https://youtu.be/5nmpokoRaZI?si=EwuZYp-6S_Vgb_Cb)

[![Shapes and Caches Inside the Engine](https://img.youtube.com/vi/5nmpokoRaZI/0.jpg)](https://youtu.be/5nmpokoRaZI?si=EwuZYp-6S_Vgb_Cb)

7) [YouTube: Check the Assembly Code for JS Code](https://youtu.be/p-iiEDtpy6I?si=fnYlhPP90ELejf_s)

[![Check the Assembly Code for JS Code](https://img.youtube.com/vi/p-iiEDtpy6I/0.jpg)](https://youtu.be/p-iiEDtpy6I?si=fnYlhPP90ELejf_s)

8) [JavaScript Engine Fundamentals: Optimizing Prototypes](https://benediktmeurer.de/2018/08/16/javascript-engine-fundamentals-optimizing-prototypes/)
9) [YouTube: BlinkOn - Browser Internals](https://www.youtube.com/watch?v=r5OWCtuKiAk&ab_channel=BlinkOn)

[![BlinkOn - Browser Internals](https://img.youtube.com/vi/r5OWCtuKiAk/0.jpg)](https://www.youtube.com/watch?v=r5OWCtuKiAk&ab_channel=BlinkOn)

### 🟠 Parsing, Code Generation, and Engine Internals
10) [Inside JavaScript Engines Part 1: Parsing](https://medium.com/@yanguly/inside-javascript-engines-part-1-parsing-c519d75833d7)
11) [Inside JavaScript Engines Part 2: Code Generation and Basic Optimizations](https://medium.com/@yanguly/inside-javascript-engines-part-2-code-generation-and-basic-optimizations-952bed02db62)
12) [Chrome Browser Exploitation Part 1](https://jhalon.github.io/chrome-browser-exploitation-1/)
13) [V8 Blog: Scanner](https://v8.dev/blog/scanner)
14) [V8 Blog: Preparser](https://v8.dev/blog/preparser)
15) [V8 Blog: Sparkplug](https://v8.dev/blog/sparkplug)

16) [Sparkplug: V8 Baseline JavaScript Compiler](https://medium.com/@yanguly/sparkplug-v8-baseline-javascript-compiler-758a7bc96e84)
17) [Chrome Browser Exploitation Part 2](https://jhalon.github.io/chrome-browser-exploitation-2/)
18) [Chrome Browser Exploitation Part 3](https://jhalon.github.io/chrome-browser-exploitation-3/)

### 🔴 Advanced V8, Optimization, and Exploitation
19) [V8 Blog: React Cliff](https://v8.dev/blog/react-cliff)
20) [V8 Blog: V8 Lite](https://v8.dev/blog/v8-lite)
21) [YouTube: ProgrammingConf - V8 and JS Engines](https://www.youtube.com/watch?v=2PhKvhxYFws&ab_channel=programmingconf)

[![ProgrammingConf - V8 and JS Engines](https://img.youtube.com/vi/2PhKvhxYFws/0.jpg)](https://www.youtube.com/watch?v=2PhKvhxYFws&ab_channel=programmingconf)

22) [Ignition: V8 Interpreter (docs)](https://docs.google.com/document/d/11T2CRex9hXxoJwbYqVQ32yIPMh0uouUZLdyrtmMoL44/edit?tab=t.0#heading=h.6jz9dj3bnr8t)
23) [JavaScript Bytecode: V8 Ignition Instructions](https://www.alibabacloud.com/blog/javascript-bytecode-v8-ignition-instructions_599188?utm_source=chatgpt.com)
24) [Browser Engineering (Book)](https://browser.engineering/)

---

## 💻 Source Codes

### 1. V8 GitHub Repository (v8/v8)
URL: https://github.com/v8/v8

What it is:
This is the official standalone repository for the V8 JavaScript engine, maintained by the V8 team.

What's included:
- All core components of the JavaScript engine:
  - Parser
  - Ignition (interpreter)
  - TurboFan (JIT compiler)
  - Garbage collector
  - Snapshot system
  - Bytecode interpreter
  - Builtins, ICs (inline caches)
- It’s fully independent and can be embedded in any C++ application (Node.js does this).

Use cases:
- Building or embedding the JS engine into other environments (like Node.js).
- Exploring engine internals.
- Lightweight, JS-only runtime experiments.

### 2. Chromium Source Code
URL: https://chromium.googlesource.com/chromium/src/

What it is:
This is the entire Chromium browser codebase, of which V8 is only one part.

What's included:
- V8 (integration)
- Blink rendering engine (HTML, CSS)
- Networking stack (HTTP)
- UI (tabs, menus, WebUI)
- Browser process / multiprocess architecture
- DevTools frontend
- PDF renderer, autofill, etc.
---

## 🤝 Contributing

Contributions are welcome! If you have more great links, corrections, or improvements, feel free to open an issue or submit a pull request. Let's make this resource even better together!
