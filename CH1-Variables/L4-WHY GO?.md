# WHY GO?

![DramaticChipmunkGIF](https://github.com/user-attachments/assets/0c7d4dfc-30a8-4f8f-bbe8-9a0430235bc5)


**Go is my favorite programming language by a good margin.**

<img width="1280" height="720" alt="RxCpanC-1280x720" src="https://github.com/user-attachments/assets/46cce35c-ecb9-44aa-84b2-170a3784d30b" />


***We'll talk more about the benefits of Go later.***

But for now, let's whet your appetite with some more code.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

# ASSIGNMENTS 📝

*CRITICAL BUG!*
 
Textio users reported that we're billing them for wildly inaccurate amounts. They're supposed to be billed .02 dollars (2 cents) for each text message sent.

Without changing any of the other lines, fix the math bug on line 8.
```
package main

import "fmt"

func main() {
	numMessagesFromDoris := 72
	costPerMessage := .02
	totalCost := costPerMessage * float64(numMessagesFromDoris)
	fmt.Printf("Doris spent %.2f on text messages today\n", totalCost)
}

```
