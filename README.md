## This plugin is obsolete

**As of the March 2023 Rust update, Rust has fixed the issue that this plugin originally solved. This plugin no longer compiles and will not be updated. This plugin can still be downloaded to review the old implementation.**

## What this plugin previously did

This plugin fixes a vanilla Rust issue where if an RC entity (such as a CCTV camera or drone) is destroyed, placing a new one and reusing the same identifier doesn't allow you to use it in computer stations where you had already saved that identifier, unless you remove it from the computer station and add it back, which is annoying. With this plugin, the computer station will automatically find the current entity matching the saved identifier, saving you some time.
