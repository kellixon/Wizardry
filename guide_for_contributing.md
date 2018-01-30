# Guide for contributing to this repository

I like my code to be tidy, so it saves me time if yours is too. Here are a few general guidelines for how to submit a good PR:

- Use proper indentation and try to space your code out nicely. This really goes without saying - select all your code and hit ctrl-i before you submit it, and try to use my spacing if you can (for instance, don't do what the Minecraft source does and put a { on a separate line, it's a waste of space).

- Commented code is dead code, UNLESS it has an accompanying comment detailing an appropriate reason for it being commented. (something like "DO NOT REMOVE, commented because it will be useful in 1.12" or "DO NOT REMOVE, commented for debugging purposes, uncomment when fixed")

- Please comment your methods/fields/classes! Preferably using Javadoc, but for small/private methods one line comments are OK. I find it hard enough to remember what I wrote a method for if it isn't commented, let alone trying to work out what yours are for. That said, you should try to name the method/field/class so it's obvious what it is anyway.

- Follow naming conventions. BLOCK_CAPITALS for constants, CapitalisedWords for classes, camelCase for almost everything else.

- This isn't code related, but when you submit a PR, please tell me what it does! You don't need much, just something like "Makes item X do X" or "Fixes #162". If you're resolving an issue, put "Fixes", "Closes" or "Resolves" and then the issue number and Github will close it automatically.