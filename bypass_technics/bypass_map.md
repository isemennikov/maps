---
title: bypass methods
markmap:
  colorFreezeLevel: 2
---

## WEB
### CSP
- [CRLF-inject](https://xakep.ru/2013/12/23/61798/)
- [Missconfig](https://timcore.ru/2024/11/01/50-bug-bounty-v-2-content-security-policy-csp-obhod-csp/)
### SOP
- [DNS Rebinding](https://github.com/mpgn/ByP-SOP)
- [Server-Side Proxy](https://www.oreilly.com/library/view/programming-social-applications/9781449302481/apas04s02.html)

## Related Projects

- [coc-markmap](https://github.com/gera2ld/coc-markmap) for Neovim
- [markmap-vscode](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode) for VSCode
- [eaf-markmap](https://github.com/emacs-eaf/eaf-markmap) for Emacs

## Features

Note that if blocks and lists appear at the same level, the lists will be ignored.

### Lists

- **strong** ~~del~~ *italic* ==highlight==
- `inline code`
- [x] checkbox
- Katex: $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$ <!-- markmap: fold -->
  - [More Katex Examples](#?d=gist:af76a4c245b302206b16aec503dbe07b:katex.md)
- Now we can wrap very very very very long text based on `maxWidth` option
- Ordered list
  1. item 1
  2. item 2

### Blocks

```js
console.log('hello, JavaScript')
```

| Products | Price |
|-|-|
| Apple | 4 |
| Banana | 2 |
