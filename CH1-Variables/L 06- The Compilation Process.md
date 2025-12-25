# THE COMPILATION PROCESS ⚙️

Computers need machine code, they don't understand English or even Go. We need to convert our high-level (Go) code into machine language, which is really just a set of instructions that some specific hardware can understand. In your case, your CPU.

The Go compiler's job is to take Go code and produce machine code, an .exe file on Windows or a standard executable on Mac/Linux.


<img width="1280" height="490" alt="rfR5MNc-1280x490" src="https://github.com/user-attachments/assets/0dd87ef7-3c47-416c-9189-b3310d5791f4" />

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# GO PROGRAM STRUCTURE 

![ThatsItYesThatsItGIF](https://github.com/user-attachments/assets/8f45501a-d9c9-45b2-a0cb-ffa5d23a8bd4)

We'll go over this all later in more detail, but to sate your curiosity:

1. **package main** lets the Go compiler know that we want this code to compile and run as a standalone program, as opposed to being a library that's imported by other programs.
2. **import "fmt"** imports the [fmt (formatting) package](https://pkg.go.dev/fmt) from the [standard library](https://pkg.go.dev/std) . It allows us to use **fmt.Println** to print to the console.
3. **func main()** defines the **main** function, the entry point for a Go program .

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 # TWO KINDS OF ERROR
 
 ![MmtErrorOldDataGIF](https://github.com/user-attachments/assets/be026331-288e-4505-84b8-1f13640df802)

 Generally speaking, there are two kinds of errors in programming:

 1. **Compilation errors**. Occur when code is compiled. It's generally better to have compilation errors because they'll never accidentally make it into production. You can't ship a program with a compiler error because the resulting executable won't even be created.
 2. **Runtime errors**. Occur when a program is running. These are generally worse because they can cause your program to crash or behave unexpectedly.

While we're in the browser it can be a bit hard to tell the difference because we run and compile the code in the same step.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


# ASSIGNMENT 📝

1. Run the code. Notice the compilation error? It's due to invalid syntax.
2. Fix the compilation error in the code.


```

package main

import "fmt"

func main() {
	fmt.Println("The compiled textio server is starting")
}

```
