# Development Commands
## Note: Development Commands are restricted to users whose IDs appear in the developers section of the Dozer Config file.

***

### reload:
Reloads the specified Cog

`{prefix}reload {cog name}` 

***

### eval:
Evaluates Python code. Await is valid and `{ctx}` is the command context.

`{prefix}eval await ctx.send('Hello, World!')` Sends "Hello, World!" to the channel where the command is executed.