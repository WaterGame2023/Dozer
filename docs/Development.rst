===========
Development (Developer Only Commands)
===========
reload
++++++
Reloads a cog.
::
   `{prefix}reload {cog name}` - reloads the development cog
eval
++++
Evaluates Python. Await is valid and `{ctx}` is the command context.
::
    `{prefix}eval await ctx.send('Hello world!')` - send "Hello World!" to this channel
su
++
Execute a command as another user.
::
   `{prefix}su cooldude {prefix}ping` - simulate user cooldude sending `{prefix}ping`
