# is-true-ai

A lightweight utility to detect if a string was likely generated by AI.

## Installation

```bash
npm install is-true-ai
```

## Environment Variables

Create a `.env` file and add your OpenAI API key:

```bash
OPENAI_API_KEY=your_openai_api_key
```

## Usage

```javascript
const isTrueAI = require('is-true-ai');

console.log(isTrueAI('Hello, world!')); // true
```
