---
description: AI rules derived by SpecStory from the project AI interaction history
globs: *
---

## HEADERS

## PROJECT RULES

## CODING STANDARDS

## WORKFLOW & RELEASE RULES

## TECH STACK

## DEBUGGING

When encountering "WA_TranslucentBackground" access errors:

*   Ensure you are importing the attribute correctly. `WA_TranslucentBackground` is not an attribute of the `Qt` class directly from `QtWidgets`, but rather from `QtCore.Qt.WidgetAttribute` or directly from `QtCore.Qt` (depending on the PyQt/PySide version).

    *   Correct usage: `QtCore.Qt.WA_TranslucentBackground`
    *   If you are already using `from PyQt5.QtCore import Qt`, you can use `Qt.WA_TranslucentBackground`.

*   Verify the spelling: It is `translucentBg` (English), not `transluscentBg`.

## PROJECT DOCUMENTATION & CONTEXT SYSTEM

## BEST PRACTICES