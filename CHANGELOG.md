# BazWidgetDrawers Changelog

> Renamed from BazDrawer to BazWidgetDrawers in v016. Settings are migrated automatically.

## 063 — Minimap Buttons catches more buttons

**Buttons that don't use LibDBIcon are adopted too.** Addons that draw
their own minimap button (Vaultloom, for example) were left sitting on
the minimap ring. The widget now recognises any addon launcher button by
its size and shape, while still leaving Blizzard's own minimap controls
and map pins alone.

**Late-loading addons are picked up automatically.** The widget sweeps
again a few seconds after login, after any addon finishes loading, and
the moment LibDBIcon reports a new icon. The manual Re-scan option is
still there if you ever need it.
