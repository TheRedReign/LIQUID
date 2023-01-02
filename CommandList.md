# LIQUID Official Command List
Hello! Every category of commands (ie, Moderation, Information), will have their own little section.
If you'd like to suggest a command, you can email the LIQUID Support Team (<liquiddiscordbot@gmail.com>), or go through LIQUID's [Community & Support Server](https://discord.gg/jZbqmT8b5D).

## Server Administration
### Set

**Options**: ("channel", "channel", "channel", "channel")

**Correct Usage**: ("/set #channel")

**Notes**: This can set 4 distinct channels for various purposes (run in Discord for better information).

## Moderation
### Ban

**Options**: ("user", "reason"),
  
**Correct Usage**: "/ban @user reason"
  
### Kick

  **Options**: ("user"),
  
  **Correct Usage**: "/kick @user"
  
### Warn

**Options**: ("user"),
  
**Correct Usage**: ("/warn @user", "/warn @user")
  
### Warns

**Options**: ("user") 
  
**Correct Usage**: ("/warns @user")
  
**notes**: This is coming soon!

### Slow

**Options**: ("seconds")

**Correct Usage**: ("/slow 5")

**Notes**: This sets a channel's slowmode in seconds (max is 21600 seconds, or 6 hours)

### Purge

**Options**: ("number")

**Correct Usage**: ("/purge 5")

**Notes**: Above 20 will use a *bulk delete* method that cannot delete messages over 2 weeks old. Delete 20 at a time to avoid this issue.

### Mute

**Options**: ("user", "minutes")

**Correct Usage**: ("/mute @user 5")

**Notes**: This uses Discord's built-in timeout functionality.
  
## Information
### Help

**Options**: ("none"),
 
**Correct Usage**: ("/help")

### Ping 

**Options**: ("none"),

**Correct Usage**: ("/ping"),

**Notes**: Displays Heartbeat & Client latency information for LIQUID.

## Fun
### Coin Flip

**Options**: ("none")

**Correct Usage**: ("/coinflip")

### Icon

**Options**: ("user")

**Correct Usage**: ("/icon @user", "/icon")
