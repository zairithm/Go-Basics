# Compiled vs. Interpreted

You can run a compiled program without the original source code. You don't need the compiler anymore after it's done its job. That's how most video games are distributed! Players don't need to install the correct version of Go to run a PC game: they just download the executable game and run it.

<img width="994" height="720" alt="image" src="https://github.com/user-attachments/assets/2a6902e9-ecc3-4733-9547-90be763da1f7" />

With interpreted languages like Python and Ruby, the code is interpreted at runtime by a separate program known as the "interpreter". Distributing code for users to run can be a pain because they need to have an interpreter installed, and they need access to the source code.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Examples of Compiled Languages

1. Go
2. C
3. C++
4. Rust

## Examples of Interpreted Languages

1. JavaScript (sometimes JIT-compiled, but a similar concept)
2. Python
3. Ruby

# Why Build Textio in a Compiled Language?

One of the most convenient things about using a compiled language like Go for Textio is that when we deploy our server we don't need to include any runtime language dependencies like Node or a Python interpreter. We just add the pre-compiled binary to the server and start it up!
