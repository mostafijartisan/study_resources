JavaScript doesn't have a built-in set of functions like PHP for handling arrays under a specific namespace (e.g., `array_`). However, JavaScript provides a comprehensive set of array methods that are part of the `Array` prototype, allowing you to manipulate arrays effectively.

Here’s a categorized list of JavaScript array methods grouped by purpose, similar to the PHP list:

---

### **1. Array Creation**

Methods to create new arrays.

- `Array.of()`
- `Array.from()`
- `Array()` (constructor)
- `new Array()`
- `Array.isArray()` (to check if a value is an array)

---

### **2. Traversing and Accessing**

Methods for iterating and accessing elements in arrays.

- `Array.prototype.at()`
- `Array.prototype.forEach()`
- `Array.prototype.keys()`
- `Array.prototype.values()`
- `Array.prototype.entries()`

---

### **3. Searching**

Methods for finding elements or indices in arrays.

- `Array.prototype.indexOf()`
- `Array.prototype.lastIndexOf()`
- `Array.prototype.includes()`
- `Array.prototype.find()`
- `Array.prototype.findIndex()`
- `Array.prototype.findLast()`
- `Array.prototype.findLastIndex()`

---

### **4. Transforming**

Methods to modify or transform arrays.

- `Array.prototype.map()`
- `Array.prototype.flat()`
- `Array.prototype.flatMap()`
- `Array.prototype.reverse()`
- `Array.prototype.sort()`

---

### **5. Filtering**

Methods to filter or exclude elements.

- `Array.prototype.filter()`
- `Array.prototype.every()`
- `Array.prototype.some()`

---

### **6. Reducing**

Methods for reducing or accumulating values from arrays.

- `Array.prototype.reduce()`
- `Array.prototype.reduceRight()`

---

### **7. Adding or Removing Elements**

Methods to modify array length or content.

- `Array.prototype.push()` (add at the end)
- `Array.prototype.pop()` (remove from the end)
- `Array.prototype.unshift()` (add at the start)
- `Array.prototype.shift()` (remove from the start)
- `Array.prototype.splice()`
- `Array.prototype.concat()`

---

### **8. Slicing and Splitting**

Methods to extract or divide arrays.

- `Array.prototype.slice()`
- `Array.prototype.splice()`
- `Array.prototype.copyWithin()`

---

### **9. Iteration Helpers**

Methods for iterating through elements.

- `Array.prototype.forEach()`
- `Array.prototype.map()`
- `Array.prototype.reduce()`

---

### **10. Utility**

Utility methods for arrays.

- `Array.isArray()` (checks if the value is an array)
- `Array.prototype.toString()` (convert to a string)
- `Array.prototype.join()`
- `Array.prototype.length`

---

### **11. Array Combination**

Methods to combine or merge arrays.

- `Array.prototype.concat()`
- `Array.prototype.flat()`

---

### **12. Array Set-Like Operations**

Methods to perform set-like operations.

- **Unique:** Use `new Set(array)` to get unique values.  
  Example:

  ```javascript
  const unique = [...new Set([1, 2, 2, 3])]; // [1, 2, 3]
  ```

- **Intersection or Difference:**  
  Custom implementations using `filter()` or `Set`.

---

### **How to List All Methods Programmatically**

You can programmatically obtain all methods of the `Array` prototype like this:

```javascript
const arrayMethods = Object.getOwnPropertyNames(Array.prototype).filter(
  (method) => typeof Array.prototype[method] === "function"
);
console.log(arrayMethods);
```

This will list all methods available on the `Array` prototype.

---

Would you like examples of any specific group or method?
