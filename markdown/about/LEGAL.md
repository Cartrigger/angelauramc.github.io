# Legality, privacy, and security
## So is it legal?
You might want to take a look at [this note](NOTE-FROM-EVA.md) first.
As far as we know, yes. We follow all of Microsoft's rules (that we're aware of), although I can't say "yes" because I haven't spoken to their representatives since then. I'll update this page when I can get that confirmation, though.  
-- Eva

## And what about private? 
This we can say yes to. If anything, it's more private than Microsoft's official launcher. 

Amethyst doesn't have the ability to contact any servers aside from:
- Microsoft's own for authentication, game downloads, and in-game telemetry, 
- mc-heads.net to grab a sweet picture for displaying next to your account name, and
- Any you might join on your own while using it. 

You can optionally choose to send log files in the event you need help with the launcher, but that's a manual process.

## Security?
Depends on the platform, depends on your interpretation, but mostly yes.

### Platform quirks
iOS is arguably the more secure platform for Amethyst, currently, but not by much. Account details are stored in the system's keychain instead of in a json file - which means that an attacker with a sandbox escape won't immediately get your token. Both are decently secure in typical usage and for most people.

### Interpretation
Security, here, is defined by how much you trust us. Most of the non-game code is written by us or people we work with, and not always with security in mind. Additionally, the Java Hotspot VM is inherently insecure by design because of just-in-time compilation.

All of our work is open-source, and can be audited for security vulnerabilities on our [GitHub](https://github.com/AngelAuraMC). Us not having the resources to be diligent about this doesn't mean we don't accept reports from others.

### Rooting and jailbreaks
We can't guarantee security in either of these scenarios for obvious reasons, and we don't try to. If the user is running with an exploited iPhone or a rooted Android device, the walls have already been broken down and we can assume that the data is compromised - regardless of what we do to try and protect it.