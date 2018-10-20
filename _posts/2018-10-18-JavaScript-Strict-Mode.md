---
title: JavaScript - Strict Mode ‘use strict’
image: /assets/img/strict-mode.png
---

Strict Mode is a new feature in ECMAScript 5 that allows you to place a program, or a function, in a “strict” operating context. This strict context prevents certain actions from being taken and throws more exceptions. The statement “use strict”; instructs the browser to use the Strict mode, which is a reduced and safer feature set of JavaScript.

#### Benefits of using ‘use strict’ 
Strict mode makes several changes to normal JavaScript semantics.

- Strict mode eliminates some JavaScript silent errors by changing them to throw errors.
- Strict mode fixes mistakes that make it difficult for JavaScript engines to perform optimizations: strict mode code can sometimes be made to run faster than identical code that’s not strict mode.
- Strict mode prohibits some syntax likely to be defined in future versions of ECMAScript.
- It prevents, or throws errors, when relatively “unsafe” actions are taken (such as gaining access to the global object).
- It disables features that are confusing or poorly thought out.
- Strict mode makes it easier to write “secure” JavaScript.

#### How to use strict mode
Strict mode can be used in two ways – used in global scope for the entire script and can be applied to individual functions. Strict mode doesn’t work with block statements enclosed in {} braces.

```sh
// Whole-script strict mode syntax
'use strict';
var v = "strict mode script!";
```

```sh
function strict() {

  // Function-level strict mode syntax
  'use strict';

  function nested() { return 'Javascript on GeeksforGeeks'; }

  return "strict mode function!  " + nested();
}
function notStrict() { return "non strict function"; }
```
