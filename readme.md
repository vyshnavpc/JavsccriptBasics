# Javascript Basics
```javascript is a dynamic type language,don't need to specify type of any variable,javascript is an object oriented programing language everything is an object in javascript```
* datatypes
  * primitive  
    * string 
    * number
    * boolean 
    * undefined 
    * null
  * non-primitive 
    * object 
    * array 
    * regexp
* operataors
    * arithmetic operators    
        * addition(+)
        * Subtraction(-)
        * Multiplication(x)
        * Division(/)
        * Modulus/Remainder(%)
        * Increment(++)
        * Decrement(--)
    * Comparison operators
        * Is equal to(==)
        * Identical (equal and of same data type)(===)
        * Not equal to(!=)
        * Not Identical(!==)
        * Greater than(>)
        * Greater than or equal to(>=)
        * Less than(<)
        * Less than or equal to(<=)
    * Bitwise operators
        * And(&)
        * OR(|)
        * XOR(^)
        * NOT(~)
        * Left Shift(<<)
        * Right Shift(>>)
        * Right Shift with Zero(>>>)
    * Logical Operators
        * Logical AND(&&)
        * Logical OR(||)
        * Logical Not(!)
    * Assignment Operators
        * Assign(=)
        * Add and assign(+=)
        * Subtract and assign(-=)
        * Multiply and assign(*=)
        * Divide and assign(/=)
        * Modulus and assign(%=)
    * Special Operators
        * (?:) -	Conditional Operator returns value based on the condition. It is like if-else.
        * , -	Comma Operator allows multiple expressions to be evaluated as single statement.
        * delete -	Delete Operator deletes a property from the object.
        * in -	In Operator checks if object has the given property
        * instanceof -	checks if the object is an instance of given type
        * new -	creates an instance (object)
        * typeof -	checks the type of object.
        * void -	it discards the expression's return value.
        * yield -	checks what is returned in a generator by the generator's iterator.

* javascript functions methods
    * apply() -	It is used to call a function contains this value and a single array of arguments.
    * bind() -	It is used to create a new function.
    * call() -	It is used to call a function contains this value and an argument list.
    * toString() -	It returns the result in a form of a string.

* javascript Objects
    * JavaScript Object by object literal
        ```
        eg : object={property1:value1,property2:value2.....propertyN:valueN}
        ```
    *  By creating instance of Object
        ```
        var objectname=new Object();  
        ```
    * By using an Object constructor
        ```
        function emp(id,name,salary){  
            this.id=id;  
            this.name=name;  
            this.salary=salary;  
        }  
        e=new emp(103,"Vimal Jaiswal",30000);  
        ```
* Js object methods
     | S.No |  	Methods	 | Description | 
     |----|-----|-----|
     | 1	 |  Object.assign() | 	This method is used to copy enumerable and own properties from a source object to a target object | 
     | 2	 |  Object.create() | 	This method is used to create a new object with the specified prototype object and properties. | 
     | 3	 |  Object.defineProperty() | 	This method is used to describe some behavioral attributes of the property. | 
     | 4	 |  Object.defineProperties()	 | This method is used to create or configure multiple object properties. | 
     | 5	 |  Object.entries()	 | This method returns an array with arrays of the key, value pairs. | 
     | 6	 |  Object.freeze()	 | This method prevents existing properties from being removed. | 
     | 7	 |  Object.getOwnPropertyDescriptor()	 | This method returns a property descriptor for the specified property of the specified object. | 
     | 8	 |  Object.getOwnPropertyDescriptors() | 	This method returns all own property descriptors of a given object. | 
     | 9	 |  Object.getOwnPropertyNames() | 	This method returns an array of all properties (enumerable or not) found. | 
     | 10	 |  Object.getOwnPropertySymbols() | 	This method returns an array of all own symbol key properties. | 
     | 11	 |  Object.getPrototypeOf()	 | This method returns the prototype of the specified object. | 
     | 12	 |  Object.is()	 | This method determines whether two values are the same value. | 
     | 13	 |  Object.isExtensible()	 | This method determines if an object is extensible | 
     | 14	 |  Object.isFrozen()	 | This method determines if an object was frozen. | 
     | 15	 |  Object.isSealed()	 | This method determines if an object is sealed. | 
     | 16	 |  Object.keys()	 | This method returns an array of a given object's own property names. | 
     | 17	 |  Object.preventExtensions() | 	This method is used to prevent any extensions of an object. | 
     | 18	 |  Object.seal()	 | This method prevents new properties from being added and marks all existing properties as non-configurable. | 
     | 19	 |  Object.setPrototypeOf() | 	This method sets the prototype of a specified object to another object. | 
     | 20	 |  Object.values()	 | This method returns an array of values. | 
