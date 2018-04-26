# Hexane-Exploit-fixer-and-Optimizer

This is a basic script to stop most/all of the exploits that are publicly known at the moment. 

The ones that are not picked up on will still be logged so it will be easy to pick up on them in the future.

All the editing that needs to be done is at the top of the file. Do not go past the warning unless you know what you are doing

# Hostname Changer

Added this as someone requested it. This will change the hostname every (X) seconds as defined at the top of the file.

![Image of console for Hostname Changer](https://i.imgur.com/QFGumfV.png)

This is mostly for servers that want it to always be fresh and to try and attract more players.

You can turn this off by doing `UseHexane.HostnameToggle = false` in the config.

# Lag Exploiter checker

When someone is trying to exploit the server they will not be able to talk in chat. This is how we can pick up on them.

Doing `lag_check` in console will start a scan. ( You will need to be superadmin )

![Image of Lag Exploiter checker](https://i.imgur.com/codDiRl.png)

This is not 100% right but should give you a good head start on who it is.

You can turn this off by doing `UseHexane.LagExploitChecker = false` in the config.

If anything goes wrong with this you can turn on `UseHexane.debug = false` and give it to us and we can help out.

# Net Message Logger

Used to find exploitable backdoors. It will print the net message that is made, who made it and how many bytes were sent.

Giving this to a developer will increase the chance of a exploitable net message being patched. 

You can turn this off by doing `UseHexane.NetMessageLogger = false` in the config.

# Console Command Logger

Same as above. Sometimes people try to exploit your server by using Console Commands instead so this covers for it. 

It will log to console so give this to a developer. 

You can turn this off by doing `UseHexane.ConCommandLogger = false` in the config.

# Server side Optimizer

This will remove some hooks from the ServerSide meaning that you will get better proformance. 

You can turn this off by doing `UseHexane.OptimizerToggle = false` in the config.
