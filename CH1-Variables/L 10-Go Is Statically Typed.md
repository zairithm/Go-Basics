# Go Is Statically Typed

Go enforces [static typing](https://developer.mozilla.org/en-US/docs/Glossary/Static_typing) meaning variable types are known before the code runs. That means your editor and the compiler can display type errors before the code is ever run, making development easier and faster.

Contrast this with most dynamically typed languages like JavaScript and Python... Dynamic typing often leads to subtle bugs that are hard to detect. The code must be run to catch syntax and type errors. (sometimes in production if you're unlucky 😨)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Concatenating Strings

Two strings can be [concatenated](https://en.wikipedia.org/wiki/Concatenation) with the + operator. But the compiler will not allow you to concatenate a string variable with an int or a float64.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Assignment

Textio uses [basic authentication](https://en.wikipedia.org/wiki/Basic_access_authentication) to log users in.

The code on the below has a type error. Change the assignment statement on line 6 to use a string value for password instead of an integer (but don't use a different password) so that it can be concatenated with the username variable.


```
package main

import "fmt"

func main() {
	var username string = "presidentSkroob"
	var password string = "12345"

	// don't edit below this line
	fmt.Println("Authorization: Basic", username+":"+password)



}

```
