=========
Actionlog
=========
messagelogconfig
++++++++++++++++
Set the message log channel for a server by passing the channel id
::
   `{prefix}messagelogconfig #message-logs` - set a channel named #message-logs to log message edits/deletions
    `{prefix}messagelogconfig {channel ID}` - configures the given channel ID to log messages
memberlogconfig
+++++++++++++++
Command group to configure Join/Leave logs
::
   `{prefix}memberlogconfig setchannel channel`: Sets the member log channel

    `{prefix}memberlogconfig toggleping`: Toggles whenever members are pinged upon joining the guild

    `{prefix}memberlogconfig setjoinmessage template`: Sets join template

    `{prefix}memberlogconfig setleavemessage template`: Sets leave template

    `{prefix}memberlogconfig help`: Returns the template formatting key
setleavemessage
+++++++++++++++
Configure custom leave message template
::
   
setjoinmessage
++++++++++++++
Configure custom join message template
::
   
help
++++
Displays message formatting key
::
   
toggleping
++++++++++
Toggles whenever a new member gets pinged on join
::
   
disable
+++++++
Disables Join/Leave logging
::
   
setchannel
++++++++++
Configure join/leave channel
::
   
locknickname
++++++++++++
Locks a members nickname to a particular string, in essence revoking
nickname change perms
::
   `{prefix}locknickname @Snowplow#5196 Dozer`: Locks user snowplows nickname to "dozer"
unlocknickname
++++++++++++++
Removes nickname lock from member
::
   `{prefix}unlocknickname @Snowplow#5196`: Removes nickname lock from user dozer
