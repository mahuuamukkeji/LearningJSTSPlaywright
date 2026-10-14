# Learning JavaScript and Playwright

A hands-on repository for learning JavaScript fundamentals and building toward browser automation with Playwright. It contains small, chapter-based examples for practicing core language concepts.

## Repository contents

- `01_chapter_JS_Basics/`: Hello World and basic math examples.
- `02_chapter_JS_Keywords_Identifiers/`: JavaScript engines, keywords, identifiers, identifier naming rules, and comments. See [Rules of Keywords and Identifiers](./02_chapter_JS_Keywords_Identifiers/Rules_of_Keywords_and_Identifiers.md) for a concise reference.
- `03_chapter_JS_Literals/`: JavaScript literals, numbers, `null`, `undefined`, and special numeric values such as `NaN` and `Infinity`.
- `04_chapter_JS_Operators/`: arithmetic, assignment, logical, and comparison operators, including examples of loose versus strict equality.
- `05_chapter_JS_Incre_Decr_Op/`: increment and decrement operators, with related operator practice including nullish coalescing.
- `06_chatper_if_else_statement_Condition/`: `if`, nested `if/else`, and multiple conditional branches.
- `07_chapter_switch/`: `switch` statements, grouped cases, and practice questions.
- `08_chapter_UserInput/`: terminal input using the Node.js `readline` module and `prompt-sync`, plus reading input from standard input.

The identifier practice in `02_chapter_JS_Keywords_Identifiers/09_IQ.js` demonstrates valid identifier characters and Unicode identifiers, contrasts valid names with invalid syntax, and shows common naming conventions: camelCase, PascalCase, snake_case, and SCREAMING_SNAKE_CASE.

Examples are standalone JavaScript files intended for learning and experimentation. To run an example, use `node path/to/example.js` from the repository root. The `prompt-sync` example requires dependencies to be installed first with `npm install`. For `62_FS_readFile.js`, enter input and end it with Ctrl+D on macOS/Linux or Ctrl+Z, then Enter, on Windows.