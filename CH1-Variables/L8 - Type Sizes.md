# TYPE SIZES 

Integers,  [uints](https://users.cs.utah.edu/~germain/PPS/Topics/unsigned_integer.html#:~:text=Unsigned%20Integers,negative%20(zero%20or%20positive).) , [floats](https://techterms.com/definition/floating_point), and [complex numbers](https://www.cloudhadoop.com/2018/12/golang-tutorials-complex-types-numbers.html) all have type sizes.

👉 **Signed integers (no decimal)**

```
int  int8  int16  int32  int64
```
👉 **Unsigned integers (non-negative numbers/no decimal)**

```
uint uint8 uint16 uint32 uint64 uintptr
```
👉 **Signed decimal numbers**

```
float32 float64
```
👉 **Complex numbers (a complex number has a real and imaginary part)**

```
complex64 complex128
```

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# WHAT'S THE DEAL WITH THE SIZES

he size (8, 16, 32, 64, 128, etc.) represents how many bits in memory will be used to store the variable. The "default" int and uint types refer to their respective 32 or 64-bit sizes depending on the environment of the user.

The "standard" sizes that should be used unless you have a specific performance need (e.g. using less memory) are:

1. *int*
2. *uint*
3. *float64*
4. *complex128*

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# CONVERTING BETWEEN TYPES 

Some types can be easily converted like this:
```
temperatureFloat := 88.26
temperatureInt := int64(temperatureFloat)

```
Casting a float to an integer in this way [truncates](https://techterms.com/definition/truncate )
the floating point portion.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ASSIGNMENT 📝 

Our Textio customers want to know how long they have had accounts with us.

On line 7, create an *accountAgeInt* variable and assign it the value of a*ccountAgeFloat* truncated to an integer.

```

package main

import "fmt"

func main() {
	accountAgeFloat := 2.6
    accountAgeInt := int64(accountAgeFloat)
	fmt.Println("Your account has existed for", accountAgeInt, "years")
}
```





