## Project Description
Learn what ES6 is.
New features introduced in ES6.
The difference between a constant and a variable.
Block-scoped variables.
Arrow functions and function parameters default to them.
Rest and spread function parameters.
String templating in ES6.
Object creation and their properties in ES6.
Iterators and for-of loops.

## More Info
### Install Node 14
```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install Jest, Babel, and ESLint
```
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
```

**Find the configuration files `package.json`, `babel.config.js` and `.eslintrc.js` in the project directory. Run `npm install` when you have the `package.json`**


* **0. Basic list of objects** - Create a function named `getListStudents` that returns an array of objects. - `0-get_list_students.js`.
* **1. More mapping** - Create a function `getListStudentIds` that returns an array of ids from a list of object. - `1-multi_languages.js`.
* **2. Filter** - Create a function `getStudentsByLocation` that returns an array of objects who are located in a specific city. - `2-get_students_by_loc.js`.
* **3. Reduce** - Create a function `getStudentIdsSum` that returns the sum of all the student ids. - `3-get_ids_sum.js`.
* **4. Combine** - Create a function `updateStudentGradeByCity` that returns an array of students for a specific city with their new grade. - `4-update_grade_by_city.js`.
* **5. Typed Arrays** - Create a function named `createInt8TypedArray` that returns a new `ArrayBuffer` with an `Int8` value at a specific position. - `5-typed_arrays.js`.
* **6. Set data structure** - Create a function named `setFromArray` that returns a Set from an array. - `6-set.js`.
* **7. More set data structure** - Create a function named `hasValuesFromArray` that returns a boolean if all the elements in the array exist within the set. - `7-has_array_values.js`.
* **8. Clean set** - Create a function named `cleanSet` that returns a string of all the set values that start with a specific string (`startString`). - `8-clean_set.js`.
* **9. Map data structure** - Create a function named `groceriesList` that returns a map of groceries with the following items (name, quantity). - `9-groceries_list.js`.
* **10. More map data structure** - Create a function named `updateUniqueItems` that returns an updated map for all items with initial quantity at 1. - `10-update_uniq_items.js`.
* **11. Weak link data structure!** - When the number of queries is >= 5 throw an error with the message `Endpoint load is high`. - `100-weak.js`.

