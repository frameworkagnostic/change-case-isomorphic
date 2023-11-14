# change-case-isomorphic
isomorphic version of change-case

> Transform a string between camelCase, PascalCase, Capital Case, snake_case, param-case, CONSTANT_CASE and others.

### Install
`npm i --save @frameworkagnostic/change-case-isomorphic`

## Usage

```js
import { camelCase } from "@frameworkagnostic/change-case-isomorphic";
camelCase("TEST_VALUE"); //=> "testValue"
```

Included case functions:

| Method            | Result      |
| ----------------- | ----------- |
| `camelCase`       | `twoWords`  |
| `capitalCase`     | `Two Words` |
| `constantCase`    | `TWO_WORDS` |
| `dotCase`         | `two.words` |
| `kebabCase`       | `two-words` |
| `noCase`          | `two words` |
| `pascalCase`      | `TwoWords`  |
| `pascalSnakeCase` | `Two_Words` |
| `pathCase`        | `two/words` |
| `sentenceCase`    | `Two words` |
| `snakeCase`       | `two_words` |
| `trainCase`       | `Two-Words` |
