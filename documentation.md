# Documentation

Base description for all oil functional.

# class Dual
This class is designed to work with the dual numbers and their functions. Contains the minimum necessary to create a dual numbers and descriptions of functions based on them.

`public new(rp,ip)`

The dual numbers class constructor. 

Creates a dual number with real part *rp* and the imaginary part *ip*. 

Constructor can take one argument (only actual or only the imaginary part), in the case of calling the constructor without parameters, will be created a real number equal to zero.

`public imagp()`

Returns the imaginary part of the number.

`public realp()`

Returns the real part of the number.

`public show()`

Returns string representation of dual number.

`public static abs(a)`

Returns absolute value.

`public static add(a,b)`

Add two dual numbers.

`public static acos(a)`

Returns arccosine.

`public static asin(a)`

Returns arcsine.

`public static atan(a)`

Returns arctangent.

`public static auto_diff(f,x)`

Automatic differentiation. 
Function for automatic differentiation must be defined in the dual number and returns with the dual number.

`public static conj(a)`

Conjugate dual number.

`public static cos(a)`

Returns cosine.

`public static div(a,b)`

Divide two dual numbers.

`public static exp(a)`

Exponentiation for dual number.

`public static log(a)`

Returns natural logarithm.

`public static log10(a)`

Returns base 10 logarithm.

`public static mul(a,b)`

Multiplicate two dual numbers.

`public static neg(a)`

Negative dual number.

`public static pow(a,b)`

Returns power for dual numbers.

`public static sin(a)`

Returns sine.

`public static sub(a,b)`

Substract two dual numbers.

`public static tan(a)`

Returns tangent.

# class Functional

`public static denested(l)`

Transforms a nested list in the usual (un-nested) list.

`public static drop(n,l)`

Returns first n elements of the list.

`public static foldl1(f,l)`

Left-associative folding of list.

`public static foldr1(f,l)`

Right-associative folding of list.

`public static idivide(l)`

Division inverse elements of list.

`public static iproduct(l)`

Product inverse elements of list.

`public static isub(l)`

Substraction inverse elements of list.

`public static isum(l)`

Sum inverse elements of list.

`public static lreverse(l)`

List reverse.

`public static napply(f,x,n)`

Returns list of n function applications to the argument.

`public static nested_level(l)`

Maximum level of nested list.

`public static partition(f,l)`

Returns a list consisting of two parts: a list of satisfying for predicate and the list is not satisfying.

`public static scanl(f,start,l)`

Left-associative list scan.

`public static scanr(f,start,l)`

Right-associative list scan.

`public static split(line,dlms)`

Splits on separator line at the list of elements.
By default, dlms equals to Tab.

`public static uniq(l)`

Returns a list consisting only of the unique elements

`public static unsplit(l,dlms)`

Transforms list of items in the string elements with separator.
By default, dlms equals to Tab.

`public static allp(f,l)`

Returns 1 if all the elements of the list satisfy the condition.

`public static anyp(f,l)`

Returns 1 if at least one item from the list satisfies the condition.

`public static nestedp(l)`

Returns 1 if the list is nested.

`public static nonep(f,l)`

Returns 1 if none of the elements of the list are not satisfies for predicate.


