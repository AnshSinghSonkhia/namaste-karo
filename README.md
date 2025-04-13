# Namaste Karo

A simple Node.js package to greet with "Namaste".

## Installation

```bash
npm install namaste-karo
```

## Usage

```javascript
const { bolo, boloWithName } = require('namaste-karo');

// Greet with a simple "Namaste"
bolo(); // Output: Namaste

// Greet with a personalized message
boloWithName('Ansh'); // Output: Namaste, Ansh
```

## Functions

### `bolo()`
Logs "Namaste" to the console.

### `boloWithName(name)`
Logs a personalized greeting to the console.

- **Parameters**:
    - `name` (string): The name to include in the greeting.

## License

This project is licensed under the MIT License.