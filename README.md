# DiscordCallRPC

Discord has this cool Rich Presence thing thats visible to yourself & participants when you’re in a call. So i decided to make a similar thing for everyone to see! 

### Caveats:
* Due to the limitations of the Rich Presence SDK, you can't automate the entire process.
* In order for the RPC to show, no other rich presences may be active at the time of activating the Call RPC otherwise it will override it. Once the RPC is active nothing will override it and you can do as you please.
