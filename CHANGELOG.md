# BazWidgetDrawers Changelog

> Renamed from BazDrawer to BazWidgetDrawers in v016. Settings are migrated automatically.

## 062 — First-install fix and Midnight API updates

**Fixed an error on first install.** Setting up the default drawer on a
fresh profile could fail because the curated widget order was not
available yet, leaving the drawer unconfigured.

**Achievement blocks open the Achievements window again.** Left-clicking
an achievement in the Quest Tracker widget now loads Blizzard's
Achievements UI if it has not been opened yet, instead of doing nothing.

**Midnight API updates.** The Zone Text widget's PvP zone colouring and
the clock loader in the Minimap Info Bar use the current APIs.

**Marked compatible with patch 12.1.0.** The addon no longer shows as out of date in the AddOns list.