* JavaScript Array Methods

    Methods|	Description
    ---|---
    concat()|	It returns a new array object that contains two or more merged arrays.
    copywithin()|	It copies the part of the given array with its own elements and returns the modified array.
    entries()	|It creates an iterator object and a loop that iterates over each key/value pair.
    every()	|It determines whether all the elements of an array are satisfying the provided function conditions.
    flat()	|It creates a new array carrying sub-array elements concatenated recursively till the specified depth.
    flatMap()	|It maps all array elements via mapping function, then flattens the result into a new array.
    fill()|	It fills elements into an array with static values.
    from()	|It creates a new array carrying the exact copy of another array element.
    filter()|	It returns the new array containing the elements that pass the provided function conditions.
    find()	|It returns the value of the first element in the given array that satisfies the specified condition.
    findIndex()|	It returns the index value of the first element in the given array that satisfies the specified condition.
    forEach()|	It invokes the provided function once for each element of an array.
    includes()|	It checks whether the given array contains the specified element.
    indexOf()|	It searches the specified element in the given array and returns the index of the first match.
    isArray()|	It tests if the passed value ia an array.
    join()|	It joins the elements of an array as a string.
    keys()	|It creates an iterator object that contains only the keys of the array, then loops through these keys.
    lastIndexOf()|	It searches the specified element in the given array and returns the index of the last match.
    map()|	It calls the specified function for every array element and returns the new array
    of()|	It creates a new array from a variable number of arguments, holding any type of argument.
    pop()|	It removes and returns the last element of an array.
    push()	|It adds one or more elements to the end of an array.
    reverse()|	It reverses the elements of given array.
    reduce(function, initial)|	It executes a provided function for each value from left to right and reduces the array to a single value.
    reduceRight()	|It executes a provided function for each value from right to left and reduces the array to a single value.
    some()	|It determines if any element of the array passes the test of the implemented function.
    shift()|	It removes and returns the first element of an array.
    slice()|	It returns a new array containing the copy of the part of the given array.
    sort()|	It returns the element of the given array in a sorted order.
    splice()|	It add/remove elements to/from the given array.
    toLocaleString()|	It returns a string containing all the elements of a specified array.
    toString()|	It converts the elements of a specified array into string form, without affecting the original array.
    unshift()|	It adds one or more elements in the beginning of the given array.
    values()|	It creates a new iterator object carrying values for each index in the array.

* JavaScript String Methods

    Methods	|Description
    ---|---
    charAt()|	It provides the char value present at the specified index.
    charCodeAt()|	It provides the Unicode value of a character present at the specified index.
    concat()|	It provides a combination of two or more strings.
    indexOf()|	It provides the position of a char value present in the given string.
    lastIndexOf()|	It provides the position of a char value present in the given string by searching a character from the last position.
    search()|	It searches a specified regular expression in a given string and returns its position if a match occurs.
    match()|	It searches a specified regular expression in a given string and returns that regular expression if a match occurs.
    replace()|	It replaces a given string with the specified replacement.
    substr()|	It is used to fetch the part of the given string on the basis of the specified starting position and length.
    substring()|	It is used to fetch the part of the given string on the basis of the specified index.
    slice()	|It is used to fetch the part of the given string. It allows us to assign positive as well negative index.
    toLowerCase()|	It converts the given string into lowercase letter.
    toLocaleLowerCase()|	It converts the given string into lowercase letter on the basis of host?s current locale.
    toUpperCase()	|It converts the given string into uppercase letter.
    toLocaleUpperCase()|	It converts the given string into uppercase letter on the basis of host?s current locale.
    toString()|	It provides a string representing the particular object.
    valueOf()|	It provides the primitive value of string object.
    split()	|It splits a string into substring array, then returns that newly created array.
    trim()	|It trims the white space from the left and right side of the string.

