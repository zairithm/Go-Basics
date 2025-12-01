# COMMENTS 🗨️

**Go has two styles of comments:**
```
// This is a single line comment

/*
  This is a multi-line comment
  neither of these comments will execute
  as code
*/
```

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# ASSIGNMENT 📝

**The new intern on the team screwed up their documentation comment.**

**Fix the issue.**
```

package main

import "fmt"

func main() {
	/*
		We are increasing the maximum message length from 140 to 280 characters.
		Very reluctantly, I might add.
		Users actually want to write more than 140 characters?!? Madness.
	*/
	maxMessageLength := 140
	newMaxMessageLength := 280
	fmt.Println("Textio is increasing the maximum message length from", maxMessageLength, "to", newMaxMessageLength, "characters.")
}
```



```
