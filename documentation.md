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