* JavaScript Date Methods

    Methods |	Description
    ---|---
    getDate() |	It returns the integer value between 1 and 31 that represents the day for the specified date on the basis of local time.
    getDay() |	It returns the integer value between 0 and 6 that represents the day of the week on the basis of local time.
    getFullYears()	 |It returns the integer value that represents the year on the basis of local time.
    getHours() |	It returns the integer value between 0 and 23 that represents the hours on the basis of local time.
    getMilliseconds() |	It returns the integer value between 0 and 999 that represents the milliseconds on the basis of local time.
    getMinutes() |	It returns the integer value between 0 and 59 that represents the minutes on the basis of local time.
    getMonth()	 |It returns the integer value between 0 and 11 that represents the month on the basis of local time.
    getSeconds() |	It returns the integer value between 0 and 60 that represents the seconds on the basis of local time.
    getUTCDate() |	It returns the integer value between 1 and 31 that represents the day for the specified date on the basis of universal time.
    getUTCDay() |	It returns the integer value between 0 and 6 that represents the day of the week on the basis of universal time.
    getUTCFullYears() |	It returns the integer value that represents the year on the basis of universal time.
    getUTCHours() |	It returns the integer value between 0 and 23 that represents the hours on the basis of universal time.
    getUTCMinutes() |	It returns the integer value between 0 and 59 that represents the minutes on the basis of universal time.
    getUTCMonth() |	It returns the integer value between 0 and 11 that represents the month on the basis of universal time.
    getUTCSeconds() |	It returns the integer value between 0 and 60 that represents the seconds on the basis of universal time.
    setDate() |	It sets the day value for the specified date on the basis of local time.
    setDay() |	It sets the particular day of the week on the basis of local time.
    setFullYears() |	It sets the year value for the specified date on the basis of local time.
    setHours() |	It sets the hour value for the specified date on the basis of local time.
    setMilliseconds() |	It sets the millisecond value for the specified date on the basis of local time.
    setMinutes() |	It sets the minute value for the specified date on the basis of local time.
    setMonth() |	It sets the month value for the specified date on the basis of local time.
    setSeconds() |	It sets the second value for the specified date on the basis of local time.
    setUTCDate() |	It sets the day value for the specified date on the basis of universal time.
    setUTCDay() |	It sets the particular day of the week on the basis of universal time.
    setUTCFullYears() |	It sets the year value for the specified date on the basis of universal time.
    setUTCHours() |	It sets the hour value for the specified date on the basis of universal time.
    setUTCMilliseconds() |	It sets the millisecond value for the specified date on the basis of universal time.
    setUTCMinutes() |	It sets the minute value for the specified date on the basis of universal time.
    setUTCMonth() |	It sets the month value for the specified date on the basis of universal time.
    setUTCSeconds() |	It sets the second value for the specified date on the basis of universal time.
    toDateString() |	It returns the date portion of a Date object.
    toISOString() |	It returns the date in the form ISO format string.
    toJSON() |	It returns a string representing the Date object. It also serializes the Date object during JSON serialization.
    toString() |	It returns the date in the form of string.
    toTimeString() |	It returns the time portion of a Date object.
    toUTCString() |	It converts the specified date in the form of string using UTC time zone.
    valueOf() |	It returns the primitive value of a Date object.

* JavaScript Math

    ```The JavaScript math object provides several constants and methods to perform mathematical operation. Unlike date object, it doesn't have constructors.```



    * JavaScript Math Methods
Let's see the list of JavaScript Math methods with description.

        Methods| 	Description
        ---|---
        abs()| 	It returns the absolute value of the given number.
        acos()	| It returns the arccosine of the given number in radians.
        asin()	| It returns the arcsine of the given number in radians.
        atan()	| It returns the arc-tangent of the given number in radians.
        cbrt()	| It returns the cube root of the given number.
        ceil()	| It returns a smallest integer value, greater than or equal to the given number.
        cos()	| It returns the cosine of the given number.
        cosh()	| It returns the hyperbolic cosine of the given number.
        exp()	| It returns the exponential form of the given number.
        floor()	| It returns largest integer value, lower than or equal to the given number.
        hypot()	| It returns square root of sum of the squares of given numbers.
        log()	| It returns natural logarithm of a number.
        max()	| It returns maximum value of the given numbers.
        min()	| It returns minimum value of the given numbers.
        pow()	| It returns value of base to the power of exponent.
        random()	| It returns random number between 0 (inclusive) and 1 (exclusive).
        round()	| It returns closest integer value of the given number.
        sign()	| It returns the sign of the given number
        sin()	| It returns the sine of the given number.
        sinh()	| It returns the hyperbolic sine of the given number.
        sqrt()	| It returns the square root of the given number
        tan()	| It returns the tangent of the given number.
        tanh()	| It returns the hyperbolic tangent of the given number.
        trunc()	| It returns an integer part of the given number.