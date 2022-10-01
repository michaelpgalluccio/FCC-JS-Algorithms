# freeCodeCamp - JavaScript Algorithms
## Notes
- JavaScript provides eight different data types
     - undefined
     - null
     - boolean
     - string
     - symbol
     - bigint
     - number
     - and object
- Variables are declared with syntax
     ```
        var varName;                      (cannot contain spaces or numbers)
     ```
   - Store a value with the variable after declaring
     ```
        var varName;
        varName = 5;
     ```
   - Can initialize and declare in one line
     ```
        var varName = 5;
        var varName = "my variable";        (strings in double quotes)
     ```   
   - Variables are all initially declared as undefined, math operations will return NaN 
   - Variables values declared using var can be overwritten with another declaration.
   - Variables values declared using let will provide an error when overwritten with another 3. declaration.
   - Variables declared using const will be read-only and not mutable when a value is reassigned.
   - Operating on variables.
     - You can perform operations in the declaration of a variable (+,-,*,/, %) for integers and floats.
     - Incrementing uses ++ and decrementing uses --.
     - In variable augmentation you can use +=, -=, *=, /= to combine a reassignment and modification.
     - For enclosing quotes in a string use the following
          ```
          const sampleStr = "Alan said \"Hello\" to her"          (must be before quotes)
          ```
          - You can also use '' or "" in combination. This can be problematic if you need to use the outer quote type inside the string.
          - Note these other escape:
               - \'	single quote
               - \"	double quote
               - \\	backslash
               - \n	newline
               - \r	carriage return
               - \t	tab
               - \b	word boundary
               - \f	form feed
          - The + operator for strings concatenates.
          - To determine hte length of a string use .length
          - Bracket [] notation returns characters starting with 0.
               - Use string[string.length-1] for finiding the last character.
          - String values are immutable. You can change a string by reassigning but not change characters.
- Arrays are lists of values.
     - Arrays are types of variables that can contain multiple datatypes.
     - You can make multi-dimensional arrays (lists of lists).
          - Bracket [] notation is for index input and returns the value at that index starting at [0]
          - Each array in an array of arrays does not need to be the same dimensions, they can even have their own dimensionality.
          - push() can be used to append a value to an array. Whatever you push can be multidimensional and doesn't have to match the receiving array.
          - pop() can be used to remove the last value from an array.
          - shift() can be used to remove the first value from an array.
          - unshift() can be used to append a value to the beginning of the array. Whatever you unshift can be multidimensional and doesnt have to match the receing array.
                 

## General Recommendations
- JavaScript is CASE SENSITIVE. Recommendation is to use camelCase for variables.

