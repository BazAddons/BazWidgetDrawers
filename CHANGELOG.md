# BazWidgetDrawers Changelog

> Renamed from BazDrawer to BazWidgetDrawers in v016. Settings are migrated automatically.

## 061 — Minimap Buttons stay put when clicked

Some addons (VaultLoom is the one that surfaced this) re-anchor
their own minimap button back to the minimap when you click them
to open the addon — yanking the button right out of the Minimap
Buttons widget. The widget now re-asserts ownership shortly after
each click, snapping the button back into its slot. The round
trip is fast enough that the visual yank isn't even visible.

Also: the Minimap Buttons widget is now on by default for new
installs, with a curated top-to-bottom default widget order
(Zone Text → Minimap → Minimap Buttons → Quest Tracker). Existing
profiles are unchanged.
