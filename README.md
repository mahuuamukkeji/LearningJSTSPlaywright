# Learning JavaScript and Playwright

A hands-on, chapter-based repository for learning JavaScript fundamentals and progressing toward browser automation with Playwright. Examples cover core language concepts, data structures, asynchronous JavaScript, ES modules, and classes.

## Repository contents

- `01_chapter_JS_Basics/`: Hello World and basic math examples.
- `02_chapter_JS_Keywords_Identifiers/`: JavaScript engines, keywords, identifiers, identifier naming rules, and comments. See [Rules of Keywords and Identifiers](./02_chapter_JS_Keywords_Identifiers/Rules_of_Keywords_and_Identifiers.md) for a concise reference.
- `03_chapter_JS_Literals/`: JavaScript literals, numbers, `null`, `undefined`, and special numeric values such as `NaN` and `Infinity`.
- `04_chapter_JS_Operators/`: arithmetic, assignment, logical, and comparison operators, including examples of loose versus strict equality.
- `05_chapter_JS_Incre_Decr_Op/`: increment and decrement operators, with related operator practice including nullish coalescing.
- `06_chatper_if_else_statement_Condition/`: `if`, nested `if/else`, and multiple conditional branches.
- `07_chapter_switch/`: `switch` statements, grouped cases, and practice questions.
- `08_chapter_UserInput/`: terminal input using the Node.js `readline` module and `prompt-sync`, plus reading input from standard input.
- `09_chapter_Loops/`: introductory loops and `for` loop examples, including practice questions.
- `10_chapter_Loops_WHILE/`: `while` loops, loop counters, and stopping a loop with `break`.
- `11_chapter_Loops_DoWhile/`: `do...while` loops, comparison with `while`, and nested loops.
- `12_chapters_Arrays/`: creating, accessing, transforming, searching, sorting, slicing, and combining arrays.
- `13_chapter_Functions/`: function declarations, expressions, arrow functions, IIFEs, arguments, and return values.
- `14_chapter_Var_Let_Const_Hoisting_TDZ/`: variable declarations, hoisting, and the temporal dead zone.
- `15_chapter_Functions_Closure/`: closures and function scope.
- `16_chapter_String/`: strings and common string operations.
- `17_Objects_JS/`: JavaScript objects, copying, and reference behavior.
- `18_Multi_Dimensions_Array/`: multidimensional arrays and pattern examples.
- `19_Callback/`: callback functions, synchronous and asynchronous callbacks, and callback-based control flow.
- `20_Promise/`: creating and chaining promises, promise cleanup, and the `all`, `allSettled`, and `race` combinators.
- `21_Async_Await/`: using `async` and `await` to write promise-based code.
- `22_Export_Import/`: named and default exports, imports, and renaming imports.
- `23_Class_Objects/`: defining classes and creating objects.
- `24_Playwright/`: an introductory Playwright project with a sample configuration and browser tests.
- `tests/` and `playwright.config.ts`: root-level Playwright browser tests and configuration.

The identifier practice in `02_chapter_JS_Keywords_Identifiers/09_IQ.js` demonstrates valid identifier characters and Unicode identifiers, contrasts valid names with invalid syntax, and shows common naming conventions: camelCase, PascalCase, snake_case, and SCREAMING_SNAKE_CASE.

Examples are standalone JavaScript files intended for learning and experimentation. To run an example, use `node path/to/example.js` from the repository root. Install dependencies with `npm install` before running examples that use `prompt-sync`.

To run the root Playwright tests, install the browser binaries once and then run the test suite:

```sh
npx playwright install
npx playwright test
```

For `62_FS_readFile.js`, enter input and end it with Ctrl+D on macOS/Linux or Ctrl+Z, then Enter, on Windows.
