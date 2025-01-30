# Database

I will implement a simple SQL database.
Yes, it would have been much easier to implement a noSQL database, but here we are.

## The interpreter

We have to start somewhere, so we will start from the SQL interpreter.
[This](https://craftinginterpreters.com/) book looks promising.

So far:

1. You have to scan for tokens in the stream of characters (lexical analisys).
2. Parse the tokens and build the abstract syntax tree

> The first bit of analysis that most languages do is called binding or resolution. For each identifier, we find out where that name is defined and wire the two together. This is where scope comes into play—the region of source code where a certain name can be used to refer to a certain declaration.
