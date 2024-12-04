PHP provides a wide variety of array functions, which can be categorized based on their purpose. Here's a categorized list:

---

### **Array Creation and Initialization**

- `array()` - Creates an array.
- `range()` - Creates an array containing a range of elements.
- `array_fill()` - Fills an array with values.
- `array_fill_keys()` - Fills an array with values, specifying keys.
- `array_pad()` - Pads an array to a specified length with a value.

---

### **Array Manipulation**

- **Adding Elements:**

  - `array_push()` - Pushes one or more elements to the end of an array.
  - `array_unshift()` - Prepends one or more elements to the beginning of an array.

- **Removing Elements:**

  - `array_pop()` - Pops the last element off an array.
  - `array_shift()` - Shifts the first element off an array.

- **Modifying Keys/Values:**
  - `array_replace()` - Replaces the values of the first array with values from subsequent arrays.
  - `array_replace_recursive()` - Recursive version of `array_replace()`.

---

### **Array Sorting**

- **By Values:**

  - `sort()` - Sorts an array in ascending order.
  - `rsort()` - Sorts an array in descending order.
  - `asort()` - Sorts an array in ascending order while maintaining key association.
  - `arsort()` - Sorts an array in descending order while maintaining key association.

- **By Keys:**

  - `ksort()` - Sorts an array by key in ascending order.
  - `krsort()` - Sorts an array by key in descending order.

- **Custom Sorting:**
  - `usort()` - Sorts an array by values using a user-defined comparison function.
  - `uksort()` - Sorts an array by keys using a user-defined comparison function.
  - `uasort()` - Sorts an array by values with a user-defined comparison function, maintaining key association.
- **others:**
  - `array_multisort()`

---

### **Array Keys and Values**

Functions to get, set, or manipulate keys and values.

- `array_keys()` - Returns all the keys of an array.
- `array_values()` - Returns all the values of an array.
- `array_flip()`

---

### **Array Counting**

Functions to count elements in arrays.

- `count()` - Counts the number of elements in an array.
- `sizeof()` - Alias of `count()`.
- `array_count_values()` - Counts the occurrences of each distinct value in an array

---

### **Array Inspection**

- `is_array()` - Checks if a variable is an array.
- `array_key_exists()` - Checks if a key exists in an array.
- `in_array()` - Checks if a value exists in an array.

---

### **Array Filtering**

- `array_filter()` - Filters elements of an array using a callback function.

---

### **Array Searching**

- `array_search()` - Searches for a value in an array and returns its key.
- `array_keys()` - Searches and returns keys for a given value.
- `array_key_exists()` (alias: `key_exists()`)

---

### **Array Mapping and Transformation**

- `array_map()` - Applies a callback function to the elements of an array.
- `array_walk()` - Applies a callback function to the elements of an array, including their keys.
- `array_walk_recursive()` - Recursively applies a callback function to elements of an array.
- `array_reduce()` - Iteratively reduces an array to a single value using a callback function.

---

### **Array Merging and Combining**

- `array_merge()` - Merges one or more arrays.
- `array_merge_recursive()` - Recursively merges arrays.
- `array_combine()` - Combines two arrays: one for keys, the other for values.

---

### **Array Chunking and Splitting**

- `array_chunk()` - Splits an array into chunks.
- `array_slice()` - Extracts a portion of an array.
- `array_splice()` - Removes and replaces a portion of an array.

---

### **Array Flipping and Reversing**

- `array_reverse()` - Reverses the order of elements in an array.
- `array_flip()` - Exchanges all keys with their associated values.

---

### **Array Intersecting and Differencing**

- **Intersection:**

  - `array_intersect()` - Computes the intersection of arrays by values.
  - `array_intersect_key()` - Computes the intersection of arrays by keys.
  - `array_intersect_assoc()` - Computes the intersection of arrays by keys and values.

- **Difference:**
  - `array_diff()` - Computes the difference of arrays by values.
  - `array_diff_key()` - Computes the difference of arrays by keys.
  - `array_diff_assoc()` - Computes the difference of arrays by keys and values.

---

### **Array Utilities**

- `array_unique()` - Removes duplicate values from an array.
- `array_column()` - Returns the values from a single column in a multi-dimensional array.
- `array_rand()` - Picks one or more random keys from an array.
- `shuffle()` - Shuffles the elements of an array.

---

### **Array Traversing and Access**

Functions used to iterate or access array elements.

- `current()`
- `next()`
- `prev()`
- `reset()`
- `end()`
- `key()`
- `each()` _(deprecated since PHP 7.2)_

---

### **Array Serialization**

Functions for serializing or deserializing arrays.

- `serialize()`
- `unserialize()`
- `json_encode()`
- `json_decode()`

---

### **Support callback**

Here is a list, who support callback functions

- `array_all()` - Checks if all array elements satisfy a callback function
- `array_any()` - Checks if at least one array element satisfies a callback function
- `array_filter()`
- `array_map()`
- `array_reduce()`
- `array_walk()`
- `array_walk_recursive()`
- `usort()`
- `uasort()`
- `uksort()`
- `array_replace_recursive()`
- `array_intersect_ukey()`
- `array_diff_uassoc()`
- `array_udiff()`
- `array_udiff_assoc()`
- `array_udiff_uassoc()`
- `array_uintersect()`
- `array_uintersect_assoc()`
- `array_uintersect_uassoc()`

---

Let me know if you'd like an explanation of any specific function!
