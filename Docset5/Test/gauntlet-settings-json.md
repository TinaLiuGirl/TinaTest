---
title: Gauntlet - Provide options for Gauntlet VS Code Functions in settings.json
description: Allow VS Code power users to choose options for Gauntlet settings, including disabling them
keywords: Spec
author: meganbradley
ms.author: mbradley
ms.date: 05/03/2017
---
#Settings.json Options

![approved](media/approved.png)

## Feature summary

Some users, especially VS Code power users, will want the ability to change or disable some Gauntlet functionality. We should enable some options in settings.json; otherwise we might lose users who prefer to uninstall the extension. Similarly Gauntlet features should not override other custom settings the user might set.

## Scope

Goals:

- Address settings issues that have been identified as problematic by current users.

Non-goals:

- Add settings options for every function in the Gauntlet VS Code extension. More will likely come later; for now we will only prioritize those that have been requested by users.

## User cases

- [I can configure Gauntlet to use all 1s for numbered lists, or disable auto-numbering](#i-can-configure-gauntlet-to-use-all-1s-for-numbered-lists-or-disable-autonumbering)
- [I can configure Gauntlet Preview to open automatically and dock either side-by-side or in a new window](#i-can-configure-gauntlet-preview-to-open-automatically-and-dock-either-sidebyside-or-in-a-new-window)
- [Gauntlet respects my overridden whitespace settings](#gauntlet-respects-my-overridden-whitespace-settings)

### I can configure Gauntlet to use all 1s for numbered lists, or disable auto-numbering

Some writers prefer to see all 1s for ordered lists while authoring, relying on rendering to get the numbering right. This should be an option configurable in settings.json.

The following options for `listOrdered` should be available:

- `auto-increment (default)`
- `all-ones`
- `disabled` - the Gauntlet extension does not automatically continue the list - users can create lists manually or use the built-in VS Code list functionality

For `listUnordered`, we should have:

- `auto-continue (default)`
- `disabled` - the Gauntlet extension does not automatically continue the list - users can create lists manually or use the built-in VS Code list functionality

If `disabled` is configured, the list buttons are removed from the toolbar and keyboard shortcuts are disabled the next time VS Code loads.

<!--

### I can configure Gauntlet Preview to open automatically and dock either side-by-side or in a new window

Users have different preference for how to use Preview. We should add the following options:

`autoOpenPreview`:
- `true`
- `false` (default)

`docPreview`:
- `sxs` (default)
- `newWindow`
-->

### Gauntlet respects my overridden whitespace settings

Currently, if a user adds custom settings to handle whitespace, Gauntlet overrides them. This is an unacceptable experience causing users to uninstall Gauntlet.

Instead of hard-coding spacing behavior for functions such as list insertion, we should use a method to read the user's settings and add a tab or spaces accordingly.

The following settings are currently causing problems. The dev should check for all functions that might override these settings.

```
"editor.detectIndentation": false,
"editor.insertSpaces": false,
```

1. hello
2. hello
    a. test
    b. test
