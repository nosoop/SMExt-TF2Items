# TF2Items

Custom patches on top of [asherkin's TF2Items extension](https://github.com/asherkin/TF2Items).

## Differences

This fork adds a new forward `TF2Items_OnGetLoadoutItem`, which allows a plugin to modify the
item returned from the player's inventory.  This allows for improved implementations of things
like [Local Item Server][] by spoofing the information at the source.

(Note that items not normally compatible with the class will still be invalidated and not
applied to the target.)

[Local Item Server]: https://forums.alliedmods.net/showthread.php?p=1747762

## Installation

Copy the files to the appropriate directories.
