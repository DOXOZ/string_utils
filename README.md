# String Utilities

A TypeScript library providing a collection of string manipulation utilities with full type safety.

## Features

- Capitalize strings
- Trim whitespace
- Repeat strings
- Convert to snake_case
- Convert to upper/lower case
- Check if string is empty
- Reverse strings
- Truncate strings
- Remove spaces
- Count words
- Check string start/end
- Replace all occurrences

## Installation

```bash
npm install
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm start` - Build and preview production build

## Usage

```typescript
import { stringUtils } from './utils';

// Examples
stringUtils.capitalize('hello');  // "Hello"
stringUtils.trim('  hello  ');    // "hello"
stringUtils.repeat('abc', 3);     // "abcabcabc"
stringUtils.toSnakeCase('Hello World');  // "hello_world"
// ... and more!
```

## Type Safety

All utilities are fully typed using TypeScript, providing excellent IDE support and compile-time type checking.

## Project Structure

- `src/types.ts` - Type definitions and interfaces
- `src/utils.ts` - Utility functions implementation
- `src/main.ts` - Usage examples

## License

MIT
#   s t r i n g _ u t i l s  
 