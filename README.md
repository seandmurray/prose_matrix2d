# Prose/Matrix 2D

Copyright (c) 2019 Seán D. Murray
SEE MIT LICENSE FILE

A 2D matrix Utility. Make writing node easier, prettier and less error prone. Writes and reads more like prose

## Usage

```javascript
const matrix = require('prose_matrix');

// Create a new matrix with 15 coordinates all set to 1
const matrix1 = new Matrix(3, 5, 1);
const matrix2 = new Matrix(3, 5, 1);

// Deep equals if matrix and all values are equal.
// returns true/false
matrix1.equal(matrix2);

// Set x y coordinates to value 2.
matrix1.set(0,1,2);

// Get the values at coordinates 2,4.
matrix1.get(2,4);

// Set all values to 3
matrix1.setAll(3);

// Get a *copy* of the internal 2D matrix in for of array of array.
matrix1.raw();
```
