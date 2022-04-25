# Sentinels of the Multiverse mod-relevant bugs
This repository is for collecting notes on bugs and issues in the digital implementation of Sentinels of the Multiverse that are relevant to mod authors. It's useful to know what things are known about to avoid repeatedly reporting the same issues and to know when something just won't be fixed. It's also useful to know workarounds other people have come up with and limitations you might not have thought about.

Unfortunately Handelabra's internal bug tracker isn't visible to us (and at any rate they wouldn't track things they don't consider a bug). Hence, this repository. Add issues you know about if they're not there if you would like to contribute.

This isn't a replacement for reporting stuff to Handelabra. If you've found something new you should let them know about it on the discord.

## Tags 

The tags you can apply to issues are:
- *Card_issue*: Some specific base-game card isn't actually implemented completedly in line with its text (this is common where the difference is either unobservable or difficult to detect without mod content). Example: Heroic Infinitor not being a villain card.
- *Engine_issue*: Some engine code does something less than ideal for mods. Example: the lack of a IsHeroTarget
- *Not_fully_general*: Some facility provided by the engine sounds like it's much more generally applicable than it actually is. Example: AskIfCardContainsKeyword only works for five specific keywords (or entirely mod-limited keywords), rather than any keyword like you might naively assume.
- *Wontfix*: Handelabra have specifically said they won't fix the issue.
