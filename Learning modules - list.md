
# TypeScript

### Type system fundamentals
- [TypeScript: Documentation - Everyday Types (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)
- [TypeScript: Documentation - Narrowing (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/narrowing.html)
	- `typeof` safeguard
	- `in` operator
	- `instanceof` operator
	- Type predicates (`parameterName is Type` style of function guards)
	- Assertion functions
	- `never` type uses
- [TypeScript: Documentation - More on Functions (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/functions.html)
	- How to write typesafe functions properly
	- Generic functions 
	- Optional parameters
	- **Rest parameters and arguments** (IMPORTANT) 
	- **Parameter destructuring** (IMPORTANT)
- [Interfaces and Types](https://www.typescriptlang.org/docs/handbook/2/objects.html)
	- [Cheat Sheets](https://www.typescriptlang.org/cheatsheets)
	- Property modifiers
	- Extending Types
	- Intersection Types
	- Interfaces vs Intersections
	- Generic object types
	- Array Types and Tuple Types 
- [Declaration Merging](https://www.typescriptlang.org/docs/handbook/declaration-merging.html)
	- Merging interfaces
	- Merging namespaces
- [Enums](https://www.typescriptlang.org/docs/handbook/enums.html)
- 
- Type manipulation
	- Generics [TypeScript: Documentation - Generics (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/generics.html)
	- `keyof` ([TypeScript: Documentation - Keyof Type Operator (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/keyof-types.html)) and `typeof` ([TypeScript: Documentation - Typeof Type Operator (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/typeof-types.html)) operators
	- Conditional types [TypeScript: Documentation - Conditional Types (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/conditional-types.html)
	- Mapped types [TypeScript: Documentation - Mapped Types (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/mapped-types.html)
- Module system
	- [Modules • JavaScript for impatient programmers (ES2022 edition) (exploringjs.com)](https://exploringjs.com/impatient-js/ch_modules.html#overview-syntax-of-ecmascript-modules)
	- [JavaScript modules - JavaScript | MDN (mozilla.org)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
	- [TypeScript: Documentation - Modules (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/2/modules.html) 
	  and 
	  [TypeScript: Documentation - Modules (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/modules.html)
		- ES Modules
		- `export` vs `export default` statements
		- `import` statements
		- Named imports (e.g. `import {foo as f} from './bar.ts'; // importing`)
		- Namespace imports (e.g. `import * as myMath from './lib/my-math.ts';`)
		- Default exports / imports
		- `export =` and `import = require()` [Reference](https://www.typescriptlang.org/docs/handbook/modules.html#export--and-import--require)
		- Dynamic module loading - [Dynamic module loading](https://www.typescriptlang.org/docs/handbook/modules.html#optional-module-loading-and-other-advanced-loading-scenarios)
		- Structuring of modules - [Structuring your modules]([TypeScript: Documentation - Modules (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/modules.html#guidance-for-structuring-modules))
		- Module resolution - [TypeScript: Documentation - Module Resolution (typescriptlang.org)](https://www.typescriptlang.org/docs/handbook/module-resolution.html)
- Declaration files
	- [Typical library structure](https://www.typescriptlang.org/docs/handbook/declaration-files/library-structures.html)
	- [Examples](https://www.typescriptlang.org/docs/handbook/declaration-files/by-example.html)
- Do's and Dont's
	- [NEVER USE GENERAL TYPES](https://www.typescriptlang.org/docs/handbook/declaration-files/by-example.html)
	- [NEVER USE `any`](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html#any)
	- [DON'T USE OPTIONAL PARAMETERS IN CALLBACKS](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html#optional-parameters-in-callbacks)
	- [DO PUT MORE GENERAL OVERLOADS AFTER MORE SPECIFIC ONES](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html#ordering)
	- [DO USE OPTIONAL PARAMETERS WHENEVER POSSIBLE](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html#use-optional-parameters)
	- [DO PREFER UNION TYPES WHENEVER POSSIBLE](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html#use-union-types)

# Advanced React

### Basics

[React Basics | Coursera](https://www.coursera.org/learn/react-basics?specialization=meta-front-end-developer)

### Advanced

[Advanced React | Coursera](https://www.coursera.org/learn/advanced-react?specialization=meta-front-end-developer)

UI/UX design principles (might be helpful)

[Principles of UX/UI Design | Coursera](https://www.coursera.org/learn/principles-of-ux-ui-design?specialization=meta-front-end-developer)

---
# Software Testing

### Testing libraries (Jest, RTL etc)

### Types of testing

[What is UI (GUI) Software testing? Types, Process, Tools & More! (zaptest.com)](https://www.zaptest.com/what-is-ui-software-testing-deep-dive-into-the-types-process-tools-implementation)

### Test Driven Development (TDD)

[Testing React Native with React-Query and Zustand | by Tarik | Level Up Coding (gitconnected.com)](https://levelup.gitconnected.com/testing-react-native-with-react-query-and-zustand-d957c2a40b73)

---
# Software Development: Best practices

### Clean code

### Software patterns (focused on React applications)

Kent Beck book "Implementation patterns"

Gang of 4 book

### DevOps: Version Control, CI/CD, SDLC

---
