# 📘 TypeScript Roadmap

A complete roadmap to learn **TypeScript** step by step — from basics to advanced concepts, including tooling, frameworks, and projects.

---

## 📌 1. Prerequisites
Before diving into TypeScript, make sure you know:
- ✅ JavaScript (ES6+ features like `let`, `const`, arrow functions, classes, async/await)
- ✅ Basic OOP (encapsulation, inheritance, polymorphism)
- ✅ Node.js & npm/yarn

---

## 📌 2. TypeScript Basics
- Install & setup (`npm install -g typescript`, `tsc --init`)
- Core Types: `string`, `number`, `boolean`, `any`, `unknown`, `never`
- Arrays & Tuples: `number[]`, `[string, number]`
- Enums
- Type inference
- Type assertions (`as`, `<Type>`)

---

## 📌 3. Functions
- Function parameter types
- Optional & default parameters
- Rest parameters
- Return types
- Function overloading

---

## 📌 4. Objects & Interfaces
- Object types
- Interfaces (`interface`)
- Type aliases (`type`)
- Extending interfaces
- Readonly & optional properties
- Intersection types (`&`)

---

## 📌 5. Classes & OOP
- Class properties & methods
- Access modifiers: `public`, `private`, `protected`
- `readonly` properties
- Getters & setters
- Inheritance & `super`
- Abstract classes
- Implementing interfaces

---

## 📌 6. Advanced Type System
- Union & intersection types
- Literal types
- Type narrowing
- Type guards (`typeof`, `instanceof`, custom guards)
- Discriminated unions
- Utility types (`Partial`, `Pick`, `Omit`, `Record`, etc.)

---

## 📌 7. Generics
- Generic functions
- Generic interfaces & classes
- Constraints (`extends`)
- Default types
- `keyof` & lookup types
- Mapped types

---

## 📌 8. Modules & Namespaces
- ES Modules (`import` / `export`)
- Namespaces
- Ambient declarations (`.d.ts`)

---

## 📌 9. Tooling & Config
- `tsconfig.json` (compiler options)
- Strict mode (`strictNullChecks`, `noImplicitAny`)
- ESLint & Prettier with TypeScript
- Debugging TypeScript
- Building with `tsc`
- Bundlers (Vite, Webpack, ESBuild)

---

## 📌 10. TypeScript with Frameworks
### React + TypeScript
- Typing props & state
- Typing hooks (`useState`, `useReducer`, `useRef`)
- Context API with TS

### Node.js + TypeScript
- Express typing
- Middleware typing
- Request/Response types

### Others
- Next.js
- NestJS

---

## 📌 11. Advanced Concepts
- Declaration merging
- Module augmentation
- Conditional types (`T extends U ? X : Y`)
- `infer` keyword
- Template literal types
- Recursive types
- Advanced utility types
- Decorators (experimental)

---

## 📌 12. Testing with TypeScript
- Jest + TypeScript
- Typing mocks
- E2E testing (Cypress / Playwright)

---

## 📌 13. Best Practices
- Prefer `unknown` over `any`
- Avoid excessive type assertions
- Use interfaces for contracts, type aliases for unions
- Keep `tsconfig.json` strict
- Organize types in a `types/` folder

---

## 📌 14. Projects to Build
1. 📝 Todo App (React + TS)  
2. 🌍 REST API (Express + TS)  
3. 🔐 Auth System (JWT + TS)  
4. 📊 Dashboard (React + TS + charts)  
5. 🎮 Game (TypeScript + Canvas)  
6. ⚡ CLI Tool (Node.js + TS)  

---

🔥 Happy Learning! Build, break, and master TypeScript 🚀
